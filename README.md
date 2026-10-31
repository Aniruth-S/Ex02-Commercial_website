# Ex02-Commercial_website

## Date:30/10/2026

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
**index.html**
```html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>LUXORA | Textiles & Furniture</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>

    <!-- Navigation -->
    <header>
        <div class="logo">
            LUXORA<span>.</span>
            <small>TEXTILES & FURNITURE</small>
        </div>

        <nav>
            <a href="#home">Home</a>
            <a href="#textiles">Textiles</a>
            <a href="#furniture">Furniture</a>
            <a href="#offers">Offers</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>

        <a href="#contact" class="nav-btn">Enquire Now</a>
    </header>


    <!-- Hero Section -->
    <section class="hero" id="home">

        <div class="hero-content">

            <span class="hero-label">WELCOME TO LUXORA</span>

            <h1>
                Make Every<br>
                Space <span>Beautiful.</span>
            </h1>

            <p>
                Discover a world of beautiful textiles and
                stylish furniture. Bring comfort, colour and
                elegance into your everyday life.
            </p>

            <div class="hero-buttons">
                <a href="#textiles" class="btn primary">
                    Explore Products
                </a>

                <a href="#contact" class="btn secondary">
                    Contact Us
                </a>
            </div>

        </div>

        <div class="hero-image">
            <img src="images/hero-interior.jpg"
            alt="Modern luxury home interior">
        </div>

    </section>


    <!-- Categories -->
    <section class="categories">

        <div class="section-heading">
            <span>EXPLORE OUR WORLD</span>
            <h2>Shop By Category</h2>
            <p>Everything you need to create your perfect lifestyle.</p>
        </div>

        <div class="category-container">

            <a href="#textiles" class="category-card">
                <img src="images/designer-sarees.jpg"
                alt="Textile collection">

                <div class="category-info">
                    <h3>Textiles</h3>
                    <p>Explore Fabrics & Collections →</p>
                </div>
            </a>

            <a href="#furniture" class="category-card">
                <img src="images/luxury-sofas.jpg"
                alt="Furniture collection">

                <div class="category-info">
                    <h3>Furniture</h3>
                    <p>Explore Home Furniture →</p>
                </div>
            </a>

        </div>

    </section>


    <!-- Textile Products -->
    <section class="products" id="textiles">

        <div class="section-heading">
            <span>COLOUR YOUR WORLD</span>
            <h2>Our Textile Collection</h2>
            <p>Beautiful fabrics for every occasion and every home.</p>
        </div>

        <div class="product-container">

            <div class="product-card">
                <img src="images/designer-sarees.jpg"
                alt="Designer sarees">

                <div class="product-info">
                    <span class="product-type">ETHNIC WEAR</span>
                    <h3>Designer Sarees</h3>
                    <p>Starting from ₹999</p>

                    <a href="https://wa.me/919876543210?text=Hello%20LUXORA%2C%20I%20am%20interested%20in%20Designer%20Sarees."
                    class="product-btn">Enquire on WhatsApp</a>
                </div>
            </div>

            <div class="product-card">
                <img src="images/premium-shirts.jpg"
                alt="Premium shirts">

                <div class="product-info">
                    <span class="product-type">MEN'S COLLECTION</span>
                    <h3>Premium Shirts</h3>
                    <p>Starting from ₹599</p>

                    <a href="https://wa.me/919876543210?text=Hello%20LUXORA%2C%20I%20am%20interested%20in%20Premium%20Shirts."
                    class="product-btn">Enquire on WhatsApp</a>
                </div>
            </div>

            <div class="product-card">
                <img src="images/designer-curtains.jpg"
                alt="Designer curtains">

                <div class="product-info">
                    <span class="product-type">HOME DECOR</span>
                    <h3>Designer Curtains</h3>
                    <p>Starting from ₹499</p>

                    <a href="https://wa.me/919876543210?text=Hello%20LUXORA%2C%20I%20am%20interested%20in%20Designer%20Curtains."
                    class="product-btn">Enquire on WhatsApp</a>
                </div>
            </div>

            <div class="product-card">
                <img src="images/luxury-bedsheets.jpg"
                alt="Luxury bedsheets">

                <div class="product-info">
                    <span class="product-type">BEDDING</span>
                    <h3>Luxury Bedsheets</h3>
                    <p>Starting from ₹799</p>

                    <a href="https://wa.me/919876543210?text=Hello%20LUXORA%2C%20I%20am%20interested%20in%20Luxury%20Bedsheets."
                    class="product-btn">Enquire on WhatsApp</a>
                </div>
            </div>

        </div>

    </section>


    <!-- Furniture Products -->
    <section class="products furniture-section" id="furniture">

        <div class="section-heading">
            <span>COMFORT MEETS DESIGN</span>
            <h2>Our Furniture Collection</h2>
            <p>Transform your home with beautiful and comfortable furniture.</p>
        </div>

        <div class="product-container">

            <div class="product-card">
                <img src="images/luxury-sofas.jpg"
                alt="Luxury sofas">

                <div class="product-info">
                    <span class="product-type">LIVING ROOM</span>
                    <h3>Luxury Sofas</h3>
                    <p>Starting from ₹14,999</p>

                    <a href="https://wa.me/919876543210?text=Hello%20LUXORA%2C%20I%20am%20interested%20in%20Luxury%20Sofas."
                    class="product-btn">Enquire on WhatsApp</a>
                </div>
            </div>

            <div class="product-card">
                <img src="images/designer-beds.jpg"
                alt="Designer beds">

                <div class="product-info">
                    <span class="product-type">BEDROOM</span>
                    <h3>Designer Beds</h3>
                    <p>Starting from ₹19,999</p>

                    <a href="https://wa.me/919876543210?text=Hello%20LUXORA%2C%20I%20am%20interested%20in%20Designer%20Beds."
                    class="product-btn">Enquire on WhatsApp</a>
                </div>
            </div>

            <div class="product-card">
                <img src="images/dining-tables.jpg"
                alt="Dining tables">

                <div class="product-info">
                    <span class="product-type">DINING ROOM</span>
                    <h3>Dining Tables</h3>
                    <p>Starting from ₹9,999</p>

                    <a href="https://wa.me/919876543210?text=Hello%20LUXORA%2C%20I%20am%20interested%20in%20Dining%20Tables."
                    class="product-btn">Enquire on WhatsApp</a>
                </div>
            </div>

            <div class="product-card">
                <img src="images/modern-chairs.jpg"
                alt="Modern chairs">

                <div class="product-info">
                    <span class="product-type">HOME FURNISHING</span>
                    <h3>Modern Chairs</h3>
                    <p>Starting from ₹2,499</p>

                    <a href="https://wa.me/919876543210?text=Hello%20LUXORA%2C%20I%20am%20interested%20in%20Modern%20Chairs."
                    class="product-btn">Enquire on WhatsApp</a>
                </div>
            </div>

        </div>

    </section>


    <!-- Special Offers -->
    <section class="offers" id="offers">

        <div class="offer-content">

            <span>LIMITED TIME DEALS</span>

            <h2>
                Something Special<br>
                Is Waiting For You!
            </h2>

            <p>
                Discover exciting deals on selected textiles
                and furniture. Give your home a fresh new look.
            </p>

            <a href="#contact" class="offer-btn">
                Discover Offers →
            </a>

        </div>

        <div class="offer-decoration">
            <h3>EXCLUSIVE</h3>
            <h2>OFFERS</h2>
            <p>ON SELECTED COLLECTIONS</p>
        </div>

    </section>


    <!-- About Us -->
    <section class="about" id="about">

        <div class="about-image">
            <img src="images/hero-interior.jpg"
            alt="Beautiful home interior">
        </div>

        <div class="about-content">

            <span>WHO WE ARE</span>

            <h2>Welcome to LUXORA</h2>

            <p>
                LUXORA is your destination for beautiful textiles
                and stylish furniture. We believe that the right
                combination of colours, fabrics and furniture
                can transform any space.
            </p>

            <p>
                From elegant clothing fabrics to modern home
                furniture, we bring together quality, comfort
                and beautiful designs under one roof.
            </p>

            <a href="#contact" class="btn primary">
                Get In Touch
            </a>

        </div>

    </section>


    <!-- Contact -->
    <section class="contact" id="contact">

        <div class="section-heading">
            <span>WE ARE HERE TO HELP</span>
            <h2>Let's Connect!</h2>
            <p>Have a question about our products? Contact us today.</p>
        </div>

        <div class="contact-details">

            <div class="contact-box">
                <h3>Visit Our Store</h3>
                <p>Your Shop Address, Tamil Nadu, India</p>
            </div>

            <div class="contact-box">
                <h3>Call Us</h3>
                <p>+91 98765 43210</p>
            </div>

            <div class="contact-box">
                <h3>Email Us</h3>
                <p>luxora@example.com</p>
            </div>

        </div>

        <a href="https://wa.me/919876543210?text=Hello%20LUXORA%2C%20I%20would%20like%20to%20know%20more%20about%20your%20products."
        class="whatsapp-btn">
            Chat With Us on WhatsApp
        </a>

    </section>


    <!-- Footer -->
    <footer>

        <div class="footer-logo">LUXORA<span>.</span></div>

        <p>Textiles & Furniture</p>

        <p>Bringing Colours, Comfort & Elegance Into Your Life.</p>

        <div class="footer-links">
            <a href="#home">Home</a>
            <a href="#textiles">Textiles</a>
            <a href="#furniture">Furniture</a>
            <a href="#contact">Contact</a>
        </div>

        <p class="copyright">
            © 2026 LUXORA. All Rights Reserved.
        </p>

    </footer>

</body>
</html>
```
**style.css**
```css

/* GLOBAL STYLING */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Arial, sans-serif;
}

html {
    scroll-behavior: smooth;
}

body {
    background: #fffdf9;
    color: #292638;
}

:root {
    --purple: #673ab7;
    --pink: #ed5794;
    --orange: #f39a3c;
    --dark: #292638;
    --light: #fff5eb;
}


/* HEADER */

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 18px 7%;
    background: white;
    position: sticky;
    top: 0;
    z-index: 100;
    box-shadow: 0 2px 12px rgba(0,0,0,0.06);
}

.logo {
    font-size: 30px;
    font-weight: 800;
    color: var(--purple);
    letter-spacing: 2px;
}

.logo span,
.footer-logo span {
    color: var(--pink);
}

.logo small {
    display: block;
    font-size: 9px;
    letter-spacing: 3px;
    color: #777;
}

nav {
    display: flex;
    gap: 22px;
}

nav a {
    text-decoration: none;
    color: var(--dark);
    font-size: 14px;
    font-weight: 600;
    transition: 0.3s;
}

nav a:hover {
    color: var(--pink);
}

.nav-btn {
    background: var(--purple);
    color: white;
    padding: 12px 20px;
    border-radius: 25px;
    text-decoration: none;
    font-size: 13px;
}


/* HERO SECTION */

.hero {
    display: flex;
    align-items: center;
    gap: 40px;
    padding: 70px 8%;
    background: linear-gradient(120deg, #fff0e5, #f5eaff);
    min-height: 570px;
}

.hero-content {
    flex: 1;
}

.hero-label,
.section-heading span,
.about-content span,
.offer-content span {
    color: var(--pink);
    font-weight: bold;
    letter-spacing: 3px;
    font-size: 12px;
}

.hero h1 {
    font-size: 65px;
    line-height: 1.12;
    margin: 20px 0;
    color: var(--dark);
}

.hero h1 span {
    color: var(--purple);
}

.hero-content p {
    color: #666;
    line-height: 1.8;
    max-width: 450px;
}

.hero-image {
    flex: 1;
}

.hero-image img {
    width: 100%;
    height: 400px;
    object-fit: cover;
    border-radius: 20px;
    box-shadow: 15px 15px 0 #ed5794;
}

.hero-buttons {
    margin-top: 30px;
    display: flex;
    gap: 15px;
}

.btn {
    display: inline-block;
    text-decoration: none;
    padding: 14px 24px;
    border-radius: 25px;
    font-weight: 600;
    transition: 0.3s;
}

.primary {
    background: var(--purple);
    color: white;
}

.primary:hover {
    background: #49248c;
}

.secondary {
    border: 2px solid var(--purple);
    color: var(--purple);
}

.secondary:hover {
    background: var(--purple);
    color: white;
}


/* SECTION HEADINGS */

section {
    padding: 75px 8%;
}

.section-heading {
    text-align: center;
    margin-bottom: 40px;
}

.section-heading h2 {
    font-size: 36px;
    margin: 12px 0;
}

.section-heading p {
    color: #777;
}


/* CATEGORY SECTION */

.category-container {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 30px;
}

.category-card {
    position: relative;
    height: 380px;
    border-radius: 18px;
    overflow: hidden;
    text-decoration: none;
}

.category-card img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: 0.5s;
}

.category-card:hover img {
    transform: scale(1.08);
}

.category-info {
    position: absolute;
    bottom: 0;
    width: 100%;
    padding: 30px;
    color: white;
    background: linear-gradient(transparent, rgba(0,0,0,0.85));
}

.category-info h3 {
    font-size: 30px;
}

.category-info p {
    margin-top: 8px;
}


/* PRODUCT SECTION */

.products {
    background: #fff5eb;
}

.furniture-section {
    background: #f0eaff;
}

.product-container {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 25px;
}

.product-card {
    background: white;
    border-radius: 15px;
    overflow: hidden;
    box-shadow: 0 5px 20px rgba(0,0,0,0.05);
    transition: 0.3s;
}

.product-card:hover {
    transform: translateY(-8px);
    box-shadow: 0 12px 25px rgba(0,0,0,0.12);
}

.product-card img {
    width: 100%;
    height: 220px;
    object-fit: cover;
}

.product-info {
    padding: 20px;
}

.product-type {
    color: var(--pink);
    font-size: 10px;
    font-weight: bold;
    letter-spacing: 2px;
}

.product-info h3 {
    margin: 10px 0;
    font-size: 19px;
}

.product-info p {
    color: var(--purple);
    font-weight: bold;
    margin-bottom: 18px;
}

.product-btn {
    display: block;
    text-align: center;
    background: #25a75a;
    color: white;
    text-decoration: none;
    padding: 11px;
    border-radius: 8px;
    font-size: 12px;
    font-weight: bold;
    transition: 0.3s;
}

.product-btn:hover {
    background: #167d3e;
}


/* OFFERS SECTION */

.offers {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 30px;
    background: linear-gradient(120deg, #673ab7, #ed5794);
    color: white;
}

.offer-content {
    max-width: 550px;
}

.offer-content span {
    color: #ffdc8c;
}

.offer-content h2 {
    font-size: 40px;
    margin: 20px 0;
}

.offer-content p {
    line-height: 1.8;
    color: #f4e9ff;
}

.offer-btn {
    display: inline-block;
    background: #ffca70;
    color: #292638;
    padding: 14px 25px;
    border-radius: 25px;
    text-decoration: none;
    font-weight: bold;
    margin-top: 25px;
}

.offer-decoration {
    border: 3px dashed white;
    border-radius: 50%;
    width: 250px;
    height: 250px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    transform: rotate(-8deg);
}

.offer-decoration h3 {
    font-size: 20px;
}

.offer-decoration h2 {
    font-size: 40px;
    color: #ffdc8c;
}

.offer-decoration p {
    font-size: 10px;
    letter-spacing: 2px;
}


/* ABOUT SECTION */

.about {
    display: flex;
    align-items: center;
    gap: 55px;
}

.about-image {
    flex: 1;
}

.about-image img {
    width: 100%;
    height: 380px;
    object-fit: cover;
    border-radius: 18px;
}

.about-content {
    flex: 1;
}

.about-content h2 {
    font-size: 38px;
    margin: 15px 0;
}

.about-content p {
    color: #777;
    line-height: 1.9;
    margin-bottom: 15px;
}


/* CONTACT SECTION */

.contact {
    background: #fff5eb;
    text-align: center;
}

.contact-details {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    margin: 40px 0;
}

.contact-box {
    background: white;
    padding: 30px 15px;
    border-radius: 12px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.05);
}

.contact-box h3 {
    color: var(--purple);
    margin-bottom: 12px;
}

.contact-box p {
    color: #777;
}

.whatsapp-btn {
    display: inline-block;
    background: #25a75a;
    color: white;
    text-decoration: none;
    padding: 15px 30px;
    border-radius: 30px;
    font-weight: bold;
}

.whatsapp-btn:hover {
    background: #167d3e;
}


/* FOOTER */

footer {
    text-align: center;
    background: #292638;
    color: white;
    padding: 45px 15px;
}

.footer-logo {
    font-size: 32px;
    font-weight: bold;
    letter-spacing: 3px;
}

footer p {
    color: #ccc;
    margin-top: 12px;
}

.footer-links {
    display: flex;
    justify-content: center;
    gap: 25px;
    margin: 25px 0;
}

.footer-links a {
    color: white;
    text-decoration: none;
}

.footer-links a:hover {
    color: #ed5794;
}

.copyright {
    font-size: 12px;
    border-top: 1px solid #514c60;
    padding-top: 20px;
}


/* RESPONSIVE DESIGN */

@media (max-width: 1000px) {

    header {
        flex-wrap: wrap;
        gap: 20px;
        justify-content: center;
    }

    .product-container {
        grid-template-columns: repeat(2, 1fr);
    }

    .hero h1 {
        font-size: 48px;
    }
}

@media (max-width: 650px) {

    header {
        position: static;
    }

    nav {
        flex-wrap: wrap;
        justify-content: center;
        gap: 15px;
    }

    .hero {
        flex-direction: column;
        padding: 50px 6%;
    }

    .hero h1 {
        font-size: 42px;
    }

    .hero-image img {
        height: 280px;
    }

    .hero-buttons {
        flex-wrap: wrap;
    }

    .category-container,
    .product-container,
    .contact-details {
        grid-template-columns: 1fr;
    }

    .category-card {
        height: 300px;
    }

    .offers {
        flex-direction: column;
        text-align: center;
    }

    .offer-content h2 {
        font-size: 30px;
    }

    .offer-decoration {
        width: 200px;
        height: 200px;
    }

    .about {
        flex-direction: column;
    }

    .about-content h2 {
        font-size: 30px;
    }

    .footer-links {
        flex-wrap: wrap;
    }

    section {
        padding: 50px 6%;
    }
}
```

## OUTPUT
![alt text](image.png)

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
