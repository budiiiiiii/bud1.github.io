# your_username-github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Photography Portfolio</title>
    <style>
        body {
            font-family: Atkinson Hyperlegible, Regular;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        header {
            background-color: #333;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav {
            margin: 0 auto;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
            font-size: 1.2rem;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1rem;
        }
        .gallery img {
            width: 100%;
            border-radius: 5px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
        .about, .contact {
            background-color: white;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
        }
        .about img {
            max-width: 150px;
            border-radius: 50%;
            margin-right: 1rem;
        }
        .about-text {
            display: flex;
            align-items: center;
        }
        form input, form textarea {
            width: 100%;
            padding: 0.5rem;
            margin: 0.5rem 0;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        form button {
            background-color: #333;
            color: white;
            border: none;
            padding: 0.75rem;
            border-radius: 5px;
            cursor: pointer;
        }
        @media only screen and (max-width: 600px) {
            nav a {
                display: block;
                margin: 0.5rem 0;
            }
            .about-text {
                flex-direction: column;
                align-items: flex-start;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Your Photography Portfolio</h1>
        <nav>
            <a href="#gallery">Portfolio</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <div class="container">
        <section id="gallery" class="gallery">
            <img src="image1.jpg" alt="Photography 1">
            <img src="image2.jpg" alt="Photography 2">
            <img src="image3.jpg" alt="Photography 3">
            <img src="image4.jpg" alt="Photography 4">
            <!-- Add more images as needed -->
        </section>

        <section id="about" class="about">
            <h2>About Me</h2>
            <div class="about-text">
                <img src="your-photo.jpg" alt="Your Photo">
                <p>Hi, I'm [Your Name], a passionate photographer specializing in [type of photography]. I love capturing moments that tell stories, and my portfolio showcases some of my best work. Feel free to explore, and if you'd like to collaborate or have any inquiries, head over to my contact page!</p>
            </div>
        </section>

        <section id="contact" class="contact">
            <h2>Contact Me</h2>
            <form action="mailto:your-email@example.com" method="post" enctype="text/plain">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Your Photography. All Rights Reserved.</p>
    </footer>

</body>
</html>
