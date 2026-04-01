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
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>

    <!-- CSS -->
    <link rel="stylesheet" href="styles.css">

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&family=Open+Sans:wght@400;500&display=swap" rel="stylesheet">
</head>
<body>

    <div class="container">

        <!-- HERO SECTION -->
        <header>
            <h1>Welcome To My Portfolio</h1>
            <p>
                I am currently learning Computer Programming at We Can Academy. 
                I am passionate about web development and always eager to learn.
            </p>
        </header>

        <!-- HOBBIES -->
        <section>
            <h2>My Hobbies</h2>
            <ol>
                <li>Reading</li>
                <li>Dancing</li>
                <li>Watching</li>
            </ol>
        </section>

        <!-- FAVORITE WEBSITE -->
        <section>
            <h2>Favourite Website</h2>
            <p>
                <a href="https://github.com" target="_blank">Visit GitHub</a>
            </p>
            <button>Reach Out</button>
        </section>

        <!-- BOX MODEL (Task 3.2) -->
        <section>
            <h2>Box Model Practice</h2>

            <div class="box">Box 1</div>
            <div class="box">Box 2</div>
            <div class="box">Box 3</div>
            <div class="box">Box 4</div>

            <div class="broken-box">Fixed Box (300px total)</div>
        </section>

        <!-- CARD COMPONENT -->
        <section>
            <h2>Project Card</h2>

            <div class="card">
                <img src="https://via.placeholder.com/300" alt="Project">
                <h3>My Project</h3>
                <p>This is a sample project card showing layout and spacing.</p>
                <button>View Project</button>
            </div>
        </section>

        <!-- CONTACT -->
        <section>
            <h2>Contact</h2>
            <p>Email: your@email.com</p>
        </section>

    </div>

</body>
</html>