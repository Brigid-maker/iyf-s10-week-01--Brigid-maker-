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

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
    content="width=device-width,
    initial-scale=1.0">
<title> I am Cheryl Brigid</title>

<!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

    <!-- Your CSS file -->
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
<li><a href="index.html">Home</a></li> |
<li><a href="about.html">About</a></li> |
<li><a href="projects.html">Projects</a></li> |
<li><a href="contact.html">Contact</a></li>
</ul>
</nav>
    </header>
<h1 style="color: red;">Welcome To My Portfolio</h1>
<img width="150" height="150" alt="image" src="https://github.com/user-attachments/assets/fc29918b-f188-47d8-a893-1833d9915ddd" />

<p>I am currently learning Computer Programming at We Can Academy. I am passionate about web development and Program Design. Always eager to learn and grow in the tech community.</p>

<section class="card">
<h2>My hobbies</h2>
<ol> 
<li>Reading</li>
<li>Dancing</li>
<li>Watching</li>
</ol> 
</section>

<section class="card">
<h3>Favourite Website</h3>
  <a href="https://github.com">GitHub</a>
</section>

<section class="card">
<h4>Email</h4>
<p><a href="mailto:adhiambocheryl2018@gmail.com">adhiambocheryl2018@gmail.com</a></p>
</section>
<button class="btn">Click Me</button>
</body>
</html>


