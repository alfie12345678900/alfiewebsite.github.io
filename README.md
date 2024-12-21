<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Welcome to Alfie's Restaurant, showcasing our menu, locations, and contact details.">
    <meta name="keywords" content="Alfie's Restaurant, Ireland, Menu, Locations, Contact">
    <meta name="author" content="Alfie's Restaurant">
    <title>Alfie's Restaurant - Home</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="locations.html">Locations</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <!-- Home Section -->
        <section id="home">
            <h1>Welcome to Alfie's Restaurant</h1>
            <p>Delicious food served with love at multiple locations across Ireland.</p>
            <h2>Opening Hours</h2>
            <p>Monday - Friday: 8:00 AM - 10:00 PM</p>
            <p>Saturday - Sunday: 9:00 AM - 11:00 PM</p>

            <h2>Address</h2>
            <p>Main Street, Dublin, Ireland</p>

            <h2>Follow Us</h2>
            <p>
                <a href="https://instagram.com/alfiesrestaurant" target="_blank">Instagram</a> | 
                <a href="https://facebook.com/alfiesrestaurant" target="_blank">Facebook</a>
            </p>

            <h2>Contact Us</h2>
            <p>Email: <a href="mailto:contact@alfiesrestaurant.ie">contact@alfiesrestaurant.ie</a></p>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Alfie's Restaurant. All Rights Reserved.</p>
    </footer>
</body>
</html>

/* styles.css */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: space-around;
    background-color: #333;
}

header nav ul li {
    margin: 0;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    padding: 15px 20px;
    display: block;
}

header nav ul li a:hover {
    background-color: #575757;
}

@media (max-width: 768px) {
    header nav ul {
        flex-direction: column;
    }
    header nav ul li a {
        text-align: center;
    }
}

.slider {
    position: relative;
    max-width: 100%;
    margin: auto;
    overflow: hidden;
}

.slider img {
    width: 100%;
    display: none;
}

.slider img.active {
    display: block;
}

#prev, #next {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    background-color: rgba(0, 0, 0, 0.5);
    color: white;
    border: none;
    padding: 10px;
    cursor: pointer;
}

#prev {
    left: 10px;
}

#next {
    right: 10px;
}

@media (max-width: 768px) {
    #prev, #next {
        padding: 5px;
    }
}

.accordion .accordion-btn {
    background-color: #333;
    color: white;
    border: none;
    padding: 15px;
    width: 100%;
    text-align: left;
    cursor: pointer;
    margin-bottom: 5px;
}

.accordion .accordion-content {
    display: none;
    padding: 15px;
    background-color: #f1f1f1;
}

.accordion .accordion-content.active {
    display: block;
}

@media (max-width: 768px) {
    .accordion .accordion-btn {
        font-size: 14px;
        padding: 10px;
    }
    .accordion .accordion-content {
        font-size: 12px;
    }
}

#contact-form {
    max-width: 600px;
    margin: auto;
    padding: 20px;
    border: 1px solid #ddd;
    border-radius: 5px;
    background-color: #f9f9f9;
}

#contact-form label {
    display: block;
    margin-bottom: 10px;
    font-weight: bold;
}

#contact-form input, #contact-form textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ddd;
    border-radius: 5px;
}

#contact-form button {
    background-color: #333;
    color: white;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
    border-radius: 5px;
}

@media (max-width: 768px) {
    #contact-form {
        padding: 10px;
    }
    #contact-form label {
        font-size: 14px;
    }
    #contact-form input, #contact-form textarea {
        font-size: 14px;
        padding: 8px;
    }
}
