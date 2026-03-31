# TinDog – Bootstrap Startup Website

Responsive landing page for a fictional dog dating app called TinDog. This project was built with Bootstrap and focuses on layout, reusable components, responsive design, and cleaner structure compared to writing everything manually with plain CSS.

## Main features

- Built as a multi-section landing page for a fictional startup product.
- Uses Bootstrap 5 through CDN for styling, layout, and responsive utilities.
- Includes a **hero/title section** with:
  - main heading
  - call-to-action download buttons
  - iPhone mockup image
- Includes a **features section** with icons and short selling points such as:
  - easy to use
  - elite clientele
  - guaranteed to work
- Includes a **testimonial section** with:
  - customer quote
  - profile image
  - supporting brand logos
- Includes a **pricing section** using Bootstrap cards for different subscription plans:
  - Chihuahua
  - Labrador
  - Mastiff
- Includes a **footer section** with multiple columns of navigation links.
- Uses Bootstrap’s grid system (`container`, `row`, `col`) to make the layout responsive across different screen sizes.
- Uses Bootstrap utility classes for:
  - spacing (`p-*`, `m-*`)
  - typography
  - alignment
  - button styles
  - colors and backgrounds
- Combines Bootstrap classes with a separate custom stylesheet for extra styling and project-specific adjustments.

## What I learned

- How Bootstrap makes layout faster by using ready-made classes instead of writing all CSS from scratch.
- How to use the Bootstrap grid system to control responsive layouts with rows and columns.
- How to build reusable sections with Bootstrap components like cards and buttons.
- How utility classes can handle spacing, alignment, font weight, and colors directly in HTML.
- How to combine Bootstrap with custom CSS when the built-in styles are not enough.
- How responsive design becomes much easier when planning sections with containers, rows, and breakpoints.

## Project structure

- `index.html`  
  Main page of the TinDog landing website. Contains all major sections:
  - title / hero
  - features
  - testimonial
  - pricing
  - footer

- `css/styles.css` or `solution.css`  
  Custom styling added on top of Bootstrap for colors, gradients, image rotation, spacing tweaks, and other design details.

- `images/`  
  Stores images used in the page, such as:
  - iPhone mockup
  - dog profile image
  - partner / press logos

## How to run

1. Clone the repo:

   git clone https://github.com/<your-username>/tindog-bootstrap-website.git  
   cd tindog-bootstrap-website  

2. Open the project folder in VS Code or any code editor.

3. Open `index.html` in the browser:
   - either double-click the file
   - or use the VS Code “Live Server” extension

4. Make sure you are connected to the internet if Bootstrap is loaded through CDN, so the Bootstrap CSS and JS files can be fetched correctly.

## Notes

- This is a front-end practice project focused on Bootstrap layout and responsive design.
- It does not include backend logic or real app functionality.
- The main goal was to learn how to structure a cleaner, more responsive landing page using Bootstrap instead of building every section manually from scratch.
