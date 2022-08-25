
# Add A Custom Font to Shopify

[https://ecomexperts.io/blogs/liquid-tutorial-shopify/shopify-font](https://ecomexperts.io/blogs/liquid-tutorial-shopify/shopify-font)
[https://www.youtube.com/watch?v=G-aqNl6mTqc&t=732s](https://www.youtube.com/watch?v=G-aqNl6mTqc&t=732s)


**Step 1**   
Download the webfont version of your font. The font files must include at least the **WOFF** and **WOFF2** file types (TTF or OTF are not a webfont file types).


**Step 2**  
From your Shopify Admin go to Online Store > Themes > next to the theme you want to edit click Actions > Edit Code. In the sidebar choose **Assets** > theme.scss.liquid**.** Scroll to the bottom of the file and paste the following code…  


```
 _@font-face {_  
_font-family: "NAME OF FONT";_  
_src: url("NAME-OF-FONT-FILE.woff2") format("woff2"),_  
_url("NAME-OF-FONT-FILE.woff") format("woff");_  
_} 
```


Replace NAME OF FONT with the name of your font and NAME OF THE FONT FILE with the exact name (casesensitve with hyphens) of the font file on your computer.

Below this code also paste the following code…  

```
_<p><span style="font-weight: 400;">yourcssselectorhere { font-family: "NAME OF FONT"!important; }</span></p>_ 
```


**Step 3**  
Go to the Assets folder and click **Add a new asset.** Upload each version of the font file one by one.


**Step 4**  
Now that the font is installed, using code we need to tell the theme what headings or text will use our new font. In a new browser tab go to your website and find the heading or text you want in this font, in this example it is a heading. Right-click on the words and select **Inspect**.

A window will pop up showing you the code of the site. Look in the right-hand column for the CSS code that is styling your heading. In the example above you will see on the left, highlighted in grey, the heading is an <h2> and on the right the CSS property selector for the heading is h1, .h1, h2, .h2, h3, .h3, h4, .h4, h5, .h5, h6, .h6. Click the property name and copy the text.

Go back to the browser tab with the theme code editor and open the theme.scss.liquid file again. Select the words that say "your CSS selector here" and paste what you have already copied. Then replace "NAME OF YOUR FONT" with the name you used before.

Save your changes, refresh your website and have a look at your custom font.

E.g.
![](https://images.amplenote.com/32e37528-0f03-11ed-a1b4-7eb08a2c5cd0/7348c971-58e1-46a0-808a-9a5e4d175b99.jpg)