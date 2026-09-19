# Technical Documentation

## Project Overview

This project is a responsive personal portfolio website created using HTML, CSS, and JavaScript.

The website contains three main sections:
- About Me
- Projects
- Contact

It also includes responsive styling and a JavaScript interaction for the contact form.

## Technologies Used

- HTML5 for the page structure
- CSS3 for styling and responsive design
- JavaScript for user interaction
- Git and GitHub for version control
- WebStorm as the development environment

## Project Structure

202260260-WalaaAlmarzooq-assignment1/
- assets/
    - images/
        - banking-project.svg
        - orbit-project.svg
- css/
    - styles.css
- docs/
    - ai-usage-report.md
    - technical-documentation.md
- js/
    - script.js
- index.html
- README.md
- .gitignore

## HTML Structure

The main HTML file is `index.html`.

It includes:
- A header with the portfolio name
- Navigation links
- An About Me section
- A Projects section
- A Contact section
- A footer

The navigation links use section IDs such as:

`#about`

`#projects`

`#contact`

This allows users to move directly to each section.

## CSS Styling

The stylesheet is located in:

`css/styles.css`

CSS is used to:
- Set fonts, colors, spacing, and backgrounds
- Style the navigation bar
- Style project cards
- Style the contact form
- Style buttons and hover effects
- Keep the website layout clean and readable

Flexbox is used in the header and navigation area.

## Responsive Design

A media query is used for smaller screens:

`@media (max-width: 768px)`

When the screen becomes smaller:
- The header changes from a horizontal layout to a vertical layout
- Navigation links adjust to fit the available space
- Page padding and heading sizes are reduced

This helps the website display properly on desktop, tablet, and mobile devices.

## JavaScript Functionality

The JavaScript file is located in:

`js/script.js`

JavaScript is used for the contact form.

When the user submits the form:
1. The default page refresh is prevented.
2. A confirmation message is displayed.
3. The form fields are cleared.

This provides simple user interaction without requiring a backend server.

## Images

The project section includes two SVG placeholder images:
- Banking Management System
- Orbit Classification System

The images are stored in:

`assets/images/`

## Testing

The website was tested by:
- Opening `index.html` in a browser
- Testing the navigation links
- Testing the contact form
- Checking the browser Console for JavaScript errors
- Resizing the browser window to test responsive design
- Checking that project images display correctly

The browser Console did not show JavaScript errors during testing.

## Limitations

The contact form does not send messages to a server because the assignment does not require a backend.

The form currently demonstrates front-end interaction only.