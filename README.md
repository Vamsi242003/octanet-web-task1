//landing.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Haven</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">Book Haven</div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Bestsellers</a></li>
                <li><a href="#">New Arrivals</a></li>
                <li><a href="#">Genres</a></li>
                <li><a href="#">Author Spotlight</a></li>
                <li><a href="#">Deals</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>
        </nav>
        <div class="search-bar">
            <input type="text" placeholder="Search for books, authors, genres...">
        </div>
    </header>

    <section class="hero">
        <h1>Discover Your Next Great Read at Book Haven</h1>
        <p>Explore thousands of books, exclusive deals, and author insights.</p>
        <button>Shop Now</button>
    </section>

    <section class="bestsellers">
        <h2>Bestsellers</h2>
        <div class="carousel"></div>
        <button>View All Bestsellers</button>
    </section>

    <section class="new-arrivals">
        <h2>New Arrivals</h2>
        <div class="grid"></div>
        <button>Browse New Arrivals</button>
    </section>

    <section class="genres">
        <h2>Browse by Genre</h2>
        <div class="grid"></div>
        <button>Explore Genres</button>
    </section>

    <section class="author-spotlight">
        <h2>Author Spotlight</h2>
        <div class="featured-author"></div>
        <button>Read More</button>
    </section>

    <section class="customer-reviews">
        <h2>What Our Readers Say</h2>
        <div class="testimonials"></div>
        <button>Read More Reviews</button>
    </section>

    <section class="exclusive-deals">
        <h2>Exclusive Deals</h2>
        <div class="banners"></div>
        <button>Shop Deals</button>
    </section>

    <section class="newsletter">
        <h2>Stay Updated!</h2>
        <p>Sign up for our newsletter to get the latest on new arrivals and exclusive deals.</p>
        <form>
            <input type="email" placeholder="Email address">
            <button type="submit">Subscribe</button>
        </form>
    </section>

    <footer>
        <div class="quick-links">
            <a href="#">About Us</a>
            <a href="#">Careers</a>
            <a href="#">Privacy Policy</a>
            <a href="#">Terms of Service</a>
        </div>
        <div class="contact-info">
            <p>Address: 123 tenali,guntur</p>
            <p>Phone: (123) 456-7890</p>
            <p>Email: nayakbhai143@gmail.com</p>
        </div>
        <div class="social-media">
            <a href="#">Facebook</a>
            <a href="#">Twitter</a>
            <a href="#">Instagram</a>
            <a href="#">Pinterest</a>
        </div>
    </footer>
</body>
</html>


//styles.css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 20px;
    background-color: #333;
    color: white;
}
header .logo {
    font-size: 24px;
    font-weight: bold;
}
header nav ul {
    list-style: none;
    display: flex;
    gap: 15px;
}
header nav ul li a {
    color: white;
    text-decoration: none;
}
header .search-bar input {
    padding: 5px;
    font-size: 16px;
}
.hero {
    text-align: center;
    padding: 100px 20px;
    background-image: url('hero-background.jpg');
    background-size: cover;
    color: orange;
}
.hero h1 {
    font-size: 48px;
    margin-bottom: 20px;
}
.hero p {
    font-size: 24px;
    margin-bottom: 40px;
}
.hero button {
    padding: 10px 20px;
    font-size: 18px;
    background-color: #ff6600;
    color: white;
    border: none;
    cursor: pointer;
}
section {
    padding: 60px 20px;
    text-align: center;
}
section h2 {
    font-size: 36px;
    margin-bottom: 40px;
}
section .grid {
    display: grid;
    gap: 20px;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
}
section .carousel {
    display: flex;
    overflow-x: scroll;
}
section .carousel::-webkit-scrollbar {
    display: none;
}
section .featured-author {
    display: flex;
    flex-direction: column;
    align-items: center;
}
section .testimonials {
    display: flex;
    flex-direction: column;
    align-items: center;
}
section button {
    margin-top: 20px;
    padding: 10px 20px;
    font-size: 18px;
    background-color: #ff6600;
    color: white;
    border: none;
    cursor: pointer;
}
.newsletter {
    background-color: #f0f0f0;
    padding: 60px 20px;
}
.newsletter form {
    display: flex;
    gap: 10px;
    justify-content: center;
    align-items: center;
}
.newsletter form input {
    padding: 10px;
    font-size: 16px;
}
.newsletter form button {
    padding: 10px 20px;
    font-size: 16px;
    background-color: #ff6600;
    color
}
