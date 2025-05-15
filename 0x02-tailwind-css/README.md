
# ProDev Frontend - CSS Grid and Flexbox with Tailwind

## Overview
This project is designed to help you master the use of Tailwind CSS for creating responsive, complex layouts using CSS Grid and Flexbox. By the end of this project, you'll be able to build responsive and aesthetically pleasing web pages using modern utility-first CSS techniques.

## Learning Objectives
- **Master Tailwind CSS Configuration:** Learn how to install and configure Tailwind CSS for seamless integration into projects.
- **Build Responsive Layouts:** Create complex, responsive layouts using Tailwind’s utility classes and responsive modifiers.
- **Combine CSS Grid and Flexbox:** Develop advanced page structures by combining both CSS Grid and Flexbox.
- **Design Aesthetically Pleasing Components:** Use Tailwind’s utilities to create visually appealing designs with gradients, spacing, and colors.
- **Optimize for Professional Development:** Enhance your professional web development skills by following best practices for structuring, coding, and managing CSS frameworks.

## Requirements
- Node.js installed on your local machine.
- Basic knowledge of HTML, CSS, and JavaScript.
- Familiarity with a code editor (e.g., VSCode) and browser developer tools.
- GitHub account for repository management.
- Tailwind CSS installed via npm or CDN.
- Modern browser to render and test designs.
- Internet connection for accessing Tailwind’s documentation and CDN links.

## Tasks

### 0. Setting Up and Installing Tailwind CSS with Configuration
- **Objective:** Set up and install Tailwind CSS.
- **Instructions:**
  - Install Tailwind CSS in your project.
  - Create a `tailwind.config.js` file with:
    ```js
    /** @type {import('tailwindcss').Config} */
    module.exports = {
      content: ["./src/**/*.{html,js}"],
      theme: {
        extend: {},
      },
      plugins: [],
    }
    ```
  - Create a `src` directory and inside it create `input.css` with:
    ```css
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
    ```
  - Run:
    ```bash
    npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
    ```
    ![Image](https://github.com/user-attachments/assets/5fb28ea2-c4d5-4eff-8b3d-ed7f09b459ef)
    
- **Repo Details:**
  - GitHub Repository: `alx-intermediate-frontend`
  - Directory: `0x02-tailwind-css`
  - Files: `src/input.css`, `src/output.css`, `tailwind.config.js`

### 1. Creating a Responsive CSS Grid Layout with Tailwind CSS
- **Objective:** Create a responsive 3-column layout.
- **Instructions:**
  - Create `1-index.html` and link Tailwind CSS.
  - Use:
    ```html
    <main class="grid grid-cols-3 gap-4">
    ```
  - Style `div`s with `bg-blue-200`, `bg-blue-300`, `bg-blue-400`, and `p-4`.
  - Add media query in `input.css`:
    ```css
    @media (max-width: 768px) {
      main {
        grid-template-columns: 1fr;
      }
    }
    ```
- **Repo Details:**
  - File: `1-index.html`

### 2. Building a Complex Page Layout with Nested CSS Grids Using Tailwind CSS
- **Objective:** Implement a complex layout with nested grids.
- **Instructions:**
  - Create `2-index.html` using 2x2 grids and style with `bg-blue-400`, `bg-blue-500`, `bg-red-200`.
- **Repo Details:**
  - File: `2-index.html`

### 3. Flexbox Basics - Build a Simple Navigation Bar
- **Objective:** Build a horizontal nav bar using Flexbox.
- **Instructions:**
  - Create `3-nav_index.html` and use Flexbox utilities and media queries.
- **Repo Details:**
  - File: `3-nav_index.html`

### 4. Create a Responsive Flexbox Layout with Tailwind
- **Objective:** Build a responsive layout.
- **Instructions:**
  - Create `4-flexbox_index.html` and use Flexbox on `main`, style `aside` and `section`.
- **Repo Details:**
  - File: `4-flexbox_index.html`

### 5. Combine CSS Grid and Flexbox for a Multi-Section Layout
- **Objective:** Use CSS Grid for large screens and Flexbox for small screens.
- **Instructions:**
  - Create `5-gridflex_index.html`.
- **Repo Details:**
  - File: `5-gridflex_index.html`

### 6. Build a Responsive Image Gallery Using CSS Grid
- **Objective:** Create an image gallery using CSS Grid.
- **Instructions:**
  - Use a responsive 3-column layout in `6-imageGallery.html`.
- **Repo Details:**
  - File: `6-imageGallery.html`

### 7. Manual Review
- **Objective:** Complete a manual review after project completion.

## Copyright
© 2025 ALX, All rights reserved.
