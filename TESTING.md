# Testing

Return back to the [README.md](README.md) file.

## Code Validation

### HTML

- I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.
- All files were validated using the live deployed site pages.
- It was noted that all pages had the same error of 1 x closing div missing from the nav section. This was due to the code being re-used from the index file before correction.
- The confirmation page had a space missing from content in the refresh meta tag.
- All errors have been corrected as shown in the table below.

| Page | W3C URL | Screenshot errors | Screenshot fixed | Notes |
| --- | --- | --- | --- | --- |
| Home | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fboderg.github.io%2Fthe-bread-shed%2F) | ![screenshot](documentation/validation/html-validation/home-validation-errors.png) | ![screenshot](documentation/validation/html-validation/home-validation-fixed.png) | closing div tag missing from nav section - fixed |
| Sandwich Menu | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fboderg.github.io%2Fthe-bread-shed%2Fsandwich-menu.html) | ![screenshot](documentation/validation/html-validation/sandwich-menu-validation-errors.png) | ![screenshot](documentation/validation/html-validation/sandwich-menu-validation-fixed.png) | closing div tag missing from nav section - fixed  |
| Drinks Menu | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fboderg.github.io%2Fthe-bread-shed%2Fdrinks-menu.html) | ![screenshot](documentation/validation/html-validation/drinks-menu-validation-errors.png) | ![screenshot](documentation/validation/html-validation/drinks-menu-validation-fixed.png) | closing div tag missing from nav section - fixed  |
| Snacks Menu | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fboderg.github.io%2Fthe-bread-shed%2Fsnacks-menu.html) | ![screenshot](documentation/validation/html-validation/snacks-menu-validation-errors.png) | ![screenshot](documentation/validation/html-validation/snacks-menu-validation-fixed.png) | closing div tag missing from nav section - fixed  |
| Contact | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fboderg.github.io%2Fthe-bread-shed%2Fcontact.html) | ![screenshot](documentation/validation/html-validation/contact-page-validation-errors.png) | ![screenshot](documentation/validation/html-validation/contact-page-validation-fixed.png) | closing div tag missing from nav section - fixed  |
| Confirmation | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fboderg.github.io%2Fthe-bread-shed%3F) | ![screenshot](documentation/validation/html-validation/confirmation-page-validation-errors.png) | ![screenshot](documentation/validation/html-validation/confirmation-page-validation-fixed.png) | closing div tag missing from nav section and space missing from content descriptor in refresh meta tag - fixed  |

### CSS

- I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.
- The screenshot shows a pass in relation to the css file that was validated by copy and paste method.
- The copy and paste method was used because the validator is trying to validate the bootstrap elements that have been used.
- The link below is for the URL test method and shows many warnings due to the bootstrap elements and vendor specific styles used.

| File | Jigsaw URL | Screenshot | Notes |
| --- | --- | --- | --- |
| style.css | [Jigsaw](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fboderg.github.io%2Fthe-bread-shed%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en) | ![screenshot](documentation/validation/css-validation.png) | Pass: No Errors |

## Browser Compatibility

- I've tested my deployment of The Bread Shed on multiple browsers to check for compatibility issues.
- As well as checking for page functionality, all social links were tested to ensure they open in new tabs.
- Each page was tested and a screenshot taken in each of the browsers below. A representation of this is shown in the table below.

