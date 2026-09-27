# Portfolio Website – Animated Version

## Overview

This project is a personal portfolio website for **Tahendra Chaudhary**. It presents an introduction, selected projects, and a contact form in a modern animated interface.

The website is built using **HTML5, CSS3, and JavaScript** and is designed as a lightweight static front-end project.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Font Awesome 6.4.0 CDN

## Project Structure

```text
Portfolio Website/
├── Index.html
├── Styles.css
└── Script.js
```

### File Description

- **Index.html** — Contains the complete portfolio page structure, navigation, About section, Projects section, Contact form, and footer.
- **Styles.css** — Contains the complete visual design, animated gradient background, responsive layout, project cards, contact form, buttons, and animations.
- **Script.js** — Adds smooth scrolling to navigation links and handles contact-form submission feedback.

## Main Sections

### 1. Header

The header introduces Tahendra Chaudhary and displays the profile description as a Java and React Developer.

### 2. Navigation

The navigation menu provides links to:

- About
- Projects
- Contact

JavaScript enables smooth scrolling when these links are clicked.

### 3. About Me

The About section contains a short professional introduction.

### 4. Projects

The project area contains three project cards:

- Portfolio Website
- Mini E-commerce
- React Dashboard

### 5. Contact Me

The contact section contains a form with:

- Name
- Email
- Message
- Send Message button

The form is handled on the client side. On submission, JavaScript displays a confirmation message and resets the form.

### 6. Footer

The footer contains the copyright notice.

## Design Features

- Animated multi-color gradient background
- Responsive layout
- Animated waving hand icon
- Font Awesome icons
- Navigation hover effects
- Project-card hover animation
- Animated section entrance effects
- Styled contact form
- Animated submit button
- Mobile layout using a CSS media query

## JavaScript Functionality

### Smooth Scrolling

Navigation links use `scrollIntoView()` with smooth behavior to move to the selected section without an abrupt page jump.

### Contact Form

The contact form prevents the default browser submission and displays:

> Thanks for your message, I will get back to you soon!

The form is then reset.

## Responsive Design

The stylesheet includes a media query for screens up to **600px** wide. On smaller screens:

- Navigation items become vertically arranged.
- The main heading becomes smaller.
- Project cards are displayed in a single column.

## How to Run

No installation or build process is required.

1. Extract the project folder.
2. Open the folder in VS Code.
3. Make sure `Index.html`, `Styles.css`, and `Script.js` remain in the same folder.
4. Open `Index.html` in a browser.
5. For easier development, use the **Live Server** extension in VS Code.

## External Dependency

The project loads Font Awesome icons from its CDN link in `Index.html`. An internet connection may therefore be required for the icons to appear when running the page normally.

## Learning Outcomes

This project demonstrates:

- Semantic HTML page organization
- CSS layouts and responsive design
- CSS animations and transitions
- Grid and Flexbox usage
- Navigation styling
- Form styling
- JavaScript DOM selection
- JavaScript event handling
- Smooth scrolling
- Client-side form interaction

## Limitations

The contact form is currently a front-end demonstration only. It does not send the submitted message to an email server or database.

## Author

**Tahendra Chaudhary**

Portfolio project developed using HTML, CSS, and JavaScript.
