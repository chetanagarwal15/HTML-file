<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #444;
            color: #fff;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
        }
        .container {
            padding: 20px;
            max-width: 800px;
            margin: 0 auto;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">
        <section id="home">
            <h2>Home</h2>
            <p>This is the home section of the website. You can include an introduction or welcome message here.</p>
        </section>

        <section id="about">
            <h2>About</h2>
            <p>This section is for information about the website or the individual or organization behind it.</p>
        </section>

        <section id="services">
            <h2>Services</h2>
            <p>Detail the services you offer or the features of your website here.</p>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>Provide contact information or a contact form in this section.</p>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 My Simple Website</p>
    </footer>
</body>
</html>
