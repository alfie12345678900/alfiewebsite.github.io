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

    <script>
        // JavaScript for Image Slider
        const slides = document.querySelectorAll(".slider img");
        let currentSlide = 0;

        function showSlide(index) {
            slides.forEach((slide, i) => {
                slide.classList.toggle("active", i === index);
            });
        }

        document.getElementById("prev").addEventListener("click", () => {
            currentSlide = (currentSlide > 0) ? currentSlide - 1 : slides.length - 1;
            showSlide(currentSlide);
        });

        document.getElementById("next").addEventListener("click", () => {
            currentSlide = (currentSlide < slides.length - 1) ? currentSlide + 1 : 0;
            showSlide(currentSlide);
        });

        // JavaScript for Accordion
        const accordionButtons = document.querySelectorAll(".accordion-btn");
        accordionButtons.forEach(button => {
            button.addEventListener("click", () => {
                const content = button.nextElementSibling;
                content.classList.toggle("active");
            });
        });

        // JavaScript for Contact Form Submission
        const contactForm = document.getElementById("contact-form");
        contactForm.addEventListener("submit", (event) => {
            event.preventDefault();
            const formData = new FormData(contactForm);
            alert(`Thank you, ${formData.get("name")}! We will respond to your query soon.`);
            contactForm.reset();
        });
    </script>
</body>
</html>
