# **Animations**

**Circle BG’s:**

grow / shrink on page scroll from corners, edges, middles of sections.

**Text**

Slider & hero text lines fade in sequence 1,2,3

**Headings**

Body text

Fade in & out on page scroll position

ZEUS [https://webflow.com/templates/html/zeus-fitness-website-template](https://webflow.com/templates/html/zeus-fitness-website-template)

scroll into view

Offset 7%

No out of view set

Div block for sections content

Div block conteinr for heading elements with overflow HIDDEN with no other settings, can be used EVERYWHERE.

so animations become visible INTO that space only and look like they are sliding in

💡is it possible to do this with text span overflow hidden?? (line1, line2, line3)

-   Initial state:  
    items moved down so they're not in view (hidden by overflow HIDDEN)
    

They also have a coloured block "into view fill"

which covers the area with SCALE 100% 100% and then gets SCALE set to 0

🌶 ONLY CHILDREN with this class so individual elements are triggered only and not everyhting at once!

Roby: [https://webflow.com/templates/html/roby-creative-website-template](https://webflow.com/templates/html/roby-creative-website-template)

floats up

![](https://images.amplenote.com/af0d34e0-1ddb-11ed-974f-926469fcc030/9666f453-1adb-4c38-a0fe-108c3a8a9117.png)

add more delay to have other items at diff rates - good for hero as you get a big chunk initially on screen

otherwise make it faster or 0!

Grow in (can do the same with scale i guess)

item 1 | item 2 | tem 3|

delay: 100ms | 200ms | 300ms

![](https://images.amplenote.com/af0d34e0-1ddb-11ed-974f-926469fcc030/82ed659c-27da-47c8-b153-677c3c6f11ba.png)

while scrolling into view:

![](https://images.amplenote.com/af0d34e0-1ddb-11ed-974f-926469fcc030/7ec578a5-1297-49a1-9495-4e73b02ab8b6.png)![](https://images.amplenote.com/af0d34e0-1ddb-11ed-974f-926469fcc030/d6f570d1-aa65-45fd-87bd-df45a0a8f7fa.png)

Needs seperate CMS collection lists for each item thougth

fun options

Mouse X & Y axis on hover