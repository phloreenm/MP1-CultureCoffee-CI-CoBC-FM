[Back to MAIN README.md](../../README.md)

<p align="center">
    <img width="100%" src="../readme-images/readme-banner.jpg">
</p>

# **TESTING**

## Testing Page Table of Contents
* [**Development Testing**](#during-development-testing)
    * [*Manual Testing*](#manual-testing)
    * [*Bugs and Fixes*](#bugs-and-fixes)
* [**Final Testing**](#final-testing)
  * [**Validators**](#validation-testing)
      * [*HTML*](#http-validation)
      * [*CSS*](#css-validation)
  * [**Lighthouse Scores**](#lighthouse-scores)
      * [*Mobile Version*](#mobile-version)
      * [*Desktop Version:*](#desktop-version)
      
      <!-- * [*Lighthouse Score Feedback From Third Party Testers*](#lighthouse-score-feedback-from-third-party-testers) -->
  * [**Issues**](#issues)

## **During Development Testing**
While developing the website I've tested its functionality locally (Live Server in VS Code or through `python3 -m http.server command`), but also the deployed page on GitHub Pages.

1. I've conducted manual testing for each element for appearance and responsiveness via a simulated live server using an extension in VSCode.
    
1. The webpage was deployed on GitHub Pages and I've asked few friends to check the page as a normal user and then send me a feedback.

1. Created 

### ***Manual Testing:***
* During testing, I've used four different browsers to ensure cross-compatibility. The desktop browsers used by myself were:
#### Mobile Devices Browsers (Smartphone and Tablet):
- Chrome
- Firefox  
- Opera
- Edge
- Safari
#### Desktop bBrowsers:
- Chrome
- Firefox  
- Opera
- Edge
- Safari
#### Testing on individidual devices:
- Smartphones
  - Samsung Galaxy S7 (5.1 inches / 1440 x 2560)
  - iPhone 13 mini (5.4 inches / 1080 x 2340)
  - Samsung Galaxy S21 Ultra (6.8 inches / 1440 x 3200)
- Tablet:
  - Samsung Galaxy Tab S4 LTE (10.5 inches / 1600 x 2560)
- Laptops:
  - Dell 5290 (Screen Size 12.50 inches / 1366 x 768)
  - Dell 7390 2 in 1 (Screen Size	13.3 inches /	1920 x 1080)
  - Apple MacBook Air M1 (13.3 inches / 2560 x 1600)
- Desktop monitors:
  - Lenovo ThinkVision T27p-10 27" UHD (27.0 inches / 3840 x 2160)
  - ASUS ProArt Display PA247CV 23.8 (23.8 inches / 1920 x 1080)
  - MSI Optix MAG162V (15.6 inches / 1920 x 1080)


* I then used the devtools to simulate different screen sizes/devices from 320 px up to 4000px in width. 
* In addition to this, I also asked several people to test using iPhones and Apple Mac laptops/desktops using safari. These users reported no issues or bugs only style suggestions.
## **Final Testing**
### **Validation Testing**
- For HTML validator I've used the [Nu Html Checker](https://validator.w3.org/nu/). I've tested the pages one by one by using the link of the deployed website and by text input. The later was faster, because the deployed page on GitHub Pages is taking longer to refresh.
-  For CSS validation I've used [The W3C CSS Validation Service](https://jigsaw.w3.org/). The `style.css` file is used for all the pages, but I've tested all pages individualy, just to make sure everything goes right.
- **Mobile testing:**
  - 1:
    ![Mobile Device report 1](../readme-images/lighthouse-index-mobile-testing.jpg)
  - 2:
    ![Mobile Device report 2](../readme-images/lighthouse-index-mobile-testing2.jpg)
- **Desktop testing:**
  - 1:
    ![Desktop Device report 1](../readme-images/lighthouse-index-desktop-testing.jpg)
  - 2:
    ![Desktop Device report 2](../readme-images/lighthouse-index-desktop-testing2.jpg)
- **Conclusions:**
- Performance score was affected by the external libraries I've used (Google Fonts, FontAwesome), but disabling them wasn't an option.
- CEO lower score across all pages ofthe website was caused by an anchor linking to an internal link.
  ![SEO Score](/readme-files/readme-images/lighthouse-SEO-low-score-cause.jpg)
  The suggested solution was to use `pre-connect` resource 'to estabilish early connection to thirst-party origins':
  ![Pre-Connect](../readme-images/lighthouse-performance-pre-connect.jpg)
- Below the SEO section there is a 'Mobile Friendly' recommandation, which suggests `Tap targets are not sized appropriately`, so I've tested all the links, especially the ones in the footer area, and testing them on smartphone devices looked and felt perfectly normal. The text is readable and the links are sized enought to be clickable.
  ![Mobile Friendly](../readme-images/lighthouse-mobile-friendly-recommandation.jpg "Mobile Friendly Recommandation")
## **Issues**
- On iPhone 13 mini using Safari browser there is an issue:
 - On **Café's Menu** page the internal links area is not displayed correctly.
  - ![](../readme-images/13mini-safari-details-element-closed.jpg)
  ![](../readme-images/13mini-safari-details-element-opened.jpg)

But on Samsung Galaxy S7 on Chrome is displayed correctly:
  - ![](../readme-images/s7-chrome-details-element-opened.jpg)

  - Searching online to solve this issue, I've' found out that there is a wide issue with Safari compatibility when using and styling the details element. A better solution would've been to avoid using this element.

- On a smartphone in landscape display mode, the menu is not scrollable and is displayed partially:

  - ![](../readme-images/s7-landscape-menu-display.jpg)

  --- 

[Back to top of the page](#testing)

[Back to MAIN README.md](../../README.md)