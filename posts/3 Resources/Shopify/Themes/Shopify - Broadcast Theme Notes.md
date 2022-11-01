
# Shopify - Broadcast Theme Notes

## Product Description
[Broadcast Theme Documentation](https://broadcast.invisiblethemes.com/about-broadcast/master)


### Remove Read More
-   Visit the "product-tabs.liquid" file
-   Find and remove `data-truncated-holder` (there should be 2 – one for tabs and one for accordion)
-   Save

_Video walkthrough:_ [_https://www.loom.com/share/5e6d99f38ef34b719cd0257cfd9f8564_](https://www.loom.com/share/5e6d99f38ef34b719cd0257cfd9f8564)


## CSS Changes
Product Padding On Collection Pages

```
  .product-item--borderless {
    margin-bottom: 20px;
    padding-right: 8px;
    padding-left: 8px;
  }
```

Bolder Button Text

```
.btn, .button {
 font-weight: var(---font-weight-heading);
}
```

Collection Hero - Less Padding on Mobile
```
@media only screen and (max-width: 749px){
.hero__content {
  padding: 20px !important;
} }
```

Heading hover menu - Less top spacing
```
.header__dropdown.is-visible, .menu__item:not(.grandparent):hover>.header__dropdown {
  margin-top: -15px !important;
}
```



## Create Filters on Collection
[https://broadcast.invisiblethemes.com/collections/filtering](https://broadcast.invisiblethemes.com/collections/filtering)


## Moore Design Text On Footer
Enter Under "Remove the following line to delete Shopify credit"

```
 <li data-powered-link>Created by <a href="http://mooredesign.co/" target="_blank" title="Moore Design Website" rel="noopener noreferrer">Moore Design</a></li>
```


### Fix Announcement Bar Displaying Over Mobile Menu
```
.drawer__content {
    z-index: 6001;
  }
```


## Hide Product Page Configurator / Add to Cart Bar
```
.cart-bar.is-visible {
visibility: hidden !important;
}
```