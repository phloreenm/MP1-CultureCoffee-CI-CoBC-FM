Back to MAIN [README.md](../../README.md)

<div style="display:flex; flex-wrap:wrap; lign-items: baseline;; min-height:225px">
    <div style="display:flex;margin:0 auto; align-items:center;">
    <a href="https://phloreenm.github.io/MP1-CultureCoffee-CI-CoBC-FM/"><img src="../../readme-files/readme-images/cc-logo-bg1.png" alt="Website Logo" width="200px" height="200px"/></a>
    </div>
    <div style="display:flex; margin:0 auto; align-items:center;">
    <h1 style="color:#ECE7E1; background-color:#552F1E; font-weight:700; text-align:center;padding:1em;border:1px solid transparent; border-radius:10px;">Culture Coffee café - Milestone Project 1</h1>
    </div>
</div>

---

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
  * [**Accessability**](#accessability)

## **During Development Testing**
While developing the website I've tested its functionality locally (Live Server in VS Code or through `python3 -m http.server command`), but also the deployed page on GitHub Pages.

1. I've conducted manual testing for each element for appearance and responsiveness via a simulated live server using an extension in VSCode.
    
1. The webpage was deployed on GitHub Pages and I've asked few friends to check the page as a normal user and then send me a feedback.

1. Created 

### ***Manual Testing:***
* During testing, I used four different browsers to ensure cross-compatibility. The desktop browsers used by myself were:

  1. Chrome
  2. Firefox  
  3. Opera
  4. Edge
  6. Safari


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
- CEO lower score was caused by an anchor linking to an internal link.
  ![SEO Score](/readme-files/readme-images/lighthouse-SEO-low-score-cause.jpg)
  The suggested solution was to use `pre-connect` resource 'to estabilish early connection to thirst-party origins':
  ![Pre-Connect](../readme-images/lighthouse-performance-pre-connect.jpg)
- Below the SEO section there is a 'Mobile Friendly' recommandation, which suggests `Tap targets are not sized appropriately`, so I've tested all the links, especially the ones in the footer area, and testing them on smartphone devices looked and felt perfectly normal. The text is readable and the links are sized enought to be clickable.
  ![Mobile Friendly](../readme-images/lighthouse-mobile-friendly-recommandation.jpg)