| Browser | Screenshot 1 | Screenshot 2 | Notes |
| --- | --- | --- | --- |
| [Brave](https://brave.com/download) | ![screenshot](documentation/browser-compatibility/brave-screenshots/brave-home-page.png) | ![screenshot](documentation/browser-compatibility/brave-screenshots/brave-offcanvas-about.png) | Works as expected |
| [Chrome](https://www.google.com/chrome) | ![screenshot](documentation/browser-compatibility/chrome-screenshots/chrome-offcanvas-menu.png) | ![screenshot](documentation/browser-compatibility/chrome-screenshots/chrome-sandwich-menu.png) | Works as expected |
| [Edge](https://www.microsoft.com/edge) | ![screenshot](documentation/browser-compatibility/edge%20-screenshots/edge-drinks-menu.png) | ![screenshot](documentation/browser-compatibility/edge%20-screenshots/edge-snacks-menu.png) | Works as expected |
| [Firefox (Developer Edition)](https://www.mozilla.org/firefox/developer) | ![screenshot](documentation/browser-compatibility/firefox-screenshots/firefoc-contact-top.png) | ![screenshot](documentation/browser-compatibility/firefox-screenshots/firefox-contact-bottom.png) | Works as expected |
| [Opera](https://www.opera.com/download) | ![screenshot](documentation/browser-compatibility/opera-screenshots/opera-confirmation.png) | ![screenshot](documentation/browser-compatibility/opera-screenshots/opera-target-blank-links.png) | Works as expected |

## Responsiveness

- I've tested my deployment of The Bread Shed on multiple devices to check for responsiveness issues.
- The devices tested on were presets within devtools in the chrome browser along with my own personal Samsung Galaxy S10+, 1080p standard and 1440p ultrawide monitors.

| Device | Screenshot | Screenshot | Notes |
| --- | --- | --- | --- |
| Mobile iPhone SE (DevTools) | ![screenshot](documentation/responsiveness/dev-tools-screenshots/responsive-home-top-mobile.png) | ![screenshot](documentation/responsiveness/dev-tools-screenshots/responsive-home-bottom-mobile.png) | Works as expected |
| Tablet iPad Air (DevTools) | ![screenshot](documentation/responsiveness/dev-tools-screenshots/responsive-nav-tablet.png) | ![screenshot](documentation/responsiveness/dev-tools-screenshots/repsonsive-about-tablet.png) | Works as expected |
| Desktop (DevTools)| ![screenshot](documentation/responsiveness/dev-tools-screenshots/responsive-sandwich-desktop.png) | ![screenshot](documentation/responsiveness/dev-tools-screenshots/responsive-drinks-desktop.png) | Works as expected |
| Standard 1080p 16:9 Monitor | ![screenshot](documentation/responsiveness/1080p-standard-monitor-screenshots/chrome-contact-top.png) | ![screenshot](documentation/responsiveness/1080p-standard-monitor-screenshots/chrome-contact-bottom.png) | Works as expected |
| XL Monitor 1440p 21:9 Ultrawide | ![screenshot](documentation/responsiveness/1440p-ultrawide-screenshots/nav-ultrawide.png) | ![screenshot](documentation/responsiveness/1440p-ultrawide-screenshots/about-ultrawide.png) | Works as expected |
| Samsung Galaxy S10+ | ![screenshot](documentation/responsiveness/samsung-galaxy-s10%2B-screenshots/galaxy-s10%2B-home.jpg) | ![screenshot](documentation/responsiveness/samsung-galaxy-s10%2B-screenshots/galaxy-s10%2B-confirmation.jpg) | Works as expected |

## Lighthouse Audit

- I've tested my deployment of The Bread Shed using the Lighthouse Audit tool to check for any major issues.
- No major issues were noted.
- Some performance issues noted due to larger content loads.
- All images compressed and converted to .webp format for faster load times.
- All script tags have been placed at the bottom of the html body for faster load times.

| Page | Size | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | Mobile | ![screenshot](documentation/lighthouse/mobile-home-crop.png) | Few warnings |
| Home | Desktop | ![screenshot](documentation/lighthouse/desktop-home-crop.png) | Few warnings |
| Sandwich Menu | Mobile | ![screenshot](documentation/lighthouse/mobile-sandwich-crop.png) | Slow response due to large content |
| Sandwich Menu | Desktop | ![screenshot](documentation/lighthouse/desktop-sandwich-crop.png) | Few warnings |
| Drinks Menu | Mobile | ![screenshot](documentation/lighthouse/mobile-drinks-crop.png) | Few warnings |
| Drinks Menu | Desktop | ![screenshot](documentation/lighthouse/desktop-drinks-crop.png) | No warnings to note |
| Snacks Menu | Mobile | ![screenshot](documentation/lighthouse/mobile-snacks-crop.png) | Few warnings |
| Snacks Menu | Desktop | ![screenshot](documentation/lighthouse/desktop-snacks-crop.png) | No warnings to note |
| Contact | Mobile | ![screenshot](documentation/lighthouse/mobile-contact-crop.png) | Slow response time due to large content |
| Contact | Desktop | ![screenshot](documentation/lighthouse/desktop-contact-crop.png) | Few warnings |

## User Story Testing

I've tested my deployment of The Bread Shed to ensure that it meets the user stories listed.

| User Story | Screenshot |
| --- | --- |
| As a new site user, I would like to easily understand the main purpose of the site, so that I can learn more about what it has to offer. | ![screenshot](documentation/features/the-bread-shed-navigation-header.png) |
| As a new site user, I would like to easily navigate through the site, so that I can easily make a choice from what is on offer. | ![screenshot](documentation/features/offcanvas-navigation-menu.png) |
| As a new site user, I would like to easily see what others think, so that I can decide if what is on offer will suit my tastes. | ![screenshot](documentation/features/scrolling-carousel.png) |
| As a new site user, I would like to easily be able to see their social media interaction, so that I can see if the have any publicised offers or loyalty schemes. | ![screenshot](documentation/features/social-media-links.png) |
| As a returning site user, I would like to find a good selection, so that I can try something different each time. | ![screenshot](documentation/features/sandwich-menu.png) |
| As a returning site user, I would like to be able to make contact, so that I can make suggestions or post comments / testimonials. | ![screenshot](documentation/features/contact-form.png) |
| As a returning site user, I would like to find good value, so that I can feel satisfied without breaking the bank. | ![screenshot](documentation/features/sandwich-menu.png) |
| As a returning site user, I would like to see a wide range of drinks and snacks, so that I can compliment my meal choice. | ![screenshot](documentation/features/drinks-menu.png) |

## Bugs

The following are bugs that I have come across while creating The Bread Shed site.

- Overflow-x - On two of the pages I had an overflow on the x-axis.

  ![screenshot](documentation/bugs/overflow-crop.png)

  - To fix this, I added a container-fluid class to the footer.

- Favicon - Chrome devtools kept warning that favicon.ico was not loading.

  ![screenshot](documentation/bugs/favicon-error-crop.png)

  - To fix this, I created a favicon and added the link to the html header on each page.

- Uncaught in promise error - Chrome devtools was giving a cross origin error that was relating to an extension in the browser trying to access the web page.

  ![screenshot](documentation/bugs/uncaught-in-promise-error-crop.png)

  - To fix this, I disabled the Adobe reader extension and this stopped the error warning.

## Unfixed Bugs

- Permission policy error - Chrome devtools gives this warning on the version that I am using. It appears to be a deprecated trial for data collection instead of using cookies.

  ![screenshot](documentation/bugs/permission-policy-crop.png)

  - I was unsuccessful at fixing this, however this does not affect the operation of the site and this trial operation is also blocked by GitHub as it breaks privacy policy.

- About Us - The about us link at the bottom of the page will not transform on hover.

  ![screenshot]()

  - I was unsuccessful at fixing this. I can get the surrounding column to transform but not the link itself. I suspect that this is a setting within bootstrap that will need further investigation.

There are no remaining bugs that I am aware of.
