# Ex.07 Restaurant Website
## Date:05/10/2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
'''
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Delicious Bites Restaurant</title>
<style>
    body { font-family: Arial, sans-serif; margin:0; padding:0; line-height:1.6; }
    header { background:#ff6347; color:white; padding:20px 0; text-align:center; }
    header nav a { color:white; margin:0 15px; text-decoration:none; font-weight:bold; }
    header nav a:hover { text-decoration:underline; }
    section { padding:50px 20px; text-align:center; }
    .food-items { display:flex; justify-content:center; gap:20px; flex-wrap:wrap; margin-top:20px; }
    .food-item { border:1px solid #ddd; padding:10px; width:200px; border-radius:10px; }
    .food-item img { width:100%; border-radius:10px; }
    ul { list-style:none; padding:0; }
    ul li { margin:10px 0; }
    footer { background:#333; color:white; text-align:center; padding:15px 0; }
</style>
</head>
<body>

<header>
    <h1>Delicious Bites</h1>
    <nav>
        <a href="#home">Home</a>
        <a href="#menu">Menu</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section id="home">
    <h2>Welcome to Delicious Bites!</h2>
    <p>Experience the best taste of our freshly prepared meals.</p>
</section>

<section id="menu">
    <h2>Our Menu</h2>
    <div class="food-items">
        <div class="food-item">
            <img src="https://via.placeholder.com/150" alt="Pizza">
            <h3>Pizza</h3>
            <p>Cheesy and delicious pizza with fresh toppings.</p>
        </div>
        <div class="food-item">
            <img src="https://via.placeholder.com/150" alt="Burger">
            <h3>Burger</h3>
            <p>Juicy burgers made with premium ingredients.</p>
        </div>
        <div class="food-item">
            <img src="https://via.placeholder.com/150" alt="Pasta">
            <h3>Pasta</h3>
            <p>Italian-style pasta cooked to perfection.</p>
        </div>
    </div>
</section>

<section id="services">
    <h2>Our Services</h2>
    <ul>
        <li>Dine-in with cozy ambiance</li>
        <li>Home delivery service</li>
        <li>Online table reservation</li>
        <li>Catering for events and parties</li>
    </ul>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <p>Email: info@deliciousbites.com</p>
    <p>Phone: +123 456 7890</p>
    <p>Address: 123 Food Street, Gourmet City</p>
</section>

<footer>
    <p>&copy; 2025 Delicious Bites Restaurant. All rights reserved.</p>
</footer>

</body>
</html>

'''

## OUTPUT:
![alt text](<Screenshot 2025-10-11 142624.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
