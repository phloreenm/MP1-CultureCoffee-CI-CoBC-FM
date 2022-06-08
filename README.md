![](static/assets/imgs/responsibedesign-01.webp)

![GitHub contributors](https://img.shields.io/github/contributors/phloreenm/MP1-CultureCoffee-CI-CoBC-FM)
![GitHub last commit](https://img.shields.io/github/last-commit/phloreenm/MP1-CultureCoffee-CI-CoBC-FM)
![GitHub language count](https://img.shields.io/github/languages/count/phloreenm/MP1-CultureCoffee-CI-CoBC-FM)
![GitHub top language](https://img.shields.io/github/languages/top/phloreenm/MP1-CultureCoffee-CI-CoBC-FM)

# **<span style="color:orange">Culture Coffee café - Milestone Project 1</span>**


![very good|200x100,10%](/assets/imgs/gallery-imgs/02.MGF_2468.webp "Hover over image picture description")

![very good|200x100,100%](/assets/imgs/gallery-imgs/02.MGF_2468.webp)
![very good|200x100](/assets/imgs/gallery-imgs/02.MGF_2468.webp)

<!-- ![very good|512x397,100%](/assets/imgs/image.webp) -->

# **Table of Contents**
1. [**About the site**](#about-the-site)
    * [**Link to live website**](#link-to-live-website-is-here)
    * [**Link to GitHub repository**](#link-to-github-repo-is-here)
1. [**Table of Contents**](#table-of-contents)
1. [**UX (User Experience)**](#ux-user-experience)
    * [**User Stories**](#user-stories)
    * [**The Strategy and the Scope Plane**](#the-strategy-and-the-scope-plane**)
    * [**The Structure Plane**](#the-structure-plane)
        *  [**Accessibility**](#accessibility)
1. [**UI (User Interface)**](#ui-user-interface)
    *  [**Wireframes**](assets/docs/wireframes.md)
    *  [**Layout**](#layout)
        * [Navigation bar](#navigation-bar)
        * [Main content](#main-content):
            * [Home page](index.htmlhtml)
            * [Menu page](cafesmenu.htmlhtml)
            * [Gallery page](gallery.htmlhtml)
            * [Contact Us page](/contact.htmlhtml)
        * [Footer area](#footer)
    *  [***Text***](#-text-)
    *  [***Colour theme***](#colours)
    *  [**Accessibility**](#-accessibility-)
    *  [**Responsiveness**](#-responsiveness-)
1. [**Performance**](#performance)
1. [**Testing**](assets/docs/testing.md)
1. [**Issues**](#issues)
1. [**Deployment**](assets/docs/deployment.md)
1. [**CREDITS:**](#credits)
    *  [**Code Snipets:**](#code-snipets)
    *  [**Research and Information:**](#research-and-information)
<!-- 1.  [**Improve Customer services**](#improve-customer-services) -->

  
  <!-- ============================== -->
  
  ---
## **About the site** 

***Culture Coffee cafe*** is a static website which is intended to promote, atract and offer information to potential and actual customers of Culture Coffee café. 
Since this website was build as a Milesstone Project for my course, therefore educational purposes only, please be advised that some information on the website may not accurate and are displayed for the fore-mentioned scope.

### Link to live website is [here](https://phloreenm.github.io/MP1-CultureCoffee-CI-CoBC-FM/)

### Link to GitHub repo is [here](https://github.com/phloreenm/MP1-CultureCoffee-CI-CoBC-FM/tree/main)

            
[Back to Table of Contents](#table-of-contents)

---
## **UX (User Experience)**

### **User Stories**
I decided to display the User Story in a table (also a link at the bottom of the table). Since some user stories (like First time user and Existing User) might actually follow the same 

| As a/an             | I want to...      | So that I can... | Scenario 1 | Scenario 2 | Acceptance Criteria |
|---------------------|-------------------|------------------|------------|------------|---------------------|
| **First time user** | **Existing User** | **Bussiness**    |            |            |                     |
| &#10003;            | &#10003;          |                  | find café's location                                 | drink a coffee in the café                            | Decided to visit the shop                                                         |                                                                                                   |                                                                                                                                                    |
| &#10003;            | &#10003;          |                  | find opening hours                                   | make avisit to the café                               |                                                                                   |                                                                                                   |                                                                                                                                                    |
| &#10003;            |                   |                  | see café's inside pictures                           | decide if I like the location                         | user is well impressed by the very positive reviews and decides to visit the café | User read some negative reviews and developed uncertainity if quality offered is high as promised |                                                                                                                                                    |
| &#10003;            | &#10003;          |                  | find if pets are allowed                             | bring my pet at the cafe                              |                                                                                   |                                                                                                   | (Only) Disabled people that use assistance dogs have important rights under the Equality Act 2010 - hygiene maters, so other cases can be accepted |
| &#10003;            |                   |                  | read some testimonials (reviews)                     | see other clients' experience                         |                                                                                   |                                                                                                   |                                                                                                                                                    |
| &#10003;            | &#10003;          |                  | find if the café offers takeaway                     | buy a coffee on my way to the train                   |                                                                                   |                                                                                                   |                                                                                                                                                    |
| &#10003;            | &#10003;          |                  | stay outside                                         | enjoy the sun while having a coffee                   |                                                                                   |                                                                                                   | weather is good                                                                                                                                    |
| &#10003;            | &#10003;          |                  | see if power outlets and internet acces are provided | use my laptop and have a coffee                       |                                                                                   |                                                                                                   |                                                                                                                                                    |
| &#10003;            | &#10003;          |                  | see if they offer wheelschair acces                  | bring someone confined to a wheelchair                |                                                                                   |                                                                                                   |
|                     |                   | &#10003;         | sell my products                                     | make profit                                           |                                                                                   |                                                                                                   |
|                     |                   | &#10003;         | create a select clientele                            | make a target                                         |                                                                                   |                                                                                                   |
|                     |                   | &#10003;         | reward the loyal clients                             | retain customers                                      | Using loyalty cards - 10th coffee comes from the house                            |                                                                                                   |
|                     |                   | &#10003;         | update Social Media                                  | make a presence in the online                         |                                                                                   |                                                                                                   |
|                     |                   | &#10003;         | offer a good, intuitive browsing experience          | raise the chances the client would remain on the site |                                                                                   |                                                                                                   |
|                     |                   | &#10003;         | implement a good site structured layout              | provide concise  informations                         |                                                                                   |                                                                                                   |
|                     |                   | &#10003;         | provide pictures gallery                             | showcase some of the products on sale                 |                                                                                   |                                                                                                   |
|                     |                   | &#10003;         | provide pictures gallery                             | present the premise's interior design                 |                                                                                   |                                                                                                   |

An online Excel version of the User Stories Board can be found [here](https://1drv.ms/x/s!AhVZRr1-0ZpXmKwYxEhkrC46UlGAow?e=utUtgc)

[Back to Table of Contents](#table-of-contents)

---

## **UI (User Interface)**
### ** Wireframes **
### ** Layout **
    
### ** Text **
- Fonts used:
    - General Headings: Proza Libre — Regular 400 (to stand out)
    - Menu items heading: Lato - 3,4,7,9
    - Paragraphs: 
        Montserrat (good readability - designed for optimal readability on screens)
        font-family: 'Proza Libre', sans-serif;
        font-family: 'Lato', sans-serif;
        font-family: 'Montserrat', sans-serif;
        font-family: 'Merriweather', serif;
            
[Back to Table of Contents](#table-of-contents)

---
### **Accessibility**

- In mobile view the main navigation bar is hidden behind an icon. The icon has normally applied a bouncing effect, but to avoid vestibular motion triggers the animation is reduced (in media queries section of the css file), when the user has disabled such effects.
- 
- Mark up different regions of web pages and applications, so that they can be identified by web browsers and assistive technologies.

[Back to Table of Contents](#table-of-contents)

---

### **Responsiveness**

- Some commonly used breakpoints are 576px, 768px, and 992px. These values should cover most of the targetted devices, like smart phones, tablets/laptops, and desktops. 

For responsiveness on mobile devices the minimum supported width is 300px. Using smaller resolution would make the pictures unreasonbly undistinguisable. That's why I decided this would be the minimum body's width.
Going higher in the width resolution from 768px to 991 we see a mobile view adapted for tablets or some laptop screens, with larger paddings and margins, but keeping the text slightly smaller than in full desktop view.

Going over 992px in width the layout adapts to a full desktop view, with a maximum width of the main content.

The navigation bar has a little different responsivness than the rest of the layout because of the size of the text from navigation bar, and also because I din not want navigation's items to wrap in desktop or tablet view mode.
Therefore the transformation of the navgation bar from desktop view to mobile view happens much earlier, going down from 920px.



===========================================

[Back to Table of Contents](#table-of-contents)

---
## **Issues**
    - Hover effects won't work properly on touch mobile devices (which are using a touch screen), so a media query for that has to be implemented.




[Back to Table of Contents](#table-of-contents)

---
# **Deployment:**
[Deployment PAGE](/assets/docs/deployment.md)

[Back to Table of Contents](#table-of-contents)

---
# **CREDITS:**
 ## **Code Snipets:**
- :arrow_right: Header layout and effects inspired from here: https://www.codinglabweb.com/2020/12/responsive-navigation-card-bar-design.html
- Content flexbox cards code sourced from here: https://www.youtube.com/watch?v=cJjej5udWVE
## **Research and Information:** 
- [Coffee Types List](https://www.baristainstitute.com/blog/emmi-kinnunen/january-2022/affogato-ristretto-list-most-common-coffee-drinks)
- [Things All Restaurant Website Designs Need to Include](https://pos.toasttab.com/blog/on-the-line/7-things-restaurant-websites-need-to-include): as highlithed in this article, having some specific sections on your restaurand (cafe in our case), improves a lot the customer experience and the chances of attracting new customers raises.
- [Initiating Voice Calls from HTML Email Newsletters](https://www.campaignmonitor.com/blog/email-marketing/using-phone-numbers-in-html-email/) 
## **Other resources:**
- [Emoji markup list](https://gist.github.com/rxaviers/7360908)

[Back to Table of Contents](#table-of-contents)

---
# **Improve Customer services**
    IMPROVING CUSTOMERS SERVICES POLL - 
        How often do you use our products?

    Which features are most valuable to you
    How would you compare our products to our competitors’?
    What important features are we missing?
    What are you trying to solve by using our product?
    What other types of people could find our product useful?
    How easy is it to use our product?
    How would you rate the value for money?
    How likely are you to recommend this product to others?
    How could we improve our product to better meet your needs? 

[Back to Table of Contents](#table-of-contents)

---
# **Accessibility**
    - [Acces](): Navigation card items contain a Boostrap class .sr-only which indicates to screen readers at which page we are, helping visualy impaired users navigating throught the website using screen readers.
    - [Landmarks](https://accessibility.blog.gov.uk/2016/05/27/using-navigation-landmarks/)Internet Explorer 11, which does not have accessibility support for the HTML5 elements used to provide landmarks, but which does support the equivalent ARIA roles. 
    https://tink.uk/enhancing-aria-landmarks-with-aria-labelledby/

[Back to Table of Contents](#table-of-contents)

---
# **Performance**
    1. To improve loading speed, I used *.webp image format  (https://developers.google.com/speed/webp)
    2. Images were resized to 768px for the long side. This resolution is enough to display good images for breakpoint-md: 768px. On large screens the gallery is presented as a grid of images, but as the width of the screen is lowered, the grid adapts to 2 or 1 column images.

[Back to Table of Contents](#table-of-contents)

---
# **Issues**
    - [Contact Page legend text centering](): an issue I had was centering the legend element, which wasn't easy achievable through css, because of the cross browsers incompatibility. There an in-line property solved it (https://www.geeksforgeeks.org/html-legend-align-attribute/). Issues discussed [HERE](https://stackoverflow.com/questions/4006824/how-to-center-the-legend-element-what-to-use-instead-of-aligncenter-attribu)
    - I could not find a FontAwesome icon for Tripadvisor. Issue is discussed [HERE](https://github.com/FortAwesome/Font-Awesome/issues/18180)
    - While site was deployed on github Pages, the images on the site wouldn't load. Found out that I have to remove the '/' from the link. Example: <<src="/assets/imgs/coffees/image.jpeg>> -> in this format the images wouldn't load, so I had to remove the backslash before the 'assets' folder. Found this through the Developer's Tools in Chrome.


[^1]: