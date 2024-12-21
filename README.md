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
                <li><a href="#home">Home</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#location">Location</a></li>
                <li><a href="#contact">Contact</a></li>
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
        </section>

        <!-- Menu Section -->
        <section id="menu">
            <h2>Our Menu</h2>
            <div class="menu-items">
                <div class="menu-item">
                    <img src="images/pizza.jpg" alt="Pizza">
                    <h3>Margherita Pizza</h3>
                    <p>Classic pizza with fresh tomatoes, mozzarella, and basil.</p>
                </div>
                <div class="menu-item">
                    <img src="images/pasta.jpg" alt="Pasta">
                    <h3>Spaghetti Bolognese</h3>
                    <p>Rich meat sauce served over tender spaghetti.</p>
                </div>
                <div class="menu-item">
                    <img src="images/burger.jpg" alt="Burger">
                    <h3>Classic Cheeseburger</h3>
                    <p>Juicy beef patty topped with cheddar cheese and fresh vegetables.</p>
                </div>
            </div>
        </section>

        <!-- Location Section -->
        <section id="location">
            <h2>Our Location</h2>
            <p>Visit us at Main Street, Dublin, Ireland.</p>
            <div class="map-container">
                <iframe 
                    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2381.6218836324446!2d-6.260310684172085!3d53.34980527997924!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x48670e9ddf2447b1%3A0x2b7b5a6d5d79b99!2sMain%20Street%2C%20Dublin%2C%20Ireland!5e0!3m2!1sen!2sie!4v1700000000000!5m2!1sen!2sie" 
                    width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2>Contact Us</h2>
            <p>Email: <a href="mailto:contact@alfiesrestaurant.ie">contact@alfiesrestaurant.ie</a></p>
            <p>Phone: <a href="tel:+353899999999">089 999 9999</a></p>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Alfie's Restaurant. All Rights Reserved.</p>
    </footer>
</body>
</html>

