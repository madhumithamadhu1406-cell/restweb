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
<html>
<head>
  <title>MNM RESTAURANT'S</title>
  <style>
    body { 
      background-color: rgb(144, 75, 77); 
      font-family: Arial, sans-serif; 
      text-align: center; 
      margin: 0;
      padding: 0;
    }

    nav a { 
      margin: 10px; 
      text-decoration: none; 
      color: rgb(93, 56, 56); 
      background-color: rgb(247, 249, 250); 
      padding: 5px 10px; 
      border-radius: 5px; 
    }

    .banner-container {
  position: relative;
  width: 100%;
  max-width: 2000px;
  margin: 20px auto;
  display: flex;         
  justify-content: center; 
}

.banner-container img {
  width: 50%;
  height: 600px; 
  border-radius: 10px;
  display: block;
}
    .banner-text {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      color: white;
      font-size: 40px;
      font-weight: bold;
      text-align: center;
      background: rgba(0, 0, 0, 0.5);
      padding: 20px 40px;
      border-radius: 10px;
    }
  </style>
</head>
<body>

  <h1>MNM RESTAURANT'S</h1>

  <nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact</a>
  </nav>

  <div class="banner-container">
    <img src="img1.jpg" alt="Restaurant Banner">
  </div>

  <h3>Our Restaurant Specials</h3>
  <p>Try our Indian dishes and desserts!</p>

  <h3>Welcome To Our MNM RESTAURANT's</h3>
</body>
</html>


admin.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MNM Restaurant'S Administration</title>
<style>
    body {
        font-family: Arial, sans-serif;
        background-color: #ad3333;
        margin: 0;
        padding: 0;
        text-align: center;
    }

    h1 {
        background-color: #ad2a35;
        color: white;
        padding: 20px 0;
        margin: 0;
    }

    nav {
        margin: 20px 0;
    }

    nav a {
        text-decoration: none;
        color: rgb(158, 47, 47);
        background-color: #f2ecec;
        padding: 10px 15px;
        border-radius: 5px;
        margin: 0 5px;
    }

    .gallery {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 20px;
        padding: 20px;
    }

    .gallery-item {
        flex: 1 1 45%; 
        max-width: 45%;
        height: 200px;
        overflow: hidden;
        border-radius: 10px;
        box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }

    .gallery-item img {
        width: 50%;
        height: 50%;
        object-fit: cover;
        transition: transform 0.3s ease;
    }

    .gallery-item img:hover {
        transform: scale(1.1);
    }

    @media (max-width: 600px) {
        .gallery-item {
            flex: 1 1 100%; 
            max-width: 100%;
        }
    }

    footer {
        margin-top: 30px;
        padding: 15px;
        background-color: #ad3434;
        color: white;
    }
</style>
</head>
<body>

    <h1>MNM RESTAURANT'S ADMINISTRATION</h1>

    <nav>
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="admin.html">Administration</a>
        <a href="contact.html">Contact</a>
    </nav>

    <h2>OUR ADMINISTRATORS</h2>
    

    <div class="gallery">
        <div><img src="photo4.jpg" alt="FOUNDER"></div>
        <div><img src="image1.png" alt="CO-FOUNDER"></div>
        <div><img src="image2.png" alt="SERVER 1"></div>
        <div><img src="image3.png"SERVER 2"></div>
        <div><img src="image4.jpg" alt="CHEF 1"></div>
    </div>

    <footer>
        <p>Designed by Madhumitha V(25016067)</p>
    </footer>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OUR Restaurant Menu</title>
<style>
    body {
        font-family: Arial, sans-serif;
        background-color: #2e1b0f;
        color: #fff;
        margin: 0;
        padding: 0;
    }

    nav a { 
      margin: 8px; 
      text-decoration: none; 
      color: rgb(93, 56, 56); 
      background-color: rgb(247, 249, 250); 
      padding: 6px 12px; 
      border-radius: 8px; 
    }

    .menu-container {
        max-width: 1000px;
        margin: 50px auto;
        padding: 10px;
        background-color: #a16b4a;
        text-align: center;
    }

    h1 {
        font-size: 2.5em;
        margin-bottom: 40px;
    }

    .menu-section {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-around;
        gap: 20px; 
        margin-bottom: 40px;
        margin-top: 1cm;
    }
    
    .menu-item {
        flex: 1 1 200px; 
        max-width: 220px; 
        display: flex;
        align-items: center;
        background-color: #774c36;
        padding: 10px;
        border-radius: 10px;
    }

    .menu-item img {
        width: 80px;
        height: 80px;
        object-fit: cover;
        border-radius: 50%;
        margin-right: 15px;
    }

    .menu-item div {
        flex: 1;
        text-align: left;
    }

    .menu-item span {
        float: right;
        font-weight: bold;
    }

    @media (max-width: 800px) {
        .menu-item {
            flex: 1 1 45%;
            max-width: none;
        }
    }

    @media (max-width: 500px) {
        .menu-item {
            flex: 1 1 100%;
        }
    }

    .website-link {
        margin-top: 30px;
        font-weight: bold;
        color: #f5d042;
        text-decoration: none;
        display: inline-block;
    }
