# Ex.07 Restaurant Website
## Date: 14.5.2025

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
\\\

admin.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MODERN MUSE - Administration</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f4;
            box-sizing: border-box;
        }

        *, *::before, *::after {
            box-sizing: inherit;
        }

        header {
            background: #745105;
            color: rgb(233, 204, 98);
            padding: 15px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 1.8rem;
            font-family: 'Playfair Display', serif;
        }

        header nav a {
            text-decoration: none;
            color: rgb(225, 199, 83);
            font-weight: 500;
            margin: 0 15px;
            transition: color 0.3s ease;
            font-size: 1rem;
        }

        header nav a:hover {
            color: #ff5722;
        }

        .admin-container {
            padding: 40px 20px;
            background: #ffffff;
            text-align: center;
        }

        .admin-container h1 {
            font-size: 2.5rem;
            color: #e2b167;
            margin-bottom: 20px;
            font-family: 'Playfair Display', serif;
        }

        .admin-items {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            justify-content: center;
        }

        .admin-item {
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            width: 280px;
            overflow: hidden;
            transition: transform 0.3s ease;
            text-align: left;
        }

        .admin-item img {
            width: 100%;
            height: 250px;
            object-fit: cover;
        }

        .admin-item:hover {
            transform: scale(1.05);
        }

        .admin-details {
            padding: 15px;
        }

        .admin-details h3 {
            font-size: 1.4rem;
            color: #2c3e50;
            margin-bottom: 8px;
        }

        .admin-details p {
            font-size: 1rem;
            color: #555;
            margin-bottom: 10px;
        }

        footer {
            background: #c3a531;
            color: white;
            text-align: center;
            padding: 15px 0;
        }

        footer a {
            color: #dba419;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s ease;
        }

        footer a:hover {
            color: #ecf0f1;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 1.5rem;
            }

            .admin-items {
                flex-direction: column;
                gap: 20px;
            }

            .admin-item {
                width: 100%;
            }

            header nav a {
                font-size: 0.9rem;
                margin: 0 5px;
            }
        }
    </style>
</head>
<body>    

<header>
        <h1>GLOBALFEAST</h1>
        <nav>
            <a href="restaurant.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="contact.html">Contact</a>
            <a href="admin.html">Administration</a>
        </nav>
    </header>

    <div class="admin-container">
        <h1>Meet Our Leadership Team</h1>
        <div class="admin-items">
            <div class="admin-item">
                <img src="rm ceo.png" alt="CEO">
                <div class="admin-details">
                    <h3>Namjoon</h3>
                    <p>CEO of globalfeast</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="kim v .png" alt="Manager">
                <div class="admin-details">
                    <h3>Taehyung</h3>
                    <p>Manager</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="jk cheif.png" alt="Master Chef">
                <div class="admin-details">
                    <h3>jungkook</h3>
                    <p>Master Chef</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="jm asst.png" alt="Assistant Managing Director">
                <div class="admin-details">
                    <h3>Jimin</h3>
                    <p>Assistant Managing Director</p>
                </div>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 GLOBALFEAST. All rights reserved. | <a href="restaurant.html">Back to Home</a></p>
    </footer>
\\\

</body>
</html>
\\ contact. html 

<html>
    <head>
        <title> CONTACT </title><header>
            <h1>GLOBALFEAST</h1>
            <nav>
                <a href="restaurant.html">Home</a>
                <a href="menu.html">Menu</a>
                <a href="contact.html">Contact</a>
                <a href="admin.html">Administration</a>
            </nav>
            </header>
    </head>
    <style>
        body{
        
            background-image: url("NEW BACKGROUND.png");
            background-size: cover;
            background-position: center;
        }
        body{
            display: inline blocks;
            margin:0 600px;
            font-family:MS Sans Serif;
            text-decoration: none;
            font-size: 23px;
            font-weight: bolder;
            color: rgb(217, 231, 239);
            position:absolute;
            top: 200px;
        }
    </style>
    <center>
        <section id="contact">  
            <h1 style="color:rgb(216, 24, 75)">contact<h1>
            <h4  style="color:rgb(178, 30, 75)">+91 7200674012 <br> |globalfeast@gmail.com</h4>
            <P  style="color:rgb(205, 26, 107)">Address: no.9 nerhu nagar sk road ambur <br>
                Trichy 625620<br> contact us to place the order<br>
            <hr> THE BEST TASTING EXPERIENCE
            </P>
         </section> 
    </center>
    </body>
