<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Online Store</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <nav>
      <h1>My Online Store</h1>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Products</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section class="products">
      <div class="product">
        <img src="product1.jpg" alt="Product 1">
        <h2>Product 1</h2>
        <p>$20.00</p>
        <button>Buy Now</button>
      </div>
      <div class="product">
        <img src="product2.jpg" alt="Product 2">
        <h2>Product 2</h2>
        <p>$30.00</p>
        <button>Buy N/button>
      </div>n
    </section>
  </main>

  <footer>
    <p>&copy; 2024 My Online Store</p>
  </footer>
</body>
</html> # Semary.comb
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
}

header {
  background: #333;
  color: #fff;
  padding: 10px 20px;
}

header nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

header nav ul {
  list-style: none;
  display: flex;
}

header nav ul li {
  margin-left: 15px;
}

header nav ul li a {
  color: #fff;
  text-decoration: none;
}

.products {
  display: flex;
  justify-content: space-around;
  padding: 20px;
}

.product {
  text-align: center;
  border: 1px solid #ccc;
  padding: 10px;
  width: 200px;
}

.product img {
  max-width: 100%;
}

button {
  background: #007BFF;
  color: #fff;
  border: none;
  padding: 10px;
  cursor: pointer;
}

button:hover {
  background: #0056b3;
}

footer {
  text-align: center;
  padding: 10px;
  background: #333;
  color: #fff;
  margin-top: 20px;
}
