<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nexlify Solutions - Empowering Your Future</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            line-height: 1.6;
            color: #333;
        }

        header {
            background: linear-gradient(to right, #2c3e50, #3498db);
            color: white;
            text-align: center;
            padding: 3rem 1rem;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }

        nav {
            background: #f4f4f4;
            padding: 1rem;
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 2rem;
        }

        nav a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }

        nav a:hover {
            color: #3498db;
        }

        .section {
            padding: 3rem 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        .about {
            background: #fff;
            text-align: center;
        }

        .services {
            background: #f9f9f9;
            text-align: center;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .service-card {
            background: white;
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        .contact {
            background: #fff;
            text-align: center;
        }

        .contact form {
            display: flex;
            flex-direction: column;
            max-width: 500px;
            margin: 1rem auto;
            gap: 1rem;
        }

        .contact input, .contact textarea {
            padding: 0.8rem;
            border: 1px solid #ddd;
            border-radius: 4px;
        }

        .contact button {
            background: #3498db;
            color: white;
            border: none;
            padding: 0.8rem;
            border-radius: 4px;
            cursor: pointer;
        }

        .contact button:hover {
            background: #2c3e50;
        }

        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 1rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Nexlify Solutions</h1>
        <p>Empowering Your Future with Innovative Technology</p>
    </header>

    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="about" class="section about">
        <h2>About Us</h2>
        <p>Nexlify Solutions is a forward-thinking technology company dedicated to providing cutting-edge solutions for businesses worldwide. Our team of experts specializes in transforming ideas into reality through innovation and expertise.</p>
    </section>

    <section id="services" class="section services">
        <h2>Our Services</h2>
        <div class="services-grid">
            <div class="service-card">
                <h3>Web Development</h3>
                <p>Custom websites tailored to your business needs, built with the latest technologies.</p>
            </div>
            <div class="service-card">
                <h3>Cloud Solutions</h3>
                <p>Scalable and secure cloud infrastructure to streamline your operations.</p>
            </div>
            <div class="service-card">
                <h3>AI Integration</h3>
                <p>Leverage artificial intelligence to enhance your products and services.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="section contact">
        <h2>Contact Us</h2>
        <p>Ready to take your business to the next level? Get in touch with us!</p>
        <form id="contact-form">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" rows="5" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Nexlify Solutions. All rights reserved.</p>
    </footer>

    <script>
        document.getElementById('contact-form').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Thank you for your message! We will get back to you soon.');
            this.reset();
        });
    </script>
</body>
</html>
run the code
