## COMMON ATTACKS ON WEB APPLICATIONS

# Restreview: Preventing Cross Site Scripting (XSS) Attacks

### Background
Welcome to Restreview!

Restreview is an application that publicly compiles reviews on selected restaurants.

The product is in the very early stages, and we’re taking over the development of the landing page to review a restaurant. We’re working closely with a new intern and, unfortunately, the current code hasn’t been secured properly and is vulnerable to different types of XSS attacks!

For this project, we’ll focus on implementing best practices and adding layers of security to protect the app from DOM-Based, Reflected, and Stored XSS Attacks.

We’ll make use of `helmet` and `express-validator` as well as explore how to use alternative methods from the document object in order to prevent any potential attacks on the application.


## Project

this project demonstrates simple measures aagainst **DOM-Based, Reflected and Stored XSS attacks**.

+ **DOM-based**: by using `Element.textContent` instead of `document.write`
+ **Stored and reflected** : by using `helmet`, `express-validator` libraries to validate and sanitize user input
