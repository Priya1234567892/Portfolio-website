# Portfolio-website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Your Name - Portfolio</title>
</head>
<body>
    <header>
        <h1>Your Name</h1>
        <p>Web Developer | Designer</p>
    </header>
    <nav>
        <ul>
            <li><a href="#about">About Me</a></li>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <section id="about">
        <h2>About Me</h2>
        <p>
            Welcome to my portfolio website! I am a web developer and designer with a passion for creating beautiful and functional websites.
        </p>
    </section>

    /* Reset some default styles */
body, h1, h2, p {
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
}

header {
    text-align: center;
    background-color: #333;
    color: #fff;
    padding: 20px;
}

nav ul {
    list-style: none;
    text-align: center;
}

nav li {
    display: inline;
    margin: 0 20px;
}

nav a {
    text-decoration: none;
    color: #333;
}

section {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    background-color: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    margin-bottom: 20px;
}

.project img {
    max-width: 100%;
}

/* Add more CSS styles to customize your portfolio */
