# Final Project and Deployment

## Objectives
Build a fully functional web application.
Apply HTML, CSS, and JavaScript concepts learned.
Deploy the project using GitHub Pages, Netlify, or Vercel.

## Instructions
Choose one of the following project ideas:
Blog Website: Implement a multi-page site with navigation.
Ecommerce Website: Implement a multi-page site with navigation.

>[!NOTE]
> - Include at least:
> - A responsive design.
> - JavaScript interactivity.
> - A deployment link.

## Tasks

Create a well-structured HTML5 document.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alex's Simple Blog</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Alex's Blog</h1>
        <p>Exploring the web, one tag at a time 🌐</p>
        <nav>
            <a href="#blog">Blog</a> |
            <a href="#about">About</a> |
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Main Content -->
    <main id="blog">
        <article>
            <h2>My First Post: Learning HTML5</h2>
            <img src="https://via.placeholder.com/600x200" alt="HTML5 graphic" />
            <p>Today I wrote my first complete HTML5 page. I learned about semantic tags like <code>&lt;header&gt;</code>, <code>&lt;main&gt;</code>, and <code>&lt;footer&gt;</code>. It’s amazing how clean and organized code can be!</p>
            <p>HTML is the foundation of all web pages. Next, I plan to explore CSS and JavaScript to make my pages interactive.</p>
            <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank">Learn more about HTML5</a>
        </article>

        <aside id="about">
            <h3>About the Author</h3>
            <img src="https://via.placeholder.com/100" alt="Author photo" />
            <p>I'm Alex, a beginner web developer on a journey to build beautiful and useful websites. I love clean code and strong coffee ☕.</p>
        </aside>
    </main>

    <!-- Footer -->
    <footer id="contact">
        <p>Contact: <a href="mailto:alex@example.com">alex@example.com</a></p>
        <p>&copy; 2025 Alex's Blog. All rights reserved.</p>
    </footer>

</body>
</html>


Use at least 5 different HTML elements.
Ensure semantic correctness.

| Element                | Purpose                                  |
| ---------------------- | ---------------------------------------- |
| `<header>`             | Introductory content or navigation links |
| `<main>`               | Primary page content                     |
| `<article>`            | A self-contained piece of content        |
| `<aside>`              | Related info (like a sidebar or bio)     |
| `<footer>`             | Footer content with copyright info       |
| `<h1>`, `<h2>`, `<h3>` | Headings for structure and SEO           |
| `<p>`                  | Paragraphs for text content              |


Good luck and happy coding! 🚀💻
