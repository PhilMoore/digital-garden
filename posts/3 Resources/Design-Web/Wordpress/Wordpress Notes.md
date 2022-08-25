
# Wordpress Notes

## Catastrophic Wordpress Failure:
Re-upload updraft files to file manager in Cpanel - to a FRESH WP install:

[https://updraftplus.com/faqs/i-want-to-restore-but-have-either-cannot-or-have-failed-to-do-so-from-the-wp-admin-console/](https://updraftplus.com/faqs/i-want-to-restore-but-have-either-cannot-or-have-failed-to-do-so-from-the-wp-admin-console/)

Manual / Auto Update options & error workarounds:

[https://wordpress.org/support/article/updating-wordpress/](https://wordpress.org/support/article/updating-wordpress/)

---

## Wordpress Speed Optimisation
Main Speed Optimisation Plugin:

[Autoptimize – WordPress plugin | WordPress.org](https://wordpress.org/plugins/autoptimize/)

### Settings to use:

Tick all settings listed below:

_Javascript_

Optimise Javascript Code

_CSS_

Optimise CSS Code

_HTML_

Optimise HTML Code

_Images_

Optimise Images (Glossy)

Load WebP in supported browsers

Lazy-load images

Also click on “Sign-up now” for/_shortpixel_/and register using clients email. Ask them for password to link their site to this for the free plan.

Make sure domain is added to shortpixel.

_Extra_

Combine and load fonts asynchronously with webfont.js

Remove emojis

Remove query strings from static resources

---

## Enable GZIP Compression on hosting

https://wpbuffs.com/enable-gzip-compression-wordpress/

### For Siteground

Add the following to ..htaccess

```
<IfModule mod_deflate.c> AddOutputFilterByType DEFLATE text/plain AddOutputFilterByType DEFLATE text/html AddOutputFilterByType DEFLATE text/xml AddOutputFilterByType DEFLATE text/css AddOutputFilterByType DEFLATE application/xml AddOutputFilterByType DEFLATE application/xhtml+xml AddOutputFilterByType DEFLATE application/rss+xml AddOutputFilterByType DEFLATE application/javascript AddOutputFilterByType DEFLATE application/x-javascript 
</IfModule>
```

.htaccess is a hidden file, gotta view File Manager with those files turned on and use the search in the top right for this file then add the code to it and save.

Here’s how:

https://www.siteground.com/kb/how_to_edit_hidden_systemfiles/

---

## Pagespeeed Insight Tips

[Google PageSpeed Insights - Scoring 100/100 with WordPress - KeyCDN](https://www.keycdn.com/blog/google-pagespeed-insights-wordpress)