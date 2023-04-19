# Testing

Return back to the [README.md](README.md) file.

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Page     | W3C URL                                                                                                     | Screenshot                                              | Notes                               |
| -------- | ----------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- | ----------------------------------- |
| Home     | [W3C](https://validator.w3.org/nu/?doc=https://dougyb83.github.io/Lunas-Leopard-Geckos/index.html)   | ![screenshot](documentation/testing/html-validation-home.png)     | Pass: No Errors  |
| Available geckos  | [W3C](https://validator.w3.org/nu/?doc=https://dougyb83.github.io/Lunas-Leopard-Geckos/available-geckos.html) | ![screenshot](documentation/testing/html-validation-available-geckos.png)  | Section lacks heading h2-h6 warning            |
| FAQ     | [W3C](https://validator.w3.org/nu/?doc=https://dougyb83.github.io/Lunas-Leopard-Geckos/faq.html)    | ![screenshot](documentation/testing/html-validation-faq.png)     | Section lacks heading h2-h6 warning                     |
| Contact | [W3C](https://validator.w3.org/nu/?doc=https://dougyb83.github.io/Lunas-Leopard-Geckos/contact.html)   | ![screenshot](documentation/testing/html-validation-contact.png) | Section lacks heading h2-h6 warning      |
| Confirmation |[W3C](https://validator.w3.org/nu/?doc=https://dougyb83.github.io/Lunas-Leopard-Geckos/confirmation.html)    | ![screenshot](documentation/testing/html-validation-confirmation.png) | Pass: No Errors                     |
| 404        | [W3C](https://validator.w3.org/nu/?doc=https://dougyb83.github.io/Lunas-Leopard-Geckos/404.html)  | ![screenshot](documentation/testing/html-validation-404.png) | Pass: No Errors |

### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.


| File         | Jigsaw URL                                                                                                       | Screenshot                                             | Notes                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------ | ---------------------------------- |
| style.css    | [Jigsaw](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fdougyb83.github.io%2FLunas-Leopard-Geckos) | ![screenshot](documentation/testing/css-validation-style.png)    | Pass: No Errors                    |


## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser           | Screenshot                                     | Screenshot                                     | Screenshot                                     | Screenshot                                     | Notes                                |
| ----------------- | ---------------------------------------------- | ---------------------------------------------- | ---------------------------------------------- | ---------------------------------------------- | ------------------------------------ |
| Chrome            | ![screenshot](documentation/testing/browser-chrome.png)  | ![screenshot](documentation/testing/browser-chrome-avail.png)  | ![screenshot](documentation/testing/browser-chrome-faq.png)  | ![screenshot](documentation/testing/browser-chrome-contact.png)  | Works as expected                    |
| Firefox           | ![screenshot](documentation/testing/browser-firefox.png)  | ![screenshot](documentation/testing/browser-firefox-avail.png)  | ![screenshot](documentation/testing/browser-firefox-faq.png)  | ![screenshot](documentation/testing/browser-firefox-contact.png)  | Works as expected                    |
| Edge              | ![screenshot](documentation/testing/browser-edge.png)  | ![screenshot](documentation/testing/browser-edge-avail.png)  | ![screenshot](documentation/testing/browser-edge-faq.png)  | ![screenshot](documentation/testing/browser-edge-contact.png)  | Works as expected                    |
| Brave             | ![screenshot](documentation/testing/browser-brave.png)  | ![screenshot](documentation/testing/browser-brave-avail.png)  | ![screenshot](documentation/testing/browser-brave-faq.png)  | ![screenshot](documentation/testing/browser-brave-contact.png)  | Works as expected                    |
| Opera             | ![screenshot](documentation/testing/browser-opera.png)  | ![screenshot](documentation/testing/browser-opera-avail.png)  | ![screenshot](documentation/testing/browser-opera-faq.png)  | ![screenshot](documentation/testing/browser-opera-contact.png)  | Works as expected                    |

## Responsiveness

I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device             | Screenshot                                        | Screenshot                                        | Screenshot                                        | Screenshot                                        | Notes                               |
| ------------------ | ------------------------------------------------- | ------------------------------------------------- | ------------------------------------------------- | ------------------------------------------------- | ----------------------------------- |
| Mobile (DevTools)  | ![screenshot](documentation/testing/responsive-mobile-dev-home.png)  | ![screenshot](documentation/testing/responsive-mobile-dev-avail.png)  |![screenshot](documentation/testing/responsive-mobile-dev-faq.png)  |![screenshot](documentation/testing/responsive-mobile-dev-contact.png)  |Works as expected                   |
| Tablet (DevTools)  | ![screenshot](documentation/testing/responsive-tablet-dev-home.png)  | ![screenshot](documentation/testing/responsive-tablet-dev-avail.png)  |![screenshot](documentation/testing/responsive-tablet-dev-faq.png)  |![screenshot](documentation/testing/responsive-tablet-dev-contact.png)  |Works as expected                   |
| Desktop            | ![screenshot](documentation/testing/responsive-desktop-home.png) | ![screenshot](documentation/testing/responsive-desktop-avail.png)  |![screenshot](documentation/testing/responsive-desktop-faq.png)  |![screenshot](documentation/testing/responsive-desktop-contact.png)  |Works as expected                |
| Google Pixel 4a | ![screenshot](documentation/testing/responsive-mobile-pixel-home.png)   | ![screenshot](documentation/testing/responsive-mobile-pixel-avail.png)  |![screenshot](documentation/testing/responsive-mobile-pixel-faq.png)  |![screenshot](documentation/testing/responsive-mobile-pixel-contact.png)  | Works as expected                  |
| Samsung Galaxy S8          | ![screenshot](documentation/testing/responsive-mobile-s8-home.png)  | ![screenshot](documentation/testing/responsive-mobile-s8-avail.png)  |![screenshot](documentation/testing/responsive-mobile-s8-faq.png)  |![screenshot](documentation/testing/responsive-mobile-s8-contact.png)  | Works as expected                  |
| Samsung Galaxy S21 Ultra          | ![screenshot](documentation/testing/responsive-mobile-s21-home.png)  | ![screenshot](documentation/testing/responsive-mobile-s21-avail.png)  |![screenshot](documentation/testing/responsive-mobile-s21-faq.png)  |![screenshot](documentation/testing/responsive-mobile-s21-contact.png)  | Works as expected                   |
| Samsung Galaxy tab 4          | ![screenshot](documentation/testing/responsive-tablet-tab4-home.png)  | ![screenshot](documentation/testing/responsive-tablet-tab4-avail.png)  |![screenshot](documentation/testing/responsive-tablet-tab4-faq.png)  |![screenshot](documentation/testing/responsive-tablet-tab4-contact.png)  | Works as expected                   |


## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page    | Size    | Screenshot                                                | Notes                                   |
| ------- | ------- | --------------------------------------------------------- | --------------------------------------- |
| Home    | Mobile  | ![screenshot](documentation/testing/lighthouse-home-mobile.png)     | Some minor warnings                     |
| Home    | Desktop | ![screenshot](documentation/testing/lighthouse-home-desktop.png)    | No major problems                            |
| Available Geckos   | Mobile  | ![screenshot](documentation/testing/lighthouse-avail-mobile.png)    | No major problems                     |
| Available Geckos   | Desktop | ![screenshot](documentation/testing/lighthouse-avail-desktop.png)   | No major problems                            |
| FAQ | Mobile  | ![screenshot](documentation/testing/lighthouse-faq-mobile.png)  | Some minor warnings  |
| FAQ | Desktop | ![screenshot](documentation/testing/lighthouse-faq-desktop.png) | No major problems  |
| Contact | Mobile | ![screenshot](documentation/testing/lighthouse-contact-desktop.png) | No major problems  |
| Contact | Desktop | ![screenshot](documentation/testing/lighthouse-contact-desktop.png) | No major problems  |

## User Story Testing

| User Story                                                                             | Screenshot                               |
| -------------------------------------------------------------------------------------- | ---------------------------------------- |
| As a new site user, I would like to quickly see the sites purpose.          | ![screenshot](documentation/jumbotron.png) |
| As a new site user, I would like to see clear navigation, so that I can easily move back and forward between pages.          | ![screenshot](documentation/navbar-desktop.png) |
| As a new site user, I would like any information to be clear and to the point, so that I can make an informed decision.          | ![screenshot](documentation/faq-cards.png) |
| As a new site user, I would like to be able to contact the site owner, so that I can make a purchase.          | ![screenshot](documentation/contact-form.png) |
| As a new site user, I would like to find the sites social media pages.          | ![screenshot](documentation/footer.png) |
| As a new site user, I would like to view the site on any device.          | ![screenshot](documentation/testing/responsive-mobile-s21-home.png) |
| As a returning site user, I would like to see up to date stock information.    | ![screenshot](documentation/testing/browser-chrome-avail.png) |
| As a returning site user, I would like to refresh my knowledge by viewing fact references.    | ![screenshot](documentation/faq-cards.png) |
| As a site administrator, The code should have proper indentation so that it is clear for myself and others to read. | ![screenshot](documentation/code-example.png) |
| As a site administrator, The code should be properly signposted to make it easy to navigate. | ![screenshot](documentation/code-example.png) |
| As a site administrator, I should be able to respond to user enquiries. | ![screenshot](documentation/contact-form.png) |

## Bugs

- JS Uncaught ReferenceError: `foobar` is undefined/not defined

  ![screenshot](documentation/bug01.png)

  - To fix this, I _____________________.
- JS `'let'` or `'const'` or `'template literal syntax'` or `'arrow function syntax (=>)'` is available in ES6 (use `'esversion: 11'`) or Mozilla JS extensions (use moz).

  ![screenshot](documentation/bug02.png)

  - To fix this, I _____________________.
- Python `'ModuleNotFoundError'` when trying to import module from imported package

  ![screenshot](documentation/bug03.png)

  - To fix this, I _____________________.
- Django `TemplateDoesNotExist` at /appname/path appname/template_name.html

  ![screenshot](documentation/bug04.png)

  - To fix this, I _____________________.
- Python `E501 line too long` (93 > 79 characters)

  ![screenshot](documentation/bug04.png)

  - To fix this, I _____________________.

## Unfixed Bugs

There are no remaining bugs that I am aware of.
