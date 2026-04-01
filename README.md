# Week 01: Personal Web Portfolio

## Author
- **Name:** Cheryl Adhiambo
- **GitHub:** https://github.com/Brigid-maker 
- **Date:** March 6, 2026

## Project Description
This project is a simple multi-page personal web portfolio created using HTML. The goal of the project is to practice web development basics such as creating web pages, structuring content using semantic HTML, linking pages together, and building a contact form.

The portfolio includes a home page, an about page, a projects page, and a contact page.

## Technologies Used
- HTML5

## Features
- Multi-page website structure
- Navigation menu linking all pages
- About page describing the author
- Projects page showing sample work
- Contact page with a functional form

## How to Run
1. Clone this repository
2. Open the project folder
3. Open `index.html` in any web browser

## Lessons Learned
While building this project, I learned how to:
- Create multiple HTML files
- Use semantic HTML elements
- Link pages using navigation menus
- Create forms using labels, inputs, and validation

## Challenges Faced
One challenge I faced was organizing multiple pages and ensuring the navigation links worked correctly. I solved this by checking the file names and ensuring all pages were connected properly.

Another challenge was creating a structured contact form with proper labels and input validation.

## Screenshots
Screenshots can be added here if needed.

## Live Demo
Not deployed yet.


/* ===============================
   1. RESET (Task 3.1)
================================ */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* ===============================
   2. DESIGN SYSTEM (Typography + Colors)
================================ */
:root {
    /* Fonts */
    --font-heading: 'Poppins', sans-serif;
    --font-body: 'Open Sans', sans-serif;

    /* Type Scale */
    --font-xs: 0.75rem;
    --font-sm: 0.875rem;
    --font-base: 1rem;
    --font-lg: 1.125rem;
    --font-xl: 1.25rem;
    --font-2xl: 1.5rem;
    --font-3xl: 1.875rem;
    --font-4xl: 2.25rem;

    /* Colors */
    --color-primary: #2563eb;
    --color-primary-light: #60a5fa;
    --color-primary-dark: #1d4ed8;

    --color-secondary: #7c3aed;

    --color-background: #f9fafb;
    --color-text: #1f2937;
    --color-muted: #6b7280;

    --color-white: #ffffff;
    --color-border: #e5e7eb;
}

/* ===============================
   3. BASE STYLES (Task 3.1)
================================ */
body {
    font-family: var(--font-body);
    font-size: 16px;
    line-height: 1.6;
    color: var(--color-text);
    background-color: var(--color-background);
    padding: 20px;
}

/* ===============================
   4. TYPOGRAPHY (Task 3.3)
================================ */
h1, h2, h3, h4, h5, h6 {
    font-family: var(--font-heading);
    color: var(--color-text);
    margin-bottom: 10px;
}

h1 {
    font-size: var(--font-4xl);
    font-weight: 700;
}

h2 {
    font-size: var(--font-3xl);
    font-weight: 600;
}

h3 {
    font-size: var(--font-2xl);
    font-weight: 600;
}

h4 {
    font-size: var(--font-xl);
    font-weight: 500;
}

h5 {
    font-size: var(--font-lg);
    font-weight: 400;
}

h6 {
    font-size: var(--font-base);
    font-weight: 300;
}

p {
    font-size: var(--font-base);
    margin-bottom: 15px;
}

small {
    font-size: var(--font-sm);
    color: var(--color-muted);
}

/* ===============================
   5. LINKS (Task 3.4)
================================ */
a {
    color: var(--color-primary);
    text-decoration: none;
}

a:hover {
    color: var(--color-primary-dark);
    text-decoration: underline;
}

/* ===============================
   6. BOX MODEL (Task 3.2)
================================ */
.box {
    width: 300px;
    padding: 20px;
    border: 2px solid var(--color-border);
    margin: 20px auto;
    background-color: var(--color-white);
}

/* Fixed broken box */
.broken-box {
    width: 300px;
    padding: 20px;
    border: none;
    box-sizing: border-box;
    background-color: #fca5a5;
    margin: 20px auto;
}

/* ===============================
   7. CARD COMPONENT (Task 3.2)
================================ */
.card {
    width: 300px;
    border: 1px solid var(--color-border);
    padding: 20px;
    margin: 20px auto;
    background-color: var(--color-white);
}

.card img {
    width: 100%;
    margin-bottom: 15px;
}

.card h3 {
    margin-bottom: 15px;
}

.card button {
    margin-top: 15px;
}

/* ===============================
   8. BUTTONS (Task 3.4)
================================ */
button {
    padding: 10px;
    border: none;
    background-color: var(--color-primary);
    color: var(--color-white);
    cursor: pointer;
    transition: all 0.3s ease;
}

button:hover {
    background-color: var(--color-primary-dark);
    transform: translateY(-2px);
}

/* ===============================
   9. FLEXBOX (Task 4 READY)
================================ */
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.nav-links {
    display: flex;
    gap: 20px;
}

.card-container {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
}

/* ===============================
   10. GRID (Task 4 READY)
================================ */
.gallery {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 15px;
}

.gallery img {
    width: 100%;
}

/* ===============================
   11. RESPONSIVE (Task 4.3)
================================ */
@media (min-width: 768px) {
    body {
        padding: 30px;
    }
}

@media (min-width: 1024px) {
    body {
        padding: 40px;
    }
}

/* ===============================
   12. POLISH (Task 4.4)
================================ */
.card {
    transition: all 0.3s ease;
}

.card:hover {
    box-shadow: 0 10px 20px rgba(0,0,0,0.1);
}

a:focus, button:focus {
    outline: 2px solid var(--color-primary);
    outline-offset: 2px;
}

img {
    max-width: 100%;
}