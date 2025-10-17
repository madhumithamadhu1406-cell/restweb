# Ex.07 Restaurant Website
## Date:17-10-2025

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
```

home.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>MADHU RESTAURANT</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: lightcoral;
            color:black;
        }
        header {
            background-color: lightblue;
            color: white;
            padding: 20px 0;
            text-align: center;
            font-size: 2em;
            font-weight: bold;
        }
        nav {
            background-color:lightpink;
            display: flex;
            justify-content: center;
            gap: 30px;
            padding: 12px 0;
        }
        nav a {
            color: rgb(232, 5, 5);
            text-decoration: none;
            font-weight: 600;
            font-size: 1.1em;
        }
        nav a:hover {
            text-decoration: underline;
        }
                .menu {
            padding: 40px 20px;
            max-width: 900px;
            margin: 0 auto;
        }
        .menu h2 {
            text-align: center;
            color: #83624c;
            margin-bottom: 30px;
            font-size: 2em;
        }
        .menu-items {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 30px;
        }
        .menu-item {
            background-color: #81664c;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            padding: 20px;
            width: 250px;
            text-align: center;
        }
        .menu-item img {
            width: 100%;
            border-radius: 6px;
            margin-bottom: 10px;
        }
        .menu-item h3 {
            margin-bottom: 8px;
            color: #201813;
        }
        .menu-item p {
            font-size: 1em;
            color: #5a2e00;
        }
        footer {
            background-color: #8e2929;
            color: white;
            text-align: center;
            padding: 18px 10px;
            margin-top: 40px;
        }
    </style>    

</head>
<body>
<header>
  <h1>MADHU RESTAURANT</h1>
  <nav>
    <a href="home.html">Home</a>
    <a href="about.html">About</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="booking.html">Book Table</a>
  </nav>
</header>
 <section id="About" class="About">
        <h1>Welcome to madhu Restaurant</h1>
        <p>our staffs</p>
        </section>
 <img src="photo4.jpg"height="200",width="200"style>
<img src="image1.png"height="200",width="200"style>
 <img src="image2.png"height="200",width="200"style>
 <img src="image3.png"height="200",width="200"style>
 <img src="image4.jpg"height="200",width="200"style>

 <footer>

  <p>© 2025 Designed By MADHUMITHA</p>
</footer>
</body>
</html>

admin.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Admin Dashboard</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
<header>
  <h1>Admin Dashboard</h1>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="admin.html">Logout</a>
  </nav>
</header>

<section class="dashboard">
  <h2>Available Dishes</h2>
  <ul>
    <li>chicken rice</li>
    <li>chicken noodles</li>
    <li>meals</li> </li>
    <li>parotta</li>
    <li>Chicken Biryani</li>
    <li>idly</li>
    <li>fish</li>
    <li>panipoori</li>
    <li>chicken barbeque</li>
    <li>sandwich</li>
    <li>butter chicken</li>
    <li>chickenwing</li>
,  </ul>

  <h2>Add New Dish</h2>
  <form>
    <input type="text" placeholder="Dish Name">
    <input type="text" placeholder="Price">
    <button type="submit">Add Dish</button>
  </form>

  <h2>Employees on Shift</h2>
  <ul>
    <li>MUGIL- Chef</li>
    <li>KANI - Waitress</li>
    <li>ARASI - Manager</li>
  </ul>
</section>

<footer>
  <p>© 2025 MADHU Restaurant</p>
</footer>
</body>
</html>

booking.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>MADHU RESTAURANT - Book table </title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: pink;
      color: #291515;
    }
    header {
      background-color:greenyellow;
      color: black;
      padding: 20px 0;
      text-align: center;
      font-size: 2em;
      font-weight: bold;
    }
    nav {
      background-color: skyblue;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 12px 0;
    }
    nav a {
      color: black;
      text-decoration: none;
      font-weight: 600;
      font-size: 1.1em;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .booking-form {
      max-width: 600px;
      margin: 40px auto;
      background-color: cyan;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    .booking-form h2 {
      text-align: center;
      color: black;
      margin-bottom: 25px;
      font-size: 2em;
    }
    .booking-form label {
      display: block;
      margin-bottom: 8px;
      font-weight: 600;
    }
    .booking-form input, 
    .booking-form select, 
    .booking-form textarea {
      width: 100%;
      padding: 5px;
      margin-bottom: 10px;
      border-radius: 6px;
      border: 1px solid #ccc;
      font-size: 1em;
    }
    .booking-form button {
      background-color: white;
      color: white;
      padding: 12px 20px;
      border: none;
      border-radius: 6px;
      font-size: 1.1em;
      cursor: pointer;
      width: 100%;
    }
    .booking-form button:hover {
      background-color: black;
    }
    footer {
      background-color: yellowgreen;
      color: black;
      text-align: center;
      padding: 12px 10px;
      margin-top: 5px;
    }
  </style>
</head>
<body>
  <header>
    MADHU RESTAURANT
    <nav>
      <a href="home.html">Home</a>
      <a href="about.html">About</a>
      <a href="menu.html">Menu</a>
      <a href="contact.html">Contact</a>
      <a href="booking.html">Book Table</a>
    </nav>
  </header>

  <section class="booking-form">
    <h2>Book a Table</h2>
    <form action="#" method="POST">
      <label for="name">Full Name</label>
      <input type="text" id="name" name="name" placeholder="Your name" required>

      <label for="email">Email</label>
      <input type="email" id="email" name="email" placeholder="Your Email" required>

      <label for="phone">Phone Number</label>
      <input type="tel" id="phone" name="phone" placeholder="Your Phone Number" required>

      <label for="guests">Number of Guests</label>
      <input type="number" id="guests" name="guests" min="1" placeholder="Number of Guests" required>

      <label for="date">Date</label>
      <input type="date" id="date" name="date" required>

      <label for="time">Time</label>
      <input type="time" id="time" name="time" required>

      <button type="submit">Book Now</button>
    </form>
  </section>

  <footer>
    <p>© 2025 Designed By MADHUMITHA V</p>
  </footer>
</body>
</html>

menu.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title> MADHU RESTAURANT</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #fff8f0;
            color: #291515;
        }
        header {
            background-color: #8d5f5f;
            color: white;
            padding: 20px 0;
            text-align: center;
            font-size: 2em;
            font-weight: bold;
        }
        nav {
            background-color: #625b40;
            display: flex;
            justify-content: center;
            gap: 30px;
            padding: 12px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-weight: 600;
            font-size: 1.1em;
        }
        nav a:hover {
            text-decoration: underline;
        }
                .menu {
            padding: 40px 20px;
            max-width: 900px;
            margin: 0 auto;
        }
        .menu h2 {
            text-align: center;
            color: #83624c;
            margin-bottom: 30px;
            font-size: 2em;
        }
        .menu-items {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 30px;
        }
        .menu-item {
            background-color: lightseagreen;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            padding: 20px;
            width: 250px;
            text-align: center;
        }
        .menu-item img {
            width: 100%;
            border-radius: 6px;
            margin-bottom: 10px;
        }
        .menu-item h3 {
            margin-bottom: 8px;
            color: #201813;
        }
        .menu-item p {
            font-size: 1em;
            color: #5a2e00;
        }
        footer {
            background-color: lightcoral;
            color: white;
            text-align: center;
            padding: 18px 10px;
            margin-top: 40px;
        }
    </style>    

</head>
<body>
<header>
  <h1>MADHU RESTAURANT</h1>
  <nav>
    <a href="home.html">Home</a>
    <a href="about.html">About</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="booking.html">Book Table</a>
  </nav>
</header>
 <section id="Menu" class="Menu">
        <h1>WELCOME TO MADHU RESTAURANT</h1>
        <p>Experience the best flavors of traditional and modern cuisine in our restaurant.</p>
    </section>
 <img src="item1.png"height="150",width="150"style>
<img src="item2.png"height="150",width="150"style>
 <img src="item3.png"height="150",width="150"style>
 <img src="item4.png"height="150",width="150"style>
 <img src="item5.png"height="150",width="150"style>


 <footer>

  <p>© 2025 Designed By MADHUMITHA V</p>
</footer>
</body>
</html>

contact.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Restaurant - Contact</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
<header>
  <h1>MADHU Restaurant</h1>
  <nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="admin.html">Administration</a>
  </nav>
</header>

<section class="contact">
  <h2>Contact Us</h2>
  <p>📍 no.8,ANNA NAGAR,VELLORE</p>
  <p>📞 +91 987655780</p>
  <p>📧 EMAIL : madhu2006@gmail.com</p>
</section>

<footer>
  <p>© 2025 MADHU Restaurant</p>
</footer>
</body>
</html>

```


## OUTPUT:
![alt text](<Screenshot 2025-10-17 213116.png>)
![alt text](<Screenshot 2025-10-17 213132.png>)
![alt text](<Screenshot 2025-10-17 213147.png>)
![alt text](<Screenshot 2025-10-17 213207.png>)
![alt text](<Screenshot 2025-10-17 213236.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
