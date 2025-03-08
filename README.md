# OCTANET_MARCH

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jain Traders - Plastic & Farming Materials</title>
    <link rel="stylesheet" href="style2.css">
</head>
<body>
    <header class="header">
        <div class="overlay">
            <h1>Jain Traders</h1>
            <h3><p>Your one-stop shop for plastic household & farming materials</p></h3>
            <nav>
                <a href="#about">About Us</a>
                <a href="#products">Products</a>
                <a href="#contact">Contact</a>
            </nav>
        </div>
    </header>

    <section id="about" class="about">
        <h2>About Us</h2>
        <p>Jain Traders, located in Satana, Nashik, is a trusted provider of high-quality plastic household items and farming-related products.</p>
    </section>

    <section id="products" class="products">
        <h2>Our Products</h2>
        <div class="product-grid">
            <div class="product">
                
                <h3>Plastic Buckets</h3>
            </div>
            <div class="product">
                
                <h3>Storage Containers</h3>
            </div>
            <div class="product">
                
                <h3>Farming Pipes</h3>
            </div>
            <div class="product">
               
                <h3>Plastic Chairs</h3>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>📍 Location: Sudarshan Nagar,Pimpri-Chinchwad Dist:Pune</p>
        <p>📞 Phone: +91 XXXXXXXXXX</p>
        <p>📧 Email: info@jaintraders.com</p>
    </section>

    <footer class="footer">
        <p>&copy; 2025 Jain Traders. All rights reserved.</p>
    </footer>
</body>
</html>






* {
    
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body {
    background-color: #f5f5f5;
    color: #333;
}


.header {
    width: 100%;
    height: 60vh;
    background-size: cover;
    background-position: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    position: relative;
}


.overlay {
    width:75%;
    min-height:70vh;
    padding: 20px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    color: black;
    
    background-image: url('https://www.printasia.in/media/catalog/product/b/-/b-h-7_plastic_shop_.jpg');
    background-size: cover;
    background-position: center;
   
}


.header h1 {
    font-size: 3rem;
    background: rgba(255, 255, 255, 0.6);
    padding: 10px 20px;
    border-radius: 10px;
}

.header p {
    font-size: 1.2rem;
    margin-top: 10px;
    background: rgba(255, 255, 255, 0.6);
    padding: 5px 10px;
    border-radius: 5px;
}


nav {
    margin-top: 20px;
}

nav a {
    color: black;
    background-color: white;
    padding: 10px 15px;
    border-radius: 5px;
    text-decoration: none;
    margin: 0 10px;
    font-size: 1.1rem;
    font-weight: bold;
    display: inline-block;
    transition: 0.3s ease-in-out;
}


nav a:hover {
    background-color:red;
    color: black;
}


.about, .products, .contact {
    text-align: center;
    padding: 40px 20px;
}
.about{
    padding:100px;;
}
.products h2, .about h2, .contact h2 {
    margin-bottom: 20px;
}


.product-grid {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 20px;
}

.product {
    background: white;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    text-align: center;
    width: 250px;
    height: 300px;
    display: flex;
    flex-direction: column;
    justify-content: end;
    position: relative;
    transition: 0.3s ease-in-out;
}


.product:nth-child(1) {
    background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTB3UJcOzAW5KwC1qrrKPZ-f2NLe5OjRwmgXA&s');
    background-size: cover;
    background-position: center;
}

.product:nth-child(2) {
    background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRUC6N3yRBcF2dl6VBVPcLi7WwvyAg6o9ut9w&s');
    background-size: cover;
    background-position: center;
}

.product:nth-child(3) {
    background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQiCojNvJu5NjbwM7gQtYpQKUBvDKdonAkaXA&s');
    background-size: cover;
    background-position: center;
}

.product:nth-child(4) {
    background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT--1N8bvZccXjXxQ0jUMfG2EnD87msDrdRWw&s');
    background-size: cover;
    background-position: center;
}


.product h3 {
    margin-top: 10px;
    font-size: 1.2rem;
    background: rgba(255, 255, 255, 0.7);
    padding: 5px 10px;
    border-radius: 5px;
}


.product:hover {
    transform: scale(1.05);
    box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.3);
}

.contact {
    background: #333;
    color: white;
    padding: 30px;
}

.footer {
    text-align: center;
    background: black;
    color: white;
    padding: 10px;
    margin-top: 20px;
}
