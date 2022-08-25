
# Web Design Notes

[Digitalmarketer.com](http://digitalmarketer.com/) - landing page audit

## BEM Naming Conventions - How to Name Classes in Webflow
[Class naming 101: BEM | Webflow Blog](https://webflow.com/blog/class-naming-101-bem?utm_campaign=May02018&utm_source=newsletter&utm_medium=email)


## Landing Page Design
[How to Design a Landing Page - Knowledge Base Articles | Balsamiq](https://balsamiq.com/learn/resources/articles/landingpages/)

_General Design Notes_

Max width for div containers on desktop _991px_

_100% width - Max 1080px for a section with padding. 1600px for the how section._

_Tips:_

VH = Viewpoint Height. So 100 VH will make the div cover the whole height of the page.

_Width & Percentages_Its ok to enable percentages on images if the container has the image info hard coded.

_Button Icons_

If there is some sort of icon going inside a button, you must always set the padding explicitly to 0 on all sides.

Then use flex-box to center the icon.

_Modals_

1.  (On Desktop - and possible Mobile as well, I’ll have to check) the Modal cannot exceed 1 full screen size (height & width). For desktop it must be contained within 1 full screen (we might be able to use a different overflow setting like overflow: scroll on mobile to still contain it within 1 screen size). The reason is because if it does not, you’ll be able to scroll down, and the black 75% opacity background will end, but the page behind it will still shine through. So to avoid this, you have to always set the position: fixed of the modal’s div container, then ensure the the modal is contained inside 1 screen width. That way when the user does scroll, only the background display will move, and the modal itself will not.
2.  The Navbar was set to a z-index: 20 so I increased the modals to a z-index: 30. This also required me to adjust the distance from top to only 50px rather than 150px. This adjustment also greatly helped with keeping the overall body size of the modal to within 1 screen. The main takeaway is that we just need to remember our Navbars in the future, and all modals should be at a z-index that is greater than the navbar.

_Drop downs:_

Need position absolute not relative.