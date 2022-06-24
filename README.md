<p align="center">
    <img width="100%" src="readme-files/readme-images/readme-banner.jpg">
</p>

![GitHub contributors](https://img.shields.io/github/contributors/phloreenm/MP1-CultureCoffee-CI-CoBC-FM)
![GitHub last commit](https://img.shields.io/github/last-commit/phloreenm/MP1-CultureCoffee-CI-CoBC-FM)
![GitHub language count](https://img.shields.io/github/languages/count/phloreenm/MP1-CultureCoffee-CI-CoBC-FM)
![GitHub top language](https://img.shields.io/github/languages/top/phloreenm/MP1-CultureCoffee-CI-CoBC-FM)

# **Table of Contents**
1.  [**About the site**](#about-the-site)
    * [**Link to live website**](#link-to-live-website-is-here)
    * [**Link to GitHub repository**](#link-to-github-repo-is-here)
1.  [**UX Design - the Five Plans method**](#uxd)
    * [**1.Strategy plan**](#stratetgy)
        * [Planning Stage](#planning-stage)
        * [User Stories](#user-stories)
        * [Site Objectives](#site-objectives)
        * [Design Goals](#design-goals)
    * [**2.Scope plan**](#scope)
    * [**3.Structure plan**](#structure)
    * [**5.Skeleton plan**](#skeleton)
        *  [**Wireframes (wireframes.md)**](readme-files/docs/wireframes.md)
    * [**6. Surface plan**](#surface)
        * [**UI (User Interface)**](#ui-user-interface)
            *  [**Site structure**](#site-structure)
            *  [**Responsiveness**](#responsiveness)
            *  [**Layout**](#layout)
                * [Header](#header)
                * [Main content](#main-content-section)
                    * [Home page](#home-page)
                    * [Menu page](#menu-page)
                    * [Gallery page](#gallery-page)
                    * [Contact page](#contact-page)
                * [Footer area](#footer)
            *  [**Typography**](#fonts)
            *  [**Colour theme**](#colours)
            *  [**Contrast ratio (contrast.md)**](readme-files/docs/contrast.md)
            *  [**Accessibility**](#accessibility)
1.  [**Testing (testing.md)**](readme-files/docs/testing.md)
1.  [**Performance**](#performance)
1.  [**Issues**](#issues)
1.  [**Deployment (deployment.md)**](readme-files/docs/deployment.md)
1.  [**CREDITS:**](#credits)
    *  [**Code Snipets:**](#code-snipets)
    *  [**Research and Information:**](#research-and-information)
    *  [**Media**](#media)
    *  [**Other Resources:**](#other-resources-and-tools-used)
1. [**Aknowledgment**](#aknowledgment)

  ---
# **About the site** 
***Culture Coffee cafe*** is a static website which is intended to promote, atract and offer information to potential and actual customers of Culture Coffee café. 
Since this website was build as a Milesstone Project for my course, therefore educational purposes only, please be advised that some information on the website may not accurate and are displayed for the fore-mentioned scope.
### Link to live website is [here](https://phloreenm.github.io/MP1-CultureCoffee-CI-CoBC-FM/)
### Link to this GitHub repo is [here](https://github.com/phloreenm/MP1-CultureCoffee-CI-CoBC-FM/tree/main)  

Some sections of this documentation have been moved to a different file, specific to that content.
The reason is all that information in this docuement only woud've made navigation difficult. So for example, `wireframes.md`, `contrast.md` or `testing.md`, are different files and they are linked in this document.
Inside those separate files there are links back to the main readme.md file too.

<br>
<p align="right">
    <a href="#table-of-contents">Return to Table of Contents</a>
</p>
<br>

---
# **UX (User Experience)**
## **UXD**
The UX design and develoepment is based on the 5 Plans we've learned on Code Institute's platform.
# **Strategy**
- incorporates:
    - **Planning Stage**
        - The idea of making this website came from a real-world need, which is to build a presentation website for Culture Coffee café located in Salisbury. From the begining I had a rough idea of the content the site will provide, but folowing the development methods learned at Code Institute, helped me organise the workflow.
        <!-- - **Users Needs** -->
    - **User Stories**
        -  A first-time client, or a **prospective client**, may have the following user stories:

            | As a                  | I want to...          | So that I can...       | 
            |-----------------------|-----------------------|------------------------|
            | **Prospective Client**|                       |                        |
            |                       | find a café in Salisbury | drink a coffee locally | 
            |                       | find café's location | visit the café | 
            |                       | find contact details | ask some other questions | 
            |                       | read the menu | see if I can have a brunch, lunch or just a coffee | 
            |                       | download the menu | print the menu | 
            |                       | find opening hours | visit the café | 
            |                       | read some testimonials (reviews) | see other clients' experience | 
            |                       | read the social media pages | see what other clients shared | 
            |                       | see if they have accessible entryway | bring my son who's using a wheelchair | 
            |                       | check if there is free Wifi | do some work from my laptop | 
            |                       | hire the café | have a private party | 


        - Additionally to the user stories of a first-time client, an **existing client** might also have the following stories:

            | As an                 | I want to...          | So that I can...      | 
            |-----------------------|-----------------------|-----------------------|
            | **Existing Client**   |                       |                       |         
            |                       | remember café's location | visit it again | 
            |                       | find if they offer bonuses for being a loyal customer. | have a coffee for free | 
            |                       | make a review | show how happy I am for their coffee | 
            |                       | make a complain | discuss a refund | 
            |                       | remember café's location | visit it again | 


        - As a **bussiness owner** the users stories are related to the purpose of the bussiness itself, but also to the intent to grow in future:

            | As a              | I want to...          | So that I can...  |
            |-------------------|-----------------------|-------------------|
            | **Business Owner**|                       |                   |       
            |                   | sell my products | make profit |            
            |                   | create a select clientele | make a target  |            
            |                   | reward the loyal clients | retain customers   |            
            |                   | offer a good, intuitive browsing experience | raise the chances the client would remain on the site |            
            |                   | implement a good site structured layout  | provide concise  informations |            
            |                   | provide pictures gallery | showcase some of the products on sale |            
            |                   | provide links to social media | make a presence in the online |            
            |                   | create a positive image | attract more customers |         
    - **Site Objectives**
        - The main purpose of this website is to offer the users the information necessary so that a client could learn:
            - who we are?
            - what could we offer as a café shop?
            - which is the café's menu?
            - where are we located?
            - how the venue looks like on the inside?
            - if there are other clients reviews about this shop.
            - if he could contact us?
    - **Design Goals**
        - The site should be responsive on all devices.
        - Offer accesibility support.
        - The navigation shoud be intuitive and easy.
        - Each page should keep a pleasant, neat and common design across the website.
        - The information offered is enough and organized well to attract the clients.

---
# **Scope**
- guided by the [Product Strategy](#strategy)
    - WHAT *features* and *functions* are within **scope**.
        - Features Required:
            - Inform user about 
            - 
            - 
    - WHAT *content elements* may be rewired to meet users need.
        - Content Required:
            - Pictures
            - Location
            - 

---
# **Structure**
- defines HOW the various *features* and *functions* FIT together.
- defines the *categories of trips or rides* possible.
- transition from abstract to concrete elements:
    - HOW users get to specific information.
    - WHERE they can go next.
- Design Options:  
    - HOW:
        - an user can learn some information about out cafe by reading the Landing Page content
        - an user could consult the cafe's menu in two ways:
            - viewing the dedicated Cafe's Menu page.
            - downloading the available Cafe's Menu in PDF format.
        - an user may see a pictures gallery:
            - by visiting the Pictures Gallery page
            - by accessing the Google Maps and TroipAdvisor links at the bootom of the Pictures Gallery's content section.
        - an user 
    - WHERE:
        - **Structure and flow (user journey) map**

        The flow of an user visiting the website is represented in the following diagram:
            ![](/readme-files/readme-images/website-flow.jpg)

        <!-- - Information Section -> Landing page
        - Menu section -> Cafe's Menu page
        - Pictures section -> Gallery page
        - Contact section:
            - Contact Us form -> Contact Us form page
            - Contact information:
                - Address - navigation to
                - Email address and contact phone number
                - Social Media -->

---
# **Skeleton**

The wireframe sketches are located in [wireframes.md](readme-files/docs/wireframes.md) file.

<br>
<p align="right">
    <a href="#table-of-contents">Return to Table of Contents</a>
</p>
<br>

---
# **Surface**
<!-- - is the *skin* layer of the product -> the final *look-and-feel*.
- dive into the *visual treatment* of the product: -->

# **UI (User Interface)**

## **Site structure**
- The site's structure follows a simple linear design. From the home page you may access any other page through the navigation menu. This is a straight forward aproach. The same navigation menu is accesible on every other page, even on the [404.html](404.html) one. The [Form Confirmation page](formconfirmation.html) is displayed to confirms the form has been successfuly submited and you have the option to navigate back to the website or other internal links.
- One reason behing this aproach (of the simple linear design) is the [Mental Model](https://en.wikipedia.org/wiki/Mental_model) natural thought process, more exactly, the users build mental models and use these 
>"to assess relations among topics and to guess where to find things they haven’t seen before".[ (Site Structure theory)](https://webstyleguide.com/wsg3/3-information-architecture/3-site-structure.html)

<p align="center">The following diagram represents this structure<br>
    <img src="readme-files/readme-images/site-structure-diagram-upd.jpg" alt="Site's structure" width="90%">
</p>

<br>
<p align="right">
    <a href="#table-of-contents">Return to Table of Contents</a>
</p>
<br>

---
## **Responsiveness**
- Some commonly used breakpoints are 576px, 768px, and 992px. These values should cover most of the targetted devices, like smart phones, tablets/laptops, and desktops. The layout I chose allowed me to use the 920px breakpoint for the navigation menu (when the header's width is too small and the navigation items would begin to wrap) and 992px for the general layout. 

- For responsiveness on mobile devices the minimum supported width is 300px. Using smaller resolution would make the pictures unreasonbly sized and the layout would not serve the purpose properly. That's why I decided this would be the minimum body's width.
- Going higher in the width resolution from 991px we see a landscape and desktop view, with larger paddings and margins, with a maximum width of the main content of `1000px`. On iPad Pro the layout is displayed as on desktop view, but on a Samsung Tab S4, the layout is rendered as a mobile view.

- The navigation bar has a little different responsivness than the rest of the layout because of the size of the text from navigation bar, and also because I din not want navigation's items to wrap in desktop view mode. When the width of the screen decreases and would force the navigation elements to wrap, that's the moment the header is displayed as mobile layout.
Therefore the transformation of the navgation bar from desktop view to mobile view happens much earlier, going down from 920px.

- The overall responsiveness of the site has been tested and the results can be found in the folowing section.

<br>
<p align="right">
    <a href="#table-of-contents">Return to Table of Contents</a>
</p>
<br>

---
## **Layout**
The general layout of the website is composed of three main areas: [Header](#header), [Content](#main-content-section) and [Footer](#footer). 
The Header (containing the Logo and the Navigation Menu) and the Footer are common to all pages, but the Content area is different for each page.

---
### **HEADER** 
- contains the company's logo and, depending on the device's screen width, a menu navigation bar to the top right (on larger screens) or a hamburger menu button (which opens the hidden menu - in mobile view).

<p align="center">On screens up to 920px width (small screens)<br>
    <img src="readme-files/readme-images/nav-bar-mobile-tablet-view.jpg" alt="On screens up to 920px width (small screens)" width="90%">
</p>
<p align="center">On screens larger than 920px width (larger screens)<br>
    <img src="readme-files/readme-images/nav-bar-desktop-view.jpg" alt="On screens larger than 920px width" width="90%">
</p>

---
### **MAIN CONTENT SECTION**
- contains the page's specific subjects (like some information on Langding Page, Cafe's Menu, Pictures Callery, Contact form or the 404 page).
- this area is limited to a `max-width: 1000px;` there is also a `padding: 0 100px;` in desktop view. Also the background-color is limited to this width and this should create a delimitation between the empty space and the actual main content.
- in mobile view the pading is reduced to `30px` and the `width:100%`, so that more information would fit on smaller screens.

<br>
<p align="right">
    <a href="#table-of-contents">Return to Table of Contents</a>
</p>
<br>

---
#### **Home page**
Home page main section contains:
- a welcoming message at the top.
- some introductory information structured as Q&A form. This area contains some links to links on another pages. For example, the word "coffees", from the `What else can we offer you ?` question, is a link to the Coffees category from Cafe's Menu page.
This is making navigation handy. 
The purpose is to guide the visitor through the website's content, and describe what the company has to offer.

<p align="center"><strong>Mobile and desktop view</strong>:</p>
<p align="center">
    <img src="readme-files/readme-images/01-2-homepage-mobileview-screenshot-h900.jpg" alt="Left - Mobile view" height="370">
    <img src="readme-files/readme-images/01-1-homepage-desktopview-screenshot-h600.jpg" alt="Bottom - Mobile view" height="370" width="650">
</p>

<br>
<p align="right">
    <a href="#table-of-contents">Return to Table of Contents</a>
</p>
<br>

---
#### **Menu page**
The menu page is structured differently that the other pages, because the main purpose is to display the Café's menu, sorted in four categories: Coffees, Dishes, Cakes and Wines. For that reason I found useful to use the grid system. The same result could be obtained with just using flexbox too, but my choice was grid for this page.
- In mobile view the layout is formed as a single column. So the categories and their content are all displayed in one columns only.
- On larger screens (desktop view) the container is displayed in a column: inside it, the categories in this column and the the content are displayed on two columns.
- Bellow each category group, there is a link `Back to top`(... of the page), to help the user to jump to the main navigation bar area.
- I chose to create another menu specific to this page only.
    - This menu only contains internal links found on the same page, to the main categories from the list, which are: Coffees, Dishes, Cakes and Wines. 
    - Using this menu the navigation is quicker for the user, if he's interested in a specific product and is not interested to see other items. 
    - It is available at the bottom of the page too.
    - Since using JS is not required for this project, I needed to find a way to change the text of a specific area, when the state changes. I found out that the `<details>` element can help.
    So when this menu is collapsed, the user is asked to acces this menu by clicking the `▶️  Click to open quick menu links`:
    <p align="center">Menu closed<br>
            <img src="readme-files/readme-images/02-6-cafemenu-internal-links-menu-closed-screenshot%20.png" alt="Menu closed" width="90%">
    </p>
    - The user may choose to colapse the menu by clicking again `🔽 Click to close quick menu links` area.
    <p align="center">Menu opened<br>
            <img src="readme-files/readme-images/02-7-cafemenu-internal-links-menu-opened-screenshot%20.png" alt="Menu opened - After the user clicks, the menu opens like this" width="90%">
    </p>
    - You may notice that the text content changes from "open" to "close". The ▶️ and 🔽 icons display the status of the `details` element.
    - In mobile and desktop view, this area keeps the same layout, by adapting its width to the viewport.
    <p align="center">
        <img src="readme-files/readme-images/02-8-cafemenu-internal-links-menu-opened-mobileview-screenshot%20.png" alt="Quick Links Menu - Mobile view" width="400">
    </p>
- Bellow, there is a linked text which, on click, it downloads the complete Café's menu in PDf format.
        <p align="center">
            <img src="readme-files/readme-images/cafesmenu-dl-pdf-link-structure.jpg" alt="Download link" width="400">
        </p>
    
- The main content of this page is composed of four categories, each with a couple of cafe's menu items, grouped acordingly.
    - Each category is delimited and begins with the header.
    - Under the Header there are the items displayed in a column or two columns, depending on screen size.         
    - At the end of each category there is a "Back to top" link.
    - Just before the Footer area, there is the same Quick Menu links displayed again, to ease users's navigation.
    <p align="center">Small screen and larger screen layout preview:<br>
          <img src="readme-files/readme-images/cafesmenu-mb-structure.jpg" alt="mobile view" height=370">      
         <img src="readme-files/readme-images/cafesmenu-des-structure.jpg" alt="desktop view" height="370">
    </p>

<br>
<p align="right">
    <a href="#table-of-contents">Return to Table of Contents</a>
</p>
<br>

---
#### **Gallery page**
The Gallery page has only one purpose: to showoff some pictures depincting the interior design of the cafe, staff, making coffees, etc.
- In **mobile view** there are two views: 
    - **One column**
            <p align="center">Mobile view: width smaller than 672px<br>
                <img src="readme-files/readme-images/03-8-gallery-mobileview-1col-sm-img-screenshot-.jpg" alt="Mobile One column Preview" height="370">
            </p>
    - **Two columns**
            <p align="center">Mobile view: width between 673 and 992px<br>
                <img src="readme-files/readme-images/03-7-gallery-mobileview-2col-sm-img-screenshot-.jpg" alt="Mobile 2 columns Preview" height="370">
            </p>
- **Desktop or large screen** view: images are displayed on a single column, at high resolution:
            <p align="center">Desktop view: width more than 992px <br>
                <img src="readme-files/readme-images/03-5-gallery-desktopview-1col-lg-img-screenshot-.jpg" alt="Larger screens and Desktop pone column Preview" height="370">
            </p>

<br>
<p align="right">
    <a href="#table-of-contents">Return to Table of Contents</a>
</p>
<br>

---
#### **Contact page**
- The Contact page is structured around a form, containing multiple fields, which the user may choose to fill. The user can make a request, ask a question, propose a recommandation, make a complain and also take part to a poll by votting his favorite coffee.
    <p align="center">Mobile and Desktop preview<br>
        <img src="readme-files/readme-images/04-2-contact-mobileview-screenshot.png" alt="Contact page - Mobile preview" height="370">
        <img src="readme-files/readme-images/04-1-contact-desktopview-screenshot.png" alt="Contact page - Desktop preview" height="370">
    </p>

<br>
<p align="right">
    <a href="#table-of-contents">Return to Table of Contents</a>
</p>
<br>

---
### **FOOTER**
<p align="center">Mobile and Desktop view</p>
<p align="center">
    <img src="readme-files/readme-images/footer-mobileview-screenshot.jpg" alt="Footer in mobile view" width="25%">
    <img src="readme-files/readme-images/footer-desktopview-screenshot-.jpg" alt="Footer in desktop view" width="60%">
</p>

- The footer is composed three sub-areas, as follows:
    - **ADDRESS** - contains a link with the Google Maps location of the Cafe shop. Accessing the link will offer you the posibility to ask for directions towards the shop. Depending on the device used, the behaviour differs: on mobile deviced it will open the Google Maps app and on desktop device it will open a new tab with Google Maps.
    - **SOCIAL MEDIA LINK** - linked icons to acces the social media pages of the café shop. On hover over these icons, they grow in size to `2rem`.
    - **CONTACT US**
        - The EMAIL contains the `mailto:` link, so if the user want's, by pressing on the e-mail address, the default email client is opened. The `Send to` and `CC` section are prefilled with the right email destinators addresses.
            <p align="center">Testing on a smartphone:<br>
                <img src="readme-files/readme-images/mailto-client.jpg" alt="Client's default app opens already having destinators emails completed" height="370">
            </p>
        - The TEL section is also a link, which, while in mobile view, is enabled and proceeds to opening the phone number in calling screen, but if viewed on a desktop, the link is disabled. As described [here](https://www.campaignmonitor.com/blog/email-marketing/using-phone-numbers-in-html-email/):  
        > *tel: support is great across mobile clients, it can be unreliable on the desktop and in webmail clients.*

        <p align="center">Preview:</p>
        <p align="center">
            <img src="readme-files/readme-images/tel-open-app.jpg" alt="Press phone number opens default calling application" height="370">
            <img src="readme-files/readme-images/tel-call-screen.jpg" alt="Calling screen on a smartphone" height="370">
        </p>

<br>
<p align="right">
    <a href="#table-of-contents">Return to Table of Contents</a>
</p>
<br>

---

## **Fonts**
- Font families used:
    - `font-family: 'Lato', sans-serif;`
    - `font-family: 'Montserrat', sans-serif;`
    - `font-family: 'Merriweather', serif;`
- The fonts were chose to offer a good visual impact, but mostly to promote readability. The text being easy readable, it is more likely that users reading the content they obtain the needed information quicly and understand the message.
<br>
<p align="right">
    <a href="#table-of-contents">Return to Table of Contents</a>
</p>
<br>

---
## **Colours**
Choosing the site's color theme was a bit tricky for me.

I have a *Moderate Deutan colour blindness*. This doesn't affect me in a manner where I could not see colours, as many people might believe when they hear "colour blindness". But it more related to colour sensivity. Is just that in some specific cases (low or crepuscular light, for example) I might not perceive colours as others. For this reason I needed help from someone else, so in some moments in the development of this project I had to ask for a second opinion.

Finally, the color theme I decided to use in this project is actually is based on the colors of a coffee bean and two other complemetary colors, to create a good contrast. So I primarly used an image of coffee beans. From that, using the tools available at [coolors.co](https://coolors.co/) I extracted the main pallete colors.
The extracted color nuances were too many, so I had to finnaly decide to which basic color I'll use. 
After, to create an acceptable contrast, I've used the generator so that I'll will give me colors to fit one each other.

As a result, the final contrast ratio is everywhere above 9:1. All contrast test were conducted on [Color Contrast Accessibility Validator](https://color.a11y.com/Contrast/) and [WebAIM - Contrast Checker](https://webaim.org/resources/contrastchecker/). The result can be consulted in the [dedicated file](assets/docs/contrast.md).

<p align="center">
    <img src="readme-files/readme-images/colormind---the-ai-powered-color-palette-generator.jpg" alt="Default color pallete - colormind.io" width="80%">
</p>

- `#231a19` - used mainly for text color.
- `#552f1e` - used for:
    - Main navigation menu links background when hovered.
    - Landing page internal links hover effect
- `#883f22` - used for active page in main navigation links
- `#f5f7bb` - used for hover text color change in links in main navigation bar and footer.
- `#ece7e1` - used for:
    - Header background.
    - Main content background color in main page.

- The arrows used in the Quick Menu categories list in Cafe's Menu page, are blue.

<br>
<p align="right">
    <a href="#table-of-contents">Return to Table of Contents</a>
</p>
<br>

---

# **Accessibility**
- The Accessibility score of 100 in Lightroom was obtained by using the recommended [landmarks](https://www.w3.org/TR/2017/NOTE-wai-aria-practices-1.1-20171214/examples/landmarks/HTML5.html) or *special regions, so that screen readers and other assistive technologies can jump to different sections of the site. These improve the overal navigation experience.
- Each page has distinctly separated areas. The main content area of each page contains the right landmarks and ARIA landmarks, such as `role`, `aria-label`.
- In mobile view the main navigation bar is hidden behind an icon. The icon has normally applied a bouncing effect, but to avoid *vestibular motion triggers* the animation is reduced (in media queries section of the css file), when the user has disabled such effects.

[Back to Table of Contents](#table-of-contents)

---
# **Deployment**
This section is described in its own file [deployment.md](/readme-files/docs/deployment.md)

<br>
<p align="right">
    <a href="#table-of-contents">Return to Table of Contents</a>
</p>
<br>

---
# **Performance**
1. To improve loading speeds, I've used *.webp image format  (https://developers.google.com/speed/webp) and *.png and *.jpg formats. Every image is been proccesed with Adobe Photoshop -> Export -> Save to Web -> and used low or medium presets for image quality.
2. Images from Gallery page were resized to 768px for the long side. This resolution is enough to display good images for `breakpoint-md: 768px` .
3. Images used on Cafe's Menu page were resized to small format and low quality, so it won't affect performance.
4. The performance of the site was tested using the Lighthouse tool. The results were negatively influenced by two aspects (`links not crawable` and `pre-connect`), for which I did not find a solution to fit my needs. This aspect is described more detailed in [testing.md page](readme-files/docs/testing.md/#lighthouse-scores) file.

<br>
<p align="right">
    <a href="#table-of-contents">Return to Table of Contents</a>
</p>
<br>

---
# **Issues**
Along the development I encountered different issues. Some of them were fixed, for other I found a way around of just used a better solution.
- When resizing the browser window to mobile view, at the left of the browser can be seen the hidden navigation bar transition effect.
- [Contact Page legend text centering](): an issue I had was centering the legend element, which wasn't easy achievable through CSS, because of the cross browsers incompatibility. There, an in-line property solved it (https://www.geeksforgeeks.org/html-legend-align-attribute/). Issues discussed [HERE](https://stackoverflow.com/questions/4006824/how-to-center-the-legend-element-what-to-use-instead-of-aligncenter-attribu)
- I could not find a FontAwesome icon for Tripadvisor. Issue is discussed [HERE](https://github.com/FortAwesome/Font-Awesome/issues/18180)
- While site was deployed on github Pages, the images on the site wouldn't load. Found out that I have to remove the '/' from the relative links. Example:
`<src="/assets/imgs/coffees/image.jpeg>` -> in this format the images wouldn't load, so I had to remove the backslash before the 'assets' folder. Found this through the Developer's Tools in Chrome. In VS Code having the `/` won't affect loading, but on GitHub alt-text is being shown.
- I couldn't use Extended Syntax for Markdown documents, as while I was trying to use Footnotes, for example, it wasn't rendered in my GitHub repository. Therefore I had to use links inside the content to credit the extracted ideas from the respective sources.
- Wasn't able to use emoji in this document, because on preview they weren't rendered ar icons, but plain text.
- Hover effects won't work properly on touch mobile devices (which are using a touch screen), so a media query for that has to be implemented.
- The navigation menu, while in mobile view, is displayed OVER the content of the page. So opening the menu in mobile view, the actual content below the header won't go lower to make place for the menu items. I didn't want to use JS and/or Boostrap, so this was an acceptable compromise I had to accept for the purpose of this project.
- While [validating](https://validator.w3.org) I had an error 
    > End tag nav seen, but there were open elements.

    > Unclosed element ul.

    but couldn't find any opened or unclosed elements. These errors dissapeared after I corrected some other errors.

<br>
<p align="right">
    <a href="#table-of-contents">Return to Table of Contents</a>
</p>
<br>

---
# **CREDITS**

## **Code Snipets**
- [Header layout and effects](https://www.codinglabweb.com/2020/12/responsive-navigation-card-bar-design.html)
- [Content flexbox cards](https://www.youtube.com/watch?v=cJjej5udWVE)
- [Customize the details element containing the internal links to menu categories](https://stackoverflow.com/questions/10813581/can-i-replace-the-expand-icon-of-the-details-element)
- [HR element styling](https://www.formget.com/css-hr/)
- [Cafe Menu Quick Menu links with details & summary elements](https://stackoverflow.com/questions/10813581/can-i-replace-the-expand-icon-of-the-details-element)

## **Research and Information** 
- Coffee Types [List](https://www.baristainstitute.com/blog/emmi-kinnunen/january-2022/affogato-ristretto-list-most-common-coffee-drinks)
- Things All Restaurant Website Designs Need to [Include](https://pos.toasttab.com/blog/on-the-line/7-things-restaurant-websites-need-to-include): as highlithed in this article, having some specific sections on your restaurand (cafe in our case), improves a lot the customer experience and the chances of attracting new customers raises.
- Initiating [Voice Calls from HTML Email Newsletters](https://www.campaignmonitor.com/blog/email-marketing/using-phone-numbers-in-html-email/) 
- Tone down the animation to avoid [vestibular motion triggers like scaling or panning large objects.](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-reduced-motion)
- [Using ARIA Landmarks](https://accessibility.oit.ncsu.edu/using-aria-landmarks-a-demonstration/)
- [Site structuring](https://webstyleguide.com/wsg3/3-information-architecture/3-site-structure.html)
- [Mental model](https://en.wikipedia.org/wiki/Mental_model)
- [Font accessibility](https://bighack.org/font-accessibility-and-readability-the-basics/)
- [UX Design using the Five Planes Method](https://medium.com/designcentered/ux-design-5-planes-method-b1b1d6587c05)

## **Media**
- Logo was created using [Logo Maker Pro on Android](https://play.google.com/store/apps/details?id=com.TTT.logomaker.logocreator.generator.designer)
- Images used for Cafe Menu product list are all credited in the code, but also in this list:
     - Coffees:
        - [Affogato](https://www.pexels.com/ro-ro/@rachel-claire/)
        - [Espresso](https://www.pexels.com/ro-ro/@victorfreitas/)
        - [Caffè Latte](https://www.pexels.com/ro-ro/@chevanon/)
        - [Caffè Mocha (Mocaccino)](https://www.pexels.com/ro-ro/@content-pixie-1405717/)
        - [Café au Lait](https://www.nespresso.com/ncp/res/uploads/recipes/nespresso-recipes-Cafe-Au-Lait-OL.jpg)
        - [Cappuccino](https://www.pexels.com/ro-ro/@jayoke/)
        - [Cold Brew Coffee](https://www.pexels.com/ro-ro/@marta-dzedyshko-1042863/)
        - [Espresso con Panna](https://i2.wp.com/www.teacoffeecup.com/wp-content/uploads/2020/08/classic-espresso-con-panna.jpg)
        - [Espresso Macchiato](https://www.nespresso.com/ncp/res/uploads/recipes/nespresso-recipes-Five-o-clock-break.png)
        - [Greek Frappé](https://www.pexels.com/ro-ro/@freestocks/)
        - [Freakshake](https://www.pexels.com/ro-ro/@alleksana/)
    - Dishes
        - [Sautéed tiger prawns](https://www.youtube.com/watch?v=FJbhplyVBUE)
        - [Vine tomato salad](https://pixabay.com/photos/vegetables-vegetable-pan-grilling-1620561/)
        - [Scottish mussels](https://www.scottishshellfish.co.uk/scottishmusselscookedinwhitebeer/)
        - [Delicious quiches](https://www.pexels.com/ro-ro/@shkrabaanthony/)
    - Cakes
        - [Caramel apple pie](https://www.pexels.com/ro-ro/@polina-tankilevitch/)
        - [Vegan cheesecake](https://www.pexels.com/ro-ro/@alesiakozik/)
        - [Strawberry gâteau](https://www.pexels.com/ro-ro/@suzyhazelwood/)
        - [Belgian Waffles](https://www.pexels.com/ro-ro/@monica-turlui-36421873/)
    - Wines:
        - [Red Dry Agiorgitiko 2017](https://www.cellartracker.com/wine.asp?iWine=3660056)
        - [Monograph Rose Agiorgitiko 2016](https://gaiawines.gr/en/monograph-rose-en/)
        - [La Gioiosa Prosecco 2012](https://www.vivino.com/HK/en/la-gioiosa-valdobbiadene-prosecco-superiore/w/1148479)
        - [Prunus Dão Tinto 2017](https://www.wine-searcher.com/find/gota+prvt+select+prunus+blanco+dao+portugal/2017/uk)
- Images used in Gallery page are my own, made with my dSLR, and processed with Photoshop.

## **Other resources and tools used**
- Code Validation:
    - [W2C Markup Validation Service](https://validator.w3.org/nu/)
    - [W2C CSS Validation Service](https://jigsaw.w3.org/css-validator/)
- Accessibility Validation:
    - [Color Contrast Accessibility Validator](https://color.a11y.com/Contrast/)
    - [WebAIM - Contrast Checker](https://webaim.org/resources/contrastchecker/)
- Tools used:
    - [Balsamiq - wireframes design](https://balsamiq.com/)
    - [Multi Device Website Mockup Generator](https://techsini.com/multi-mockup/)
    - [Adobe Photoshop v.23](https://www.adobe.com/uk/products/photoshop/)
    - [FontAwesome](https://fontawesome.com/)
    - [Google Fonts](https://fonts.google.com/)
    - [Document format - Beautify](https://codebeautify.org/htmlviewer)
    - [Colormind.io to extract website color theme](http://colormind.io/)
    - [Website Flow diagram](https://lucid.app/)
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)

<br>
<p align="right">
    <a href="#table-of-contents">Return to Table of Contents</a>
</p>
<br>

---
# **Aknowledgment**
I would not be enough to finish this project without saying a big "thank you!" to all of you who helped me in working on this project.
Firstly, to my family who supported me all along in every aspect, especialy in being absent at some important moments, because I had to study.
Of course, nothing would have been possible without everyting Code Institue has to offer through this course and its wonderful Slack community. 
Since I am officialy taking this course at City of Bristol College, a big thanks to my tutors, [Pasquale F.](https://www.linkedin.com/in/pasquale-fasulo-68612218a/) and Ben S. for every step they've been with me through the learning process.
And last but not least, to my mentor, [Adegbenga Adeye](https://github.com/deye9), whose insights were always very helpful and helped me shape this project.

<br>
<p align="right">
    <a href="#table-of-contents">Return to Table of Contents</a>
</p>
<br>