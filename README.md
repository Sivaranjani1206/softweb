# Ex.06 Restuarant Website
## Date: 25.05.2026

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

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
```
soft.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title> PLUM AND PEARL | Home</title>

  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #eee6ee;
      color: #0a0109;
    }

    header {
      background: #680b65;
      color: rgb(226, 223, 226);
      text-align: center;
      padding: 1rem;
    }

    nav {
      margin-top: 10px;
    }

    nav a {
      color: rgb(223, 205, 218);
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .hero {
      background: url('back.avif');
      color: rgb(3, 0, 3);
      text-align: center;
      padding: 150px 20px;
    }

    .hero h2 {
      font-size: 3em;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 1.2em;
    }

    .btn {
      background: #886d96e8;
      color: #070008;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
      transition: 0.3s;
    }

    .btn:hover {
      background: #eae1eb;
      color: #050005;
    }

    .intro {
      text-align: center;
      padding: 40px;
    }

    .intro img {
      width: 70%;
      max-width: 500px;
      border-radius: 10px;
      margin-top: 20px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }

    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>

<body>
  <!-- Header Section -->
  <header>
    <h1>PLUM AND PEARL🍽️</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="about.html">About</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <h2> HEADING TO PLUM AND PEARL</h2>
    <p>TASTYY FOOD. SMOOTH AND COZY VIBES. AMAZING MOMENTS.</p>
    <a href="menu.html" class="btn">DIVE INTO OUR MENU</a>
  </section>

  <!-- About Preview Section -->
  <section class="intro">
    <h2>WHY DINE WITH US?</h2>
    <p>At Plum And Pearl, we blend the freshest ingredients with a touch of love to give you meals that speak to your soul. Whether you're craving a cheesy pizza, creamy pasta, or a juicy burger, we’ve got you covered!</p>
    <img src="rest.jpg" alt="Restaurant Interior">
  </section>

  <footer>
    <p>© 2026 PLUM AND PEARL | Designed with ❤️ by SIVARANJANI M</p>
  </footer>
</body>
</html>


menu.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menu | PLUM AND PEARL</title>

  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #faf9f8;
      color: #0a0000;
    }

    header {
      background: #4b024b;
      color: white;
      text-align: center;
      padding: 1rem;
    }

    nav {
      margin-top: 10px;
    }

    nav a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    h1 {
      margin: 0;
    }

    .menu {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 25px;
      padding: 40px;
    }

    .dish {
      background: white;
      border-radius: 10px;
      box-shadow: 0 3px 8px rgba(0,0,0,0.1);
      width: 250px;
      text-align: center;
      transition: transform 0.3s ease;
    }

    .dish:hover {
      transform: scale(1.05);
    }

    .dish img {
      width: 100%;
      border-radius: 10px 10px 0 0;
    }

    .dish h3 {
      margin: 10px 0 5px 0;
      color: #46055f;
    }

    .dish p {
      margin: 0 10px 10px;
    }

    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>

<body>
  <!-- Header Section -->
  <header>
    <h1>Our Menu 🍽️</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="about.html">About</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <!-- Menu Section -->
  <section class="menu">
    <div class="dish">
      <img src="pasta.jpg" alt="Pasta">
      <h3>Italian Pasta</h3>
      <p>Rich, creamy, and full of flavor.</p>
    </div>

    <div class="dish">
      <img src="pizza.jpeg" alt="Pizza">
      <h3>Cheese Burst Pizza</h3>
      <p>Melty cheese goodness in every bite.</p>
    </div>

    <div class="dish">
      <img src="burger.jfif" alt="Burger">
      <h3>Classic Burger</h3>
      <p>Juicy patty with fresh veggies.</p>
    </div>

    <div class="dish">
      <img src="noodles.jpg" alt="Noodles">
      <h3>Hakka Noodles</h3>
      <p>Perfectly tossed with veggies and sauces.</p>
    </div>

    <div class="dish">
      <img src="juice.jfif" alt="Juice">
      <h3>Fresh Juices</h3>
      <p>Refreshing fruit blends made fresh.</p>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>Bon Appétit 🍕 | © 2026 PLUM AND PEARL</p>
  </footer>
</body>
</html>


about.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About | PLUM AND PEARL🍽️</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background-color: #f3f0ee;
      color: #0c0101;
      line-height: 1.6;
    }

    header {
      background-color: #4d096d;
      color: white;
      text-align: center;
      padding: 1.5rem 0;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }

    nav {
      background: #2c2c2c;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 1rem;
    }

    nav a {
      text-decoration: none;
      color: white;
      font-weight: bold;
      transition: 0.3s;
    }

    nav a:hover {
      color: #480a72;
    }

    .about-container {
      max-width: 1000px;
      margin: 50px auto;
      text-align: center;
      padding: 20px;
    }

    .about-container h2 {
      font-size: 2.5rem;
      color: #4c035e;
      margin-bottom: 20px;
    }

    .about-container p {
      font-size: 1.1rem;
      margin-bottom: 30px;
      color: #444;
    }

    .team {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
    }

    .member {
      background: white;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      width: 280px;
      padding: 20px;
      transition: 0.3s;
    }

    .member:hover {
      transform: scale(1.05);
    }

    .member img {
      width: 100%;
      height: 220px;
      border-radius: 10px;
      object-fit: cover;
    }

    .member h3 {
      color: #4e025e;
      margin-top: 10px;
    }

    .member p {
      color: #555;
      margin-top: 5px;
    }

    footer {
      background-color: #2c2c2c;
      color: white;
      text-align: center;
      padding: 1rem 0;
      margin-top: 50px;
    }
  </style>
</head>
<body>
  <header>
    <h1>About Us</h1>
  </header>

  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="about.html">About</a>
    <a href="contact.html">Contact</a>
  </nav>

  <section class="about-container">
    <h2>WELCOME TO PLUM AND PEARL!🍽️</h2>
    <p>Founded in 2018, <b>Plum and Pearl</b> is a cozy place where every dish tells a story. 
      From sizzling grills to creamy pastas, our chefs bring passion and creativity to every plate.  
      We blend local flavors with global cuisines to give you an unforgettable dining experience — served with warmth and a smile. 😋
    </p>

    <h2>Meet Our Team mates👨‍🍳</h2>
    <div class="team">
      <div class="member">
        <img src="ceo.jpeg" alt="CEO">
        <h3>CEO</h3>
        <p>Sparkling Sivaranjani</p>
      </div>

      <div class="member">
        <img src="person1.jpg" alt="Manager">
        <h3>Manager</h3>
        <p>Vibrant Vijay</p>
      </div>

      <div class="member">
        <img src="person2.jpg" alt="Assistant Manager">
        <h3>Assistant Manager</h3>
        <p>Scintillating Surya</p>
      </div>

      <div class="member">
        <img src="person4.jpg" alt="Chef">
        <h3>Chef Divya</h3>
        <p>Dessert Queen</p>
      </div>

      <div class="member">
        <img src="person5.jpg" alt="Chef">
        <h3>Chef Sree Leela</h3>
        <p>Spicy food and grill expert</p>
      </div>
    </div>
  </section>

  <footer>
    <p>© 2026 Plum And Pearl | Crafted with ❤️</p>
  </footer>
</body>
</html>


contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us | Plum And Pearl</title>
    <style>
        body {
            margin: 0;
            font-family: 'Poppins', sans-serif;
            background-color: #faf7f4;
            color: #130101;
        }

        header {
            background-color: #55055f;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav a {
            text-decoration: none;
            color: white;
            margin: 0 15px;
            font-weight: 500;
        }

        nav a:hover, .active {
            text-decoration: underline;
        }

        .contact-section {
            background: url('backg.jfif');
            padding: 50px;
            text-align: center;
        }

        .contact-container {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin-top: 30px;
        }

        form {
            background-color: #fff;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            width: 300px;
            text-align: left;
        }

        form input, form textarea {
            width: 100%;
            padding: 10px;
            margin-top: 8px;
            margin-bottom: 15px;
            border-radius: 8px;
            border: 1px solid #ccc;
            font-size: 14px;
        }

        button {
            background-color: #44033f;
            color: white;
            border: none;
            padding: 12px 20px;
            border-radius: 8px;
            cursor: pointer;
            width: 100%;
        }

        button:hover {
            background-color: #48044b;
        }

        .contact-info {
            background-color: #fff;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            width: 300px;
            text-align: left;
        }

        footer {
            background-color: #49053e;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 50px;
        }

        iframe {
            margin-top: 25px;
            border-radius: 12px;
            width: 90%;
            max-width: 600px;
            height: 300px;
            border: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Flavours & Feast</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="about.html">About</a>
            <a href="contact.html" class="active">Contact</a>
        </nav>
    </header>

    <section class="contact-section">
        <h2>Contact Us</h2>
        <p>We’d love to hear from you! Whether you have a question, feedback, or just wanna say hi, drop us a message below 🍴💬</p>
        <div class="contact-container">
            <form>
                <label>Name:</label>
                <input type="text" placeholder="Your Name" required>

                <label>Email:</label>
                <input type="email" placeholder="Your Email" required>

                <label>Message:</label>
                <textarea placeholder="Type your message here..." required></textarea>

                <button type="submit">Send Message</button>
            </form>

            <div class="contact-info">
                <h3>Reach Us At</h3>
                <p><strong>📍 Address:</strong> No. 66, Taj nagar, Chennai, Tamil Nadu</p>
                <p><strong>📞 Phone:</strong> +91 98647 86543</p>
                <p><strong>✉️ Email:</strong> contact@plumandpearl.com</p>
                <p><strong>🕒 Open Hours:</strong> Mon - Sun | 09 AM - 10 PM</p>
            </div>
        </div>

        
    </section>

    <footer>
        <p>© 2026 Plum And Pearl. All rights reserved.</p>
    </footer>
</body>
</html>
```

## OUTPUT:
![alt text](Screenshot (210).png)
![alt text](Screenshot (211).png)
![alt text](Screenshot (212).png)
![alt text](Screenshot (213).png)
![alt text](Screenshot (214).png)
![alt text](Screenshot (215).png)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
