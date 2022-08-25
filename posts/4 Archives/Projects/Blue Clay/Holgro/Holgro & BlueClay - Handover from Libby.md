
# Holgro & BlueClay | Handover from Libby

# Laticia Meeting Notes 27/05

## Godaddy Login:

![](https://images.amplenote.com/0e1b43ac-de6a-11ec-a6de-f2e2bc5c6b4b/e01423af-0b1b-43ab-8c6b-814c006aee96.jpg)

## Ventra Login

![](https://images.amplenote.com/0e1b43ac-de6a-11ec-a6de-f2e2bc5c6b4b/7ede6996-d6bc-4eb6-8061-b4eaf672e8d3.jpg)

![](https://images.amplenote.com/0e1b43ac-de6a-11ec-a6de-f2e2bc5c6b4b/fd0f3c73-506b-490b-9cc0-231801e6ef83.jpg)

---

## Meeting Agenda 04/06:

1.  [Holgro & BlueClay | Handover from Libby#Mailchimp Tags](https://www.amplenote.com/notes/0e1b43ac-de6a-11ec-a6de-f2e2bc5c6b4b#Mailchimp_Tags)
    
2.  [Partners](craftdocs://open?blockId=086902BF-CAB8-441E-A8CF-BD63A44F12DC&spaceId=f6a9e1c6-4f77-f92c-8adb-df6d1abfdc4b)
    
3.  [Holgro | Demo Site](https://www.amplenote.com/notes/0d90ee14-de6a-11ec-a6de-f2e2bc5c6b4b)
    
4.  Walk through adding BLUECLAY google drive to UpdraftPlus with Laticia / or get login to do it ourselves.
5.  email notifications for member sign ups have been swapped to moore design

**G-drive needs to be linked to UPDRAFT on 5 websites:**

1.  blueclay
2.  holgro.com
3.  holgro.me
4.  toomey family law
5.  country change

---

### Holgro Site Core Functions

### [**Holgro | Members**](craftdocs://open?blockId=8BCF8B51-B97F-438E-B960-8B3DBE9DC09B&spaceId=f6a9e1c6-4f77-f92c-8adb-df6d1abfdc4b)

Member types:

-   [Partners](craftdocs://open?blockId=086902BF-CAB8-441E-A8CF-BD63A44F12DC&spaceId=f6a9e1c6-4f77-f92c-8adb-df6d1abfdc4b)
    
-   Champions
-   Members (subscription tiers in future)

### [Courses, Learning & Mentoring](craftdocs://open?blockId=3CE5E934-1A24-43C2-B451-B7CE9088D58C&spaceId=f6a9e1c6-4f77-f92c-8adb-df6d1abfdc4b)

-   **Courses**
    
-   Blog posts are ‘topics’ for learning
-   [1:1 Mentoring](craftdocs://open?blockId=46381159-C31D-4E05-AC6A-8DFA8FFDF90B&spaceId=f6a9e1c6-4f77-f92c-8adb-df6d1abfdc4b)
    

### Social

-   Profiles
-   Groups
-   Forums
-   Chat

---

### [Plugins & Theme](craftdocs://open?blockId=204C8FD7-AC36-498B-BFBD-A8D12C5C914C&spaceId=f6a9e1c6-4f77-f92c-8adb-df6d1abfdc4b)

SET UP FLOW CHART / DOCCUMENT / list Plugins intercations/ functions etc

---

### Mailchimp Tagging Holgro .me & .com

# Mailchimp Tags

# **R&D Timeline:**

**28/05**

issue raised - requiring tag data to be passed to mailchimp from membership sign up page on holgro.me and newsletter sign up/other forms on holgro.com

**31/05**

1h research

looking into current set ups & options for both sites. discovered current plugin set up is not ideal for needs.

holgro.com using MC4WP instead of gravity mailchimp add on reduces functionality options, doesn’t allow tagging in the way we need.

holgro.me mailchimp tagging needs to happen at memberhsip sign up level. further research required for plugin options that allow this or getting devloper to program in required functions.

**01/06**

Option to create seperate lists for members and newsletters instead, but would still have the same tagging Issues with membership sign up level data collection.

**02/06**

Full tagging & list requirements decided & clarified

**09/06**

Discussed needs with developer to code in passing of data to required places on member sign up.

discovered gravity add on for membership sign up which integrates with buddypress, mailchimp & more.

**10/06**

Discussing switching CRM from mailchimp to Active Campaign. From our experience Mailchimp is not a great CRM and does not allow for the deep segmentation of our audience and automation of marketing that is offered by Active Campaign.

Pausing following this mailchimp tags task until new system is decided /set up.

Spent, 30min comparing pricing tiers of Mailchimp and AC and seeing the benefits and drawbacks of each system. Also looking into gravity form integration and compatibility.

---

# Research links & notes

### Gravity forms plugin for member sign ups!!

[Using the User Registration Add-On - Gravity Forms Documentation](https://docs.gravityforms.com/user-registration-add-on/)

# issue:

requires elite lisence to use the add-on we need!

[User Registration - Gravity Forms](https://www.gravityforms.com/add-ons/user-registration/)

might be better to get developer to program this instead

drawback of this is things may get broken when updates to plugins and wp-core are done & require fixing.

# Requirements:

The most recent LMS subscribers have auto feed into Mailchimp so I can confirm that part is working.

Tagged all LMS member subscribers as 'members' in Mailchimp to distinguish between our many subscribers.

> **Is it possible to make all** [**HOLGRO.me**](http://HOLGRO.me)** LMS subscribers be feed into Mailchimp with the 'member' tag? And any** [**HOLGRO.me**](http://HOLGRO.me)** or** [**HOLGRO.com**](http://HOLGRO.com)** newsletter subscribers be feed into Mailchimp with the 'newsletter' tag?**

This would help immensely as we are currently emailing stakeholders, partners, newsletters and members with completely different email formats and content. We are also kick starting the automated triggers in Mailchimp so need a clear way to identify new member subscribers. Our automated trigger is set for new subscribers tagged as 'member':

![](Holgro%20&%20BlueClay%20%7C%20%20Handover%20from%20Libby.assets/Screen%20Shot%202021-05-28%20at%208.56.48%20pm.png)

> Is the development focus .com or .me or both?

.Me is the core focus - .com is the secondary one.

With where we are taking the holgro side - the important element is the data integrity and the insights we get from this data.

F

### Front end [holgro.me](http://holgro.me) sign up:

Must fill fields:

-   First name
-   Last name
-   email address
-   Postcode (becomes a segment in list)
-   Automatically signed up as 'subscriber" (which sends subscriber updates) tag for this can be “holgro member" not subscriber.
-   Untick/tick option - sign up to a monthly newsletter with offers, events and updates - Newsletter can be a specific type of tag for subscriber

-  Must select, which best describes you? Can select more than one

> are these to be added as 'groups’ in mailchimp? -(groups in mailchimp are different to tags)

Yes, on mailchimp there is holgro stakeholders (using to make contact with stakholders and log notes with communication with them) and holgro members and holgro subscribers which are signed up from the .com and .me side.

-   Business owner (0-20 team members/staff)
-   Business owner (21-100 team members/staff)
-   Business owner (200 + team members/staff)
-   Student
-   Industry Stakeholder
-   Professional (practising in the area of physical/body health & services)
-   Professional (practising in the area of mental health & services))
-   Professional (practising in the area of business health & services)
-   Other - please describe

> **Holgro.me** - users are subscribing when they **sign up as a Member**. we need to look into how to change the member sign up form and intergrate with mailchimp. (this is a different system to gravity forms)

### Front end [holgro.com](http://holgro.com) sign up (automatically tags as newsletter updates)

-   First name
-   Last name
-   email address
-   Postcode (becomes a segment in list)

-  Must select, which best describes you? Can select more than one

-   Business owner (0-20 team members/staff)
-   Business owner (21-100 team members/staff)
-   Business owner (200 + team members/staff)
-   Student
-   Industry Stakeholder
-   Professional (practising in the area of physical/body health & services)
-   Professional (practising in the area of mental health & services))
-   Professional (practising in the area of business health & services)
-   Other - please describe

> are these to be added as 'groups’ in mailchimp? - these are different to tags

> Is there a membership signup for holgro.com?

.com site is only a landing page that connects you to the .me site for everything. only form on .com is a newsletter form.

**Need to update this form so they are tagged a E-NEWS**

> Is the mailchimp tagging for this happening at the membership signup level or the newsletter signup form?

happening on both ideally

> **Holgro.com** - users are signing up on the sign up forms. so we can use the [Gravity Forms Mailchimp Addon](https://www.gravityforms.com/mailchimp-v44/) which requires a gravity forms lisence.

### Forms found on Holgro.com

![](Holgro%20&%20BlueClay%20%7C%20%20Handover%20from%20Libby.assets/Screenshot%202021-06-01%20at%2016.18.19%20(2).jpeg)

![](Holgro%20&%20BlueClay%20%7C%20%20Handover%20from%20Libby.assets/Screenshot%202021-06-01%20at%2016.19.26%20(2).jpeg)

# Research, solutions, documentation

**ON BLUE CLAY** they have the actual gravity forms mailchimp addon which allows TAGS to be assigned through the forms.

We can use this where sign ups are happening through gravity forms.

but NOT through membership sign up form on holgro.me

requires gravity forms licence

![](Holgro%20&%20BlueClay%20%7C%20%20Handover%20from%20Libby.assets/Screenshot%202021-06-03%20at%2012.18.36.jpeg)

[MailChimp Add-On v4.4 Released - Gravity Forms](https://www.gravityforms.com/mailchimp-v44/)

![](Holgro%20&%20BlueClay%20%7C%20%20Handover%20from%20Libby.assets/Screenshot%202021-06-01%20at%2016.35.26.jpeg)

# Holgro.me

**Member Sign Up > Mailchimp List**

youzify documentation:

[KaineLabs](https://kainelabs.ticksy.com/article/16341/)

When members sign up they are added to the mailchimp list

These are the setting for Youzify for members & mailchimp sign ups.

This Is the API key and list ID being used currently for [Holgro.me](http://Holgro.me) new members:

![](Holgro%20&%20BlueClay%20%7C%20%20Handover%20from%20Libby.assets/Screenshot%202021-05-31%20at%2013.47.29.jpeg)

I can't find an obvious way to add a tag to a new member or edit the member sign up form yet.

**Newsletter Subscription:**

Can’t find a newsletter only sign up form on this site.

# Holgro.com

For [Holgro.me](http://Holgro.me) it is set up a little differently, as it's done through the contact forms.

If you create the tag 'newsletter' then I can assign it to be added to whoever signs up or completes the forms on here.

![](Holgro%20&%20BlueClay%20%7C%20%20Handover%20from%20Libby.assets/Screenshot%202021-06-01%20at%2017.09.26.jpeg)

[https://www.mc4wp.com/kb/adding-tags-to-mailchimp-subscribers/](https://www.mc4wp.com/kb/adding-tags-to-mailchimp-subscribers/)

should be simple. but.

we are using gravity forms and custom tick boxes to add subsribers.. not the MC4WP forms.

If we create the form in mCWP we can add a tag.. no problem… e.g:

![](Holgro%20&%20BlueClay%20%7C%20%20Handover%20from%20Libby.assets/Screenshot%202021-06-01%20at%2017.18.54.jpeg)

**MC4WP Intergrations**

![](Holgro%20&%20BlueClay%20%7C%20%20Handover%20from%20Libby.assets/Screenshot%202021-06-01%20at%2016.14.49.jpeg)

1.  **Custom:**
    

no tag option

![](Holgro%20&%20BlueClay%20%7C%20%20Handover%20from%20Libby.assets/Screenshot%202021-06-01%20at%2016.16.54.jpeg)

This is being used to add the checkbox to the forms?

1.  **Gravity Forms:**
    

![](Holgro%20&%20BlueClay%20%7C%20%20Handover%20from%20Libby.assets/Screenshot%202021-06-01%20at%2016.18.19%20(2).jpeg)

![](Holgro%20&%20BlueClay%20%7C%20%20Handover%20from%20Libby.assets/Screenshot%202021-06-01%20at%2016.19.26%20(2).jpeg)

---

### [Site UI / UX](craftdocs://open?blockId=EEF88F58-C70C-489D-A25C-8DDDBEAF10CD&spaceId=f6a9e1c6-4f77-f92c-8adb-df6d1abfdc4b)

---

**Info from libby:**

I explained to Laticia that all premium plugins I provided via my developers licences for free. I did this so she wouldn’t have to pay for them whilst [Holgro.me](http://Holgro.me) was under development and I also do it for sites that are on maintenance plans with me. Now that that has ceased, she will have to sort it out herself, there is nothing that has to be transferred as none of them were paid for. In order to access updates, ::the plugins will have to be manually updated with your own developer versions as I did, or licenses will have to be purchased.::

I have kept what theme licences I can in place (ones that can be used multiple times) however single use licences will require purchase, I believe that is only the case on [Holgro.com](http://Holgro.com) though. Budget was very tight for the build of that site, so a licence was not included, it was one of many ways I was forced to keep the $$ down. I was also never paid to do maintenance on [Holgro.com](http://Holgro.com) anyway.

Finally, there is no theme licence for the CC website, I didn’t build that site, someone else did and they never bothered to include the Envato API, they also never bothered to create a child theme, it’s a bit of a mess so I’ve just done what I could with it.

I’m not going to list all the plugins etc for all of these sites and which ones are premium or not… that would take ages and if you don’t know already, you’ll just have to work it out yourself I’m afraid. When the ::updates fails, its because it’s a premium plugin with no licence.::

Someone from codeable would likely be familiar with all of the plugins etc straight up, or if not would have the experience and skills to take over straight away.

[Hire the Best Freelance WordPress Developers - Vetted by Codeable](https://codeable.io/)

Wordpress freelance developers

---

## Holgro Handover

[ขอแนะนำ Google ไดรฟ์ - ที่แห่งเดียวสำหรับไฟล์ทั้งหมดของคุณ](https://accounts.google.com/ServiceLogin?service=wise&passive=1209600&continue=https://drive.google.com/drive/folders/15ySi6BmwKCj0re_QZu-O2hNdVRjYgHsi?usp%3Dsharing&followup=https://drive.google.com/drive/folders/15ySi6BmwKCj0re_QZu-O2hNdVRjYgHsi?usp%3Dsharing)

## Holgro R&D

Document journey

Date > this is what we did > this is what what worked, what dident > this is where we can improve or change.

---

## Holgro Mock Site Access

Need link and details to access the mock site the previous developer created

This was a site a developer had created to show what we want holgro to be able to do in the future

**Q For Laticia:** If you don't know how to acess this, Can you give us Cpanel access for Holgro.me so we can check this out? - This should be through your web host if youre not sure

**Info from Libby:**

The link is here: [https://demo.holgro.me/login/](https://demo.holgro.me/login/) and you can find everything you need for it though within cpanel.

It has been added as a subdomain under [Holgro.me](http://Holgro.me)

[VentraIP Australia | 100% Australian Web Hosting & Domain Names](https://ventraip.com.au/)

added user acess

---

## Website takeover & maintenance

# Backups

COUNTRY CHANGE NEEDS GRAVITY LISENCE:

& maybe slider rev. check if they need premium.

![](Holgro%20&%20BlueClay%20%7C%20%20Handover%20from%20Libby.assets/Screenshot%202021-06-14%20at%2012.48.30.jpeg)

![](Holgro%20&%20BlueClay%20%7C%20%20Handover%20from%20Libby.assets/Screenshot%202021-06-14%20at%2012.49.42.jpeg)

TOOMEY needs gravity lisence:

![](Holgro%20&%20BlueClay%20%7C%20%20Handover%20from%20Libby.assets/Screenshot%202021-06-14%20at%2012.51.17.jpeg)

15/06  
TOOMEY FAMILY LAW

-   updating parent theme breaks child theme
-   wp-admin/.rnd - file found in wordfence. this file is CREATED BY UPDRAFT and is fine.

**Backup Folders Paths:**

Moore Design/Clients/Blue Clay/

CLIENT WEBSITE BACKUPS/

TOOMEY FAMILY LAW/2021

COUNTRY CHANGE/2021

BLUE CLAY/2021

HOLGRO

/HOLGRO.ME/2021

/HOLGRO.COM/2021

![](Holgro%20&%20BlueClay%20%7C%20%20Handover%20from%20Libby.assets/Screenshot%202021-06-14%20at%2012.11.57.jpeg)

[laticia@blueclay.com.au](https://laticia@blueclay.com.au)

Updraft does not work with a shared folder.

It just creates the same folder again.

we copied the file path of the shared folder, placed into our drive:

Moore Design/Clients/Blue Clay/CLIENT WEBSITE BACKUPS/CLIENT NAME/2021

I linked Toomey Family Law with the shared drive folder you made.

But Updraft just ignores the shared folder and replicates the file path in our drive instead of using the shared folder of the same name.

[I looked into it](https://updraftplus.com/feature-requests/request/google-drive-shared-drive/), and using shared folders form another account is just not something Updraft supports right now unfortunately.

So, we will either need to share the new folder from our drive to you, or the folders will need to be linked from your google account directly.

let u know how you'd prefer to do it, either way is fine :)

I will wait to link the other sites until you let us know how you'd like to do it.

![](Holgro%20&%20BlueClay%20%7C%20%20Handover%20from%20Libby.assets/Screenshot%202021-06-04%20at%2016.16.55.jpeg)

# Linking GDrive in Updraft Instructions

1.  log in to site and go to the backend bdashboard

![](Holgro%20&%20BlueClay%20%7C%20%20Handover%20from%20Libby.assets/Screenshot%202021-06-07%20at%2010.12.53.jpeg)

1.  From the dashboard, find the ‘settings’ menu and select ‘UpdraftPlus Backups’

![](Holgro%20&%20BlueClay%20%7C%20%20Handover%20from%20Libby.assets/Screenshot%202021-06-07%20at%2010.06.47.jpeg)

1.  In the Updraft screen, click on ‘Settings’ You have multiple things to make sure are ticked & entered correctly here.

![](Holgro%20&%20BlueClay%20%7C%20%20Handover%20from%20Libby.assets/Screenshot%202021-06-07%20at%2010.08.57.jpeg)

1.  further down within ‘settings’ will be the options for Google Drive

![](Holgro%20&%20BlueClay%20%7C%20%20Handover%20from%20Libby.assets/Screenshot%202021-06-14%20at%2012.11.57%20(2).jpeg)

Moore Design/Clients/Blue Clay/CLIENT WEBSITE BACKUPS/CLIENT NAME/2021

BLUE CLAY MAIN FOLDER/CLIENT WORK/CLIENT WEBSITE BACKUPS/CLIENT NAME/2021

BLUE CLAY MAIN FOLDER/CLIENT WORK/CLIENT WEBSITE BACKUPS/BLUE CLAY/2021

BLUE CLAY MAIN FOLDER/CLIENT WORK/CLIENT WEBSITE BACKUPS/HOLGRO/HOLGRO.COM/2021

BLUE CLAY MAIN FOLDER/CLIENT WORK/CLIENT WEBSITE BACKUPS/HOLGRO/HOLGRO.ME/2021

BLUE CLAY MAIN FOLDER/CLIENT WORK/CLIENT WEBSITE BACKUPS/COUNTRY CHANGE/2021

BLUE CLAY MAIN FOLDER/CLIENT WORK/CLIENT WEBSITE BACKUPS/TOOMEY FAMILY LAW/2021

![](Holgro%20&%20BlueClay%20%7C%20%20Handover%20from%20Libby.assets/Screenshot%202021-06-07%20at%2010.09.21.jpeg)

4.2. next, make sure the boxes are ticked as in this screenshot

![](Holgro%20&%20BlueClay%20%7C%20%20Handover%20from%20Libby.assets/Screenshot%202021-06-07%20at%2010.09.21%20copy.jpeg)

![](Holgro%20&%20BlueClay%20%7C%20%20Handover%20from%20Libby.assets/Screenshot%202021-06-07%20at%2010.10.00.jpeg)

1.  you can then go ahead and click save, which will promt you to authorise through your google account. If you are using google chrome, make sure you are logged in to the right account already to make things easier!

This video will guide you through what to eexpect at this stage, but is fairly straighforward :)

[How to add Google Drive to your UpdraftPlus account settings - UpdraftPlus](https://updraftplus.com/how-to-add-google-drive-to-your-updraftplus-account-settings/)

[Monthly Retainers](craftdocs://open?blockId=8BC62FA8-576A-4ECD-A6CC-CB374F849195&spaceId=f6a9e1c6-4f77-f92c-8adb-df6d1abfdc4b)

-   Blue Clay
-   Country Change
-   Toomey Family Law

Maintainence per hour until we know time average / work out handover kinks

-   Holgro.me
-   Holgro.com

Future Maintainence Client

-   Barns Lane Farm

> Libby manages the hosting for Country Change