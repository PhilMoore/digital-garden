
# HTML Code for Safari 15 Theme & Header Colour

Safari 15 adds a theme color for the tab bar. Safari can automatically pick a color based on the content or you can manually set the color with a meta tag.

```
<meta name="theme-color" content="#1a5d8d">
```


### Safari 15 Tab Bar Color
The Safari team at Apple have long been following a design trend of reducing the emphasis on the browser chrome to **“defer to the content”**. In Safari 15 that includes a more compact browser tab layout and having the tab bar take its color from the content.


### Setting The Theme Color
You can manually set the tab bar color if you don’t like the choice Safari is making. Add a meta tag in the HTML head with the name “theme-color” and the color you want to use in the content:
```
<head>
  <meta name="theme-color" content="#1a5d8d">
</head>
```


If you want a different color for light and dark color schemes use media queries:
```
<head>
  <meta name="theme-color" content="#1a5d8d"
   media="(prefers-color-scheme: light)">
  <meta name="theme-color" content="#06568F"
   media="(prefers-color-scheme: dark)">
</head>
```