</style>
</head>
<body>

    <div class="menu-container">
        <h1>OUR RESTAURANT MENU</h1>

        <nav>
            <a href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Administration</a>
            <a href="contact.html">Contact</a>
        </nav>

        <div class="menu-section">
            <div class="menu-item">
                <img src="item1.png" alt="mutton" >
                <div>mutton</div>
            </div>
            <div class="menu-item">
                <img src="item2.png" alt="chicken gravy">
                <div>chicken gravy</div>
            </div>
            <div class="menu-item">
                <img src="item3.png" alt="fish biriyani">
                <div>fish biriyani</div>
            </div>
            <div class="menu-item">
                <img src="item4.png" alt="tandoori" >
                <div>tandoori</div>
            </div>
            <div class="menu-item">
                <img src="item5.png" alt="mutton chuka" >
                <div>mutton chuka</div>
            </div>
        </div>

        <a href=" " class="website-link">WWW.MNM RESTAURANT'S.COM</a>
    </div>
</body>
</html>


contact.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>MNM Restaurant - Contact Us</title>
<style>
    body {
        font-family: Arial, sans-serif;
        background-color: #ad2929;
        margin: 0;
        padding: 0;
        text-align: center;
    }

    h1 {
        background-color: #ad2222;
        color: white;
        padding: 20px 0;
        margin: 0;
    }

    nav {
        margin: 20px 0;
    }

    nav a {
        text-decoration: none;
        color: rgb(158, 35, 35);
        background-color: #f2f5f8;
        padding: 10px 15px;
        border-radius: 5px;
        margin: 0 5px;
    }

    .contact-container {
        max-width: 600px;
        margin: 30px auto;
        background-color: #fff;
        padding: 30px;
        border-radius: 10px;
        box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        text-align: left;
    }

    .contact-container h2 {
        text-align: center;
        color: #333;
    }

    label {
        display: block;
        margin-top: 15px;
        font-weight: bold;
    }

    input, textarea {
        width: 100%;
        padding: 10px;
        margin-top: 5px;
        border-radius: 5px;
        border: 1px solid #ccc;
        box-sizing: border-box;
    }

    textarea {
        resize: vertical;
        height: 120px;
    }

    button {
        background-color: #ad2828;
        color: white;
        padding: 12px 25px;
        margin-top: 20px;
        border: none;
        border-radius: 5px;
        cursor: pointer;
        font-size: 16px;
    }

    button:hover {
        background-color: #ad1818;
    }

    footer {
        margin-top: 30px;
        padding: 15px;
        background-color: #ad2121;
        color: white;
        text-align: center;
    }

</style>
</head>
<body>

<h1>MNM RESTAURANT'S</h1>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact</a>
</nav>

<div class="contact-container">
    <h2>Contact Us</h2>
    <p>We would love to hear from you! Please fill out the form below:</p>

    <form action="#" method="post">
        <label for="name">Name</label>
        <input type="text" id="name" name="name" placeholder="Your Name" required>

        <label for="email">Email</label>
        <input type="email" id="email" name="email" placeholder="Your Email" required>

        <label for="phone">Phone</label>
        <input type="tel" id="phone" name="phone" placeholder="Your Phone Number">

        <label for="message">Message</label>
        <textarea id="message" name="message" placeholder="Write your message here..." required></textarea>

        <button type="submit">Send Message</button>
    </form>
</div>

<footer>
    <p>Designed by Madhumitha V(25016067)</p>
</footer>

</body>
</html>

```


## OUTPUT:

![alt text](<Screenshot (44).png>)
![alt text](<Screenshot (45).png>)
![alt text](<Screenshot (46).png>)
![alt text](<Screenshot (47).png>)





## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
