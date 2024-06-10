
CodeCrafters Website - README

Table of Contents

Project Overview
Technologies Used
Folder Structure
File Descriptions
Features
Media Queries
ScrollReveal Animations
Credits
Project Overview

CodeCrafters is a landing page for a platform that helps organizations find and assess top technical talent. It provides information about the platform's features, testimonials from users, and calls-to-action for potential clients to get started or request a demo.

Technologies Used
HTML5
CSS3
JavaScript
ScrollReveal.js for scroll animations

Folder Structure
scss
Copy code
project-root/
│
├── index.html
├── styles.css
├── images/
│   ├── blue-background.jpg
│   ├── dashboard.jpg
│   └── man-smiling.jpg
├── icons/
│   ├── code-solid.svg
│   ├── chart-simple-solid.svg
│   ├── rocket-solid.svg
│   └── sitemap-solid.svg
└── README.md


File Descriptions


index.html

The main HTML file that contains the structure of the webpage.
Includes sections for the navbar, hero section, about section, steps for assessment, testimonials, call-to-action, and footer.

styles.css

Contains the CSS styles for the webpage.
Defines variables for colors, styles for each section, buttons, images, and media queries for responsiveness.

images/

Contains images used in the project such as the background image, dashboard image, and man smiling image.

icons/

Contains SVG icons used for various elements like the logo and example illustrations.

Features

Responsive Design: The website adapts to different screen sizes using media queries.
Scroll Animations: Elements are revealed as the user scrolls down the page using ScrollReveal.js.
Call-to-Action Buttons: Encourages users to get started with the platform or request a demo.
Testimonials Section: Displays feedback from users of the platform.
Informative Content: Provides information about the platform's features and benefits.

Media Queries

@media screen and (max-width: 830px)
Hides navigation links in the navbar.
Adjusts the size and layout of various elements for better viewing on smaller screens.

@media screen and (max-width: 500px)
Further adjusts styles for very small screens.
Hides certain buttons and reduces font sizes for better readability.

Element-specific Animations:

Navbar, about section text, third step, third stat: { delay: 500, origin: 'top' }
Hero content, dashboard, first step, first stat: { delay: 200, origin: 'top' }
Hero span, logos, second step, second stat: { delay: 300, origin: 'bottom' }
Buttons in hero section: { delay: 500, origin: 'left' }
Hero paragraph, sda image: { delay: 500, origin: 'right' }
sda text: { delay: 250, origin: 'left' }

Credits

Images: Provided in the images folder.
Icons: SVG icons in the icons folder.
ScrollReveal.js: Used for scroll animations. ScrollReveal.js
Feel free to reach out if you have any questions or need further assistance. Enjoy exploring CodeCrafters!
