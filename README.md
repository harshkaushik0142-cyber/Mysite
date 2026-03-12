<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>JPS Sports | Badminton Store</title>

<style>

body{
margin:0;
font-family:Arial, Helvetica, sans-serif;
background:#f4f4f4;
}

header{
background:#0a1f44;
color:white;
padding:15px;
display:flex;
justify-content:space-between;
align-items:center;
}

header h1{
margin:0;
font-size:26px;
}

nav a{
color:white;
text-decoration:none;
margin:0 15px;
font-weight:bold;
}

.hero{
background:url("https://images.unsplash.com/photo-1599058917765-a780eda07a3e") center/cover;
height:400px;
display:flex;
align-items:center;
justify-content:center;
color:white;
text-align:center;
}

.hero h2{
font-size:40px;
background:rgba(0,0,0,0.5);
padding:15px;
border-radius:10px;
}

.section{
padding:40px;
text-align:center;
}

.categories{
display:flex;
justify-content:center;
flex-wrap:wrap;
gap:20px;
}

.card{
background:white;
padding:20px;
border-radius:10px;
box-shadow:0 5px 10px rgba(0,0,0,0.1);
width:200px;
}

.card img{
width:100%;
border-radius:10px;
}

.products{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:25px;
}

.product{
background:white;
padding:15px;
width:220px;
border-radius:10px;
box-shadow:0 5px 10px rgba(0,0,0,0.1);
}

.product img{
width:100%;
}

.price{
color:#e63946;
font-weight:bold;
}

button{
background:#0a1f44;
color:white;
border:none;
padding:10px 15px;
border-radius:5px;
cursor:pointer;
}

footer{
background:#0a1f44;
color:white;
text-align:center;
padding:20px;
margin-top:40px;
}

</style>
</head>

<body>

<header>
<h1>JPS Sports</h1>
<nav>
<a href="#">Home</a>
<a href="#categories">Categories</a>
<a href="#products">Products</a>
<a href="#about">About</a>
<a href="#contact">Contact</a>
</nav>
</header>

<section class="hero">
<h2>Your Badminton Store 🏸</h2>
</section>

<section id="categories" class="section">
<h2>Shop by Category</h2>

<div class="categories">

<div class="card">
<img src="https://images.unsplash.com/photo-1626224583764-5f7e1b5d8f9e">
<h3>Rackets</h3>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1616628188858-2c07b44ef246">
<h3>Shuttlecocks</h3>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1600185365483-26d7a4cc7519">
<h3>Badminton Shoes</h3>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1589187155479-3c5e6b7a3e02">
<h3>Apparel</h3>
</div>

</div>
</section>

<section id="products" class="section">
<h2>Featured Products</h2>

<div class="products">

<div class="product">
<img src="https://images.unsplash.com/photo-1611486212557-88be5ff6f941">
<h4>Carbon Pro Racket</h4>
<p class="price">₹1,799</p>
<button>Add to Cart</button>
</div>

<div class="product">
<img src="https://images.unsplash.com/photo-1580795479225-c50ab8c3348d">
<h4>Feather Shuttlecock</h4>
<p class="price">₹499</p>
<button>Add to Cart</button>
</div>

<div class="product">
<img src="https://images.unsplash.com/photo-1521417531039-0a5f33e6ef8b">
<h4>Badminton T-Shirt</h4>
<p class="price">₹699</p>
<button>Add to Cart</button>
</div>

</div>

</section>

<section id="about" class="section">
<h2>About JPS Sports</h2>
<p>
JPS Sports is your trusted badminton store for rackets, shuttlecocks,
shoes and professional badminton gear. We provide high quality products
for beginners and professional players.
</p>
</section>

<section id="contact" class="section">
<h2>Contact Us</h2>
<p>Email: jpssports@gmail.com</p>
<p>Instagram: @jpssportsnbd</p>
</section>

<footer>
<p>© 2026 JPS Sports | All Rights Reserved</p>
</footer>

</body>
</html># Mysite
