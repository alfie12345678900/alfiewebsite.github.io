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

<!-- menu.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Explore the menu at Alfie's Restaurant">
    <meta name="keywords" content="Alfie's Restaurant, Menu, Food">
    <meta name="author" content="Alfie's Restaurant">
    <title>Alfie's Restaurant - Menu</title>
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
        <section id="menu">
            <h2>Our Menu</h2>
            <ul>
                <li><strong>Breakfast Special:</strong> Full Irish Breakfast - €10.99</li>
                <li><strong>Lunch:</strong> Gourmet Burger with Fries - €12.99</li>
                <li><strong>Dinner:</strong> Grilled Salmon with Vegetables - €18.99</li>
                <li><strong>Desserts:</strong> Chocolate Lava Cake - €6.99</li>
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Alfie's Restaurant. All Rights Reserved.</p>
    </footer>
</body>
</html>

<!-- locations.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Find Alfie's Restaurant locations across Ireland">
    <meta name="keywords" content="Alfie's Restaurant, Locations, Ireland">
    <meta name="author" content="Alfie's Restaurant">
    <title>Alfie's Restaurant - Locations</title>
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
        <section id="locations">
            <h2>Our Locations</h2>
            <p>We are proud to serve you at multiple locations across Ireland:</p>
            <ul>
                <li><strong>Dublin:</strong> Main Street, Dublin</li>
                <li><strong>Cork:</strong> Harbour Road, Cork</li>
                <li><strong>Galway:</strong> Ocean Drive, Galway</li>
                <li><strong>Limerick:</strong> Riverbank Avenue, Limerick</li>
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Alfie's Restaurant. All Rights Reserved.</p>
    </footer>
</body>
</html>

<!-- contact.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Contact Alfie's Restaurant">
    <meta name="keywords" content="Alfie's Restaurant, Contact">
    <meta name="author" content="Alfie's Restaurant">
    <title>Alfie's Restaurant - Contact</title>
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
        <section id="contact">
            <h2>Contact Us</h2>
            <form id="contact-form">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="subject">Subject:</label>
                <input type="text" id="subject" name="subject">

                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>

                <button type="submit">Submit</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Alfie's Restaurant. All Rights Reserved.</p>
    </footer>
</body>
</html>
