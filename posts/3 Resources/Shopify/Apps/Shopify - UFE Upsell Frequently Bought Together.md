
# Shopify - UFE Upsell Frequently Bought Together

### How to manually set the position of the app using Custom HTML

[https://helpdesk.helixo.co/how-to-place-a-widget-in-a-custom-position](https://helpdesk.helixo.co/how-to-place-a-widget-in-a-custom-position)


### **METHOD 2 (In Shopify Homepage)**
Go to Shopify admin > Online Store > Themes > Customize

Select Add section>Custom HTML>Custom HTML

-   Clear the content in the HTML text box
-   add `<div class="ufe-custom-upsell"></div>` and click `save`    

Ensure position of app is `.ufe-custom-upsell` and set to after.


---

### Making the widget full within its section
Go to Edit widget > Widget settings > Design and paste code in the Additional CSS Styles

```
.ufe-wrap {
margin: 0px;
}
.ufe-widget .upsellWrapper.ufe-normal .upsellContent .upsellPrice.ufe-price {
margin: 5px 0px 5px 0px;
}
.ufe-style-inpage .ufe-wrap {

max-width: 626px;

}
```


## Adding a Button style to the pop-up product bundle

```
.ufe-next-prev-wrap {  
position: absolute;  
bottom: 50%;  
right: 12px;  
background: #111111 !important;  
padding: 0px;  
width: 11% !important;  
height: 50px;  
transform: skew(-12deg);  
}  
.ufe-next-prev-wrap .ufe-popup-next {  
display: inline-block;  
transform: skew(12deg);  
top: 0%;  
padding-top: 10px;  
}  
.ufe-next-prev-wrap .ufe-popup-next:hover, .ufe-next-prev-wrap .ufe-popup-prev:hover {  
background: unset;  
}

```