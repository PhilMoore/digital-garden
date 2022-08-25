# Holgro - User log in content restriction redirect & User restricted menus.

Trying to remove content restriction redirect from homepage & other oages

Redirect tickbox on page editor mode is not affecting it.

Found code in functions.php to redirect:

However this code seems like it was never complete, so may have been creating a conflict with the tickbox option.

```
/* If a user IS logged in, tell WordPress to use 'page' on front page of the site:
this will load whatever home page has been set in settings.     */

    function fn_set_page_as_front_for_loggedin_user( $value ) {
        if ( is_user_logged_in() ) {
            $value = 'page';
            //page is set as front page
        }
        return $value;
    }
    add_filter( 'pre_option_show_on_front', 'fn_set_page_as_front_for_loggedin_user' );

    /* If user is NOT logged in, set a static page to act as home page */
    function fn_set_context_based_page_on_front( $value ) {

        if( ! is_user_logged_in() ) {
            return $value;
        }

        //for logged in user, use page id - in this case 56
        return 3581;
        //change with your own page id.
    }
  add_filter( 'pre_option_page_on_front', 'fn_set_context_based_page_on_front' );
```

After removing this code from functions.php the tickbox now works as intended to restrict or unrestrict content.

Content Enabled without login:

home

Academy

courses

mind

body

business

'All content'

Events is being restricted but not sure where - is different to other restricted pages.

restriced page looks like this:

![](Holgro%20%7C%20User%20log%20in%20content%20restriction%20redirect%20&%20User%20restricted%20menus..assets/Screenshot%202022-02-24%20at%2012.54.49.png)

Is auto created page from events plugin so settings are different.

Need to replace this function with something better anyway, so have removed from left menu.

**Menu for logged in/ not logged in users**

Created new menu for logged out users only, re-named regular menu for logged in members only.

Added below code to functions.php theme file to display seperate menus for logged in & non-logged in users.

```
/* Display Seperate Menus for Logged In & Logged Out Members */

function my_wp_nav_menu_args( $args = '' ) {
 
if( is_user_logged_in() ) { 
    $args['menu'] = 'Top Menu Logged In';
} else { 
    $args['menu'] = 'Top Menu Logged Out';
} 
    return $args;
}
add_filter( 'wp_nav_menu_args', 'my_wp_nav_menu_args' );
```

[How to Show Different Menus to Logged in Users in WordPress](https://www.wpbeginner.com/wp-themes/how-to-show-different-menus-to-logged-in-users-in-wordpress/)