</html>
\\\ 
menu.html 

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Global feast - Menu</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            color: #df6e27;
            background-color: #f4f4f4;
            box-sizing: border-box;
        }

        *, *::before, *::after {
            box-sizing: inherit;
        }

        header {
            background: #e16a0f;
            color: white;
            padding: 15px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 1.8rem;
            font-family: 'Playfair Display', serif;
        }

        header nav a {
            text-decoration: none;
            color: white;
            font-weight: 500;
            margin: 0 15px;
            transition: color 0.3s ease;
            font-size: 1rem;
        }

        header nav a:hover {
            color: #ff5722;
        }

        .menu-container {
            padding: 40px 20px;
            background: #ffffff;
            text-align: center;
        }

        .menu-container h1 {
            font-size: 2.5rem;
            color: #ee9931;
            margin-bottom: 30px;
            font-family: 'Playfair Display', serif;
        }

        .menu-items {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            justify-content: center;
        }

        .menu-item {
            background: white;
            border-radius: 15px;
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.15);
            width: 280px;
            overflow: hidden;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            text-align: left;
        }

        .menu-item img {
            width: 100%;
            height: 220px;
            object-fit: cover;
            transition: transform 0.3s ease;
        }

        .menu-item:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
        }

        .menu-item:hover img {
            transform: scale(1.1);
        }

        .menu-details {
            padding: 15px;
        }

        .menu-details h3 {
            font-size: 1.4rem;
            color: #ea9228;
            margin-bottom: 10px;
            font-weight: 500;
        }

        .menu-details p {
            font-size: 1rem;
            color: #e6b224;
            margin-bottom: 10px;
        }

        .menu-details .price {
            font-weight: bold;
            font-size: 1.1rem;
            color: #e1bf27;
        }

        footer {
            background: #e38111;
            color: white;
            text-align: center;
            padding: 15px 0;
        }

        footer a {
            color: #ea9125;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s ease;
        }

        footer a:hover {
            color: #ecf0f1;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 1.5rem;
            }

            .menu-items {
                flex-direction: column;
                gap: 20px;
            }

            .menu-item {
                width: 100%;
            }

            header nav a {
                font-size: 0.9rem;
                margin: 0 5px;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>MODERN MUSE</h1>
        <nav>
            <a href="restaurant.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="contact.html">Contact</a>
            <a href="admin.html">Administration</a>
        </nav>
    </header>

    <div class="menu-container">
        <h1>Our Menu</h1>
        <div class="menu-items">
            <div class="menu-item">
                <img src="biryani.jpg" alt="Ambur Briyani">
                <div class="menu-details">
                    <h3>Ambur Briyani</h3>
                    <p class="price">₹280/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="appam.jpg" alt="appam">
                <div class="menu-details">
                    <h3>Appam</h3>
                    <p class="price">₹120/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="browni.jpg" alt="browni">
                <div class="menu-details">
                    <h3>Browni</h3>
                    <p class="price">₹80/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="cake.jpg" alt="cake">
                <div class="menu-details">
                    <h3>cake</h3>
                    <p class="price">₹380/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="cocktail.jpg" alt="cocktail">
                <div class="menu-details">
                    <h3>cocktail</h3>
                    <p class="price">₹250/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="icecream.jpg" alt="ice cream">
                <div class="menu-details">
                    <h3>ICECREAM</h3>
                    <p class="price">₹100/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="idli.jpg" alt="idli">
                <div class="menu-details">
                    <h3>idli</h3>
                    <p class="price">₹100/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="kunafa.jpg" alt="kunafa">
                <div class="menu-details">
                    <h3>kunafa</h3>
                    <p class="price">₹250/-</p>
                </div>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 GLOBAL FEAST. All rights reserved. | <a href="restaurant.html">Back to Home</a></p>
    </footer>

</body>
</html>
\\\
restaurant.html
restaurant,html


<!DOCTYPE html>
<html lang="en"?>
    <head>
        <title>GLOBAL FEAST</title>
        <link rel="icon" href="logo.png">
    </head>
    <style>
        body{
            background-image: url("NEW BACKGROUND.png");
            background-size: cover;
            background-position: center;
        }
        .nav-list{
            position: absolute;
            top: 30px;
            left: 80%;
            transform:  translatex(10%);
        }
        .nav-list a{
            display: inline blocks;
            margin: 0 10px;
            font-family:MS Sans Serif;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            color: white;
        }
        .nav-list a:hover{
            color: rgb(230, 124, 19);
        }
    </style>
        <div class="nav-list">
        <a href="#">Home</a>
        <a href="menu.html">Menu</a>
        <a href="contact.html">contact</a>
        <a href="admin.html">Admin</a>
        </div>
    <body style="color: white;">
        <center>
        <img src="logo.html.png" style="height: 150px;">
        </center>
        <center>
            <h1 style="color:rgb(236, 222, 222); font-size: 50px;">global feast</h1>
        </center>
    <table> 
        <center>
        <tr>
            <td><img src="appam.jpg"" style="width: 300px; height: 250px;"></td>
            <td><img src="biryani.jpg" style="width:300px; height: 250px;"></td>
            <td><img src="browni.jpg" style="width:300px; height: 250px;"></td>
            <td><img src="cake.jpg" style="width:300px; height: 250px;"></td>
            <td><img src="kunafa.jpg" style="width:300px; height: 250px;"></td>
        </tr>
        </center>
        <tr>
            <td><h3 style="color:white;"><center>Appam</center></h3></td>
            <td><h3 style="color:white;"><center>Biriyani</center></h3></td>
            <td><h3 style="color:azure;"><center>Brownie</center></h3></td>
            <td><h3 style="color:azure;"><center>Cake</center></h3></td>
            <td><h3 style="color:azure;"><center>Kunafa</center></h3></td>
        </tr>
    </table>
    <h2>Interior Design:
        <h2><center>Decor:</center></h2>
    </h2>
        <p style="font-family: 'Times New Roman',Times, serif";><center>Warm colors,comfy seating,with beautiful appearance</center>
            Come on down to our new fast food restaurant in the area! indulge in mouth
            watering burgers,crispy fries,juicy chicken,pizza,noodles,fried rice and more! our menu is packed with flavorfuln options that will
            satisfy your hunger cravings ,a limited,standardized menu with items that are quick to prepare and serve.the focus is on convenience,speed and 
            affordability,with little emphasis on nutritional valve ornculinary creativity.fast food is about more than just nutrition 
            Although imposing higher tax on fast food could have some positive effects,these would be overweighted by the drawbacks.

        </p> 
        <hr>
        <tr>
            <td><h4 style="font-size: larger;"><center>The Best Tasting Experience!</center></h4></td>
        </tr>
        <footer align="center" id="copywrite">
            Designed and developed by Praisy Nishitha &copy 2024
        </footer>
    </body>        
</html>




## OUTPUT:
//
![alt text](<Screenshot 2025-05-14 113303.png>)

![alt text](<Screenshot 2025-05-14 113320.png>)

![alt text](<Screenshot 2025-05-14 113341.png>)

![alt text](<Screenshot 2025-05-14 113400.png>)

![alt text](<Screenshot 2025-05-14 113430.png>)

![alt text](<Screenshot 2025-05-14 113502.png>)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
