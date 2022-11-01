
# Shopify - Showcase Theme Notes

## Product Description
-   [Showcase Shopify Product Page](https://themes.shopify.com/themes/showcase/)
-   [Showcase Theme Documentation](https://support.cleancanvas.co.uk/showcase-theme-support/)


[Adding Swatches Documentation](https://support.cleancanvas.co.uk/swatches-faq/?theme=showcase)


## Moore Design Text On Footer

Look for **copyright** in footer
```
<span class="copy">&copy; {{ "now" | date: "%Y" }} <a data-cc-animate-click href="{{ routes.root_url }}">{{ shop.name }}</a>.</span>

<span class="copy">Created by <a href="http://mooredesign.co/" target="_blank" title="Moore Design Website" rel="noopener noreferrer">Moore Design</a>.</span>
```