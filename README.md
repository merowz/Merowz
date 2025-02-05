## Hi there 👋<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Merowz</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>MEROWZ</h1>
        <nav>
            <a href="#">Home</a>
            <a href="#">Shop</a>
            <a href="#">About</a>
            <a href="#">Contact</a>
        </nav>
    </header>

    <section class="hero">
        <h2>Luxury Clown Fashion</h2>
        <p>Elevate your circus style with elegance</p>
        <button>Shop Now</button>
    </section>

    <section class="products">
        <div class="product">
            <img src="clown1.jpg" alt="Clown Suit">
            <h3>Elegant Clown Suit</h3>
            <p>$99.99</p>
        </div>
        <div class="product">
            <img src="clown2.jpg" alt="Rainbow Shoes">
            <h3>Rainbow Shoes</h3>
            <p>$49.99</p>
        </div>
        <div class="product">
            <img src="clown3.jpg" alt="Red Nose">
            <h3>Classic Red Nose</h3>
            <p>$9.99</p>
        </div>
    </section>

    <footer>
        <p>© 2025 Clown Zara. All rights reserved.</p>
    </footer>
</body>
</html>body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
}

header {
    background: black;
    color: white;
    padding: 20px;
}

nav a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
    font-weight: bold;
}

.hero {
    background: url('clown-background.jpg') no-repeat center center/cover;
    color: white;
    padding: 100px 20px;
}

.hero h2 {
    font-size: 3em;
}

.hero button {
    background: red;
    color: white;
    padding: 10px 20px;
    border: none;
    font-size: 1.2em;
    cursor: pointer;
}

.products {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    padding: 20px;
}

.product {
    margin: 15px;
    text-align: center;
}

.product img {
    width: 200px;
    height: 250px;
    object-fit: cover;
}

footer {
    background: black;
    color: white;
    padding: 10px;
}

<!--
**merowz/Merowz** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
