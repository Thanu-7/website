# Ex.07 Restaurant Website
# Date:
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
## Home Page
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CURNCHY MUNCHY</title>
    <link rel="stylesheet" href="style.css">
</head>
<body >
    <header class="banner">
        <h1>Welcome to CURNCHY MUNCHY </h1>
        <nav>
            <ul>
                <li><a href="res.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
                <li><a href="booktable.html">Reserve a table!</a></li>
            </ul>
        </nav>
    </header>

    <section class="intro">
        <h2>Life is short, make it delicious.</h2>
        <p>Hundreds of flavors under one roof.</p>
        <p>A taste you'll remember.</p>
    </section>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <footer>
        <p>© Thanushree Vijayakanth - 24900679</p>
    </footer>
</body>
</html>
```

## Css Styling
```
body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
    background-image:url(/Users/admin/Desktop/resimg/background.jpg); /* Replace with your image file path */
    background-size:auto; /* Ensures the image covers the entire screen */
    background-position: center; /* Centers the image */
    background-repeat: repeat;
    ba
}

/* Header Styling */
header.banner {
    background-color: sienna;
    color: white;
    padding: 20px 10px;
    text-align: center;
}

header.banner h1 {
    margin: 0;
    font-size: 2.5em;
    letter-spacing: 2px;
}

header.banner nav ul {
    list-style: none;
    padding: 0;
    margin: 10px 0 0;
    display: flex;
    justify-content: center;
    gap: 20px;
}

header.banner nav ul li {
    display: inline;
}

header.banner nav ul li a {
    text-decoration: none;
    color: white;
    font-size: 1.2em;
    transition: color 0.3s;
}

header.banner nav ul li a:hover {
    color: D3BCA5;
}

/* Intro Section */
section.intro {
    padding: 40px 20px;
    text-align: center;
    background-color: #fff;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    margin: 20px;
    border-radius: 10px;
}

section.intro h2 {
    font-size: 2em;
    color: #222;
    margin-bottom: 10px;
}

section.intro p {
    font-size: 1.1em;
    color: #555;
    margin: 0;
}

/* Footer Styling */
footer {
    text-align: center;
    padding: 10px 0;
    background-color: #222;
    color: white;
    position: relative;
    bottom: 0;
    width: 100%;
}

footer p {
    margin: 0;
    font-size: 0.9em;
}

/* Responsive Design */
@media (max-width: 768px) {
    header.banner nav ul {
        flex-direction: column;
        gap: 10px;
    }

    section.intro {
        margin: 10px;
    }
}
```

## Menu Page
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            color: #333;
        }

        header.banner {
            background-color: #222;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header.banner h1 {
            margin: 0;
        }

        header.banner nav ul {
            list-style: none;
            padding: 0;
            margin: 10px 0 0;
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        header.banner nav ul li {
            display: inline;
        }

        header.banner nav ul li a {
            text-decoration: none;
            color: white;
            font-size: 1.2em;
            transition: color 0.3s;
        }

        header.banner nav ul li a:hover {
            color: #ff6347;
        }

        .menu {
            padding: 20px;
            text-align: center;
        }

        .menu h2 {
            font-size: 2em;
            color: #222;
            margin-bottom: 20px;
        }

        .menu-items {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 0;
        }

        .item {
            background: white;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            text-align: center;
            padding: 15px;
        }

        .item img {
            max-width: 100%;
            height: auto;
            border-bottom: 2px solid #f4f4f4;
        }

        .item h3 {
            font-size: 1.5em;
            margin: 10px 0;
        }

        .item p {
            font-size: 1.2em;
            color: #555;
        }

        footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 0;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <header class="banner">
        <h1>Menu</h1>
        <nav>
            <ul>
                <li><a href="res.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
                <li><a href="booktable.html">Reserve a table!</a></li>
            </ul>
        </nav>
    </header>

    <section class="menu">
        <h2>Our Delicious Menu</h2>
        <div class="menu-items">
            <div class="item">
                <img src="C:\Users\admin\Desktop\resimg\chocolate milkshke.jpg" alt="Chocolate Milkshake">
                <h3>Chocolate Milkshake</h3>
                <p>Rs.150</p>
            </div>

            <div class="item">
                <img src="c:\Users\admin\Desktop\resimg\dalgona.jpg" alt="Dalgona">
                <h3>Dalgona</h3>
                <p>Rs. 70</p>
            </div>

            <div class="item">
                <img src="c:\Users\admin\Desktop\resimg\coffee with biscuits.jpg" alt="Coffee with biscuits">
                <h3>Coffee with biscuit</h3>
                <p>Rs. 70</p>
            </div>

            <div class="item">
                <img src="c:\Users\admin\Desktop\resimg\waffle.jpg" alt="Waffle">
                <h3>waffle </h3>
                <p>Rs. 150</p>
            </div>

            <div class="item">
                <img src="c:\Users\admin\Desktop\resimg\noodles.jpg" alt="Noodles">
                <h3>Noodles</h3>
                <p>Rs. 210</p>
            </div>

            <div class="item">
                <img src="c:\Users\admin\Desktop\resimg\panner kathi roll.jpg" alt="Panner Kathi Roll">
                <h3>Panner Kathi Roll</h3>
                <p>Rs. 150</p>
            </div>

            <div class="item">
                <img src="c:\Users\admin\Desktop\resimg\veg meals.jpg" alt="Rice Platter">
                <h3>Rice Platter</h3>
                <p>Rs. 210</p>
            </div>

            <div class="item">
                <img src="c:\Users\admin\Desktop\resimg\veg biri.jpg" alt="Veg Biriyani">
                <h3>Veg Biriyani</h3>
                <p>Rs. 250</p>
            </div>

            <div class="item">
                <img src="c:\Users\admin\Desktop\resimg\naan.jpg" alt="Naan with Panner butter Masala">
                <h3>Naan with Panner butter Masala</h3>
                <p>Rs. 350</p>
            </div>

            <div class="item">
                <img src="c:\Users\admin\Desktop\resimg\dosa.jpg" alt="Malsala Dosa">
                <h3>Malsala Dosa</h3>
                <p>Rs. 150</p>
            </div>

            <div class="item">
                <img src="c:\Users\admin\Desktop\resimg\pizza.jpg" alt="pizza.">
                <h3>Panner pizza</h3>
                <p>Rs. 550</p>
            </div>

            <div class="item">
                <img src="c:\Users\admin\Desktop\resimg\samosa.jpg" alt="samosa">
                <h3>samosa</h3>
                <p>Rs. 60</p>
            </div>

            <div class="item">
                <img src="c:\Users\admin\Desktop\resimg\momos.jpg" alt="Momos">
                <h3>Momos</h3>
                <p>Rs. 120</p>
            </div>

            <div class="item">
                <img src="c:\Users\admin\Desktop\resimg\pani puri.jpg" alt="Pani Puri">
                <h3>pani Puri</h3>
                <p>Rs. 70</p>
            </div>

            <div class="item">
                <img src="c:\Users\admin\Desktop\resimg\icecream.jpg" alt="icecream">
                <h3>icecream</h3>
                <p>Rs. 120</p>
            </div>
        </div>
    </section>

    <footer>
        <p>Thanushree Vijayakanth - 24900679</p>
    </footer>
</body>
</html>
```
## Administration Page
```<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        .banner {
            background-color: #4CAF50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        .banner h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            background-color: #333;
        }

        nav ul li {
            margin: 0;
        }

        nav ul li a {
            display: block;
            padding: 10px 20px;
            text-decoration: none;
            color: white;
        }

        nav ul li a:hover {
            background-color: #4CAF50;
        }

        .team {
            padding: 40px 20px;
            text-align: center;
        }

        .team h2 {
            margin-bottom: 20px;
            font-size: 2em;
            color: #4CAF50;
        }

        .team-members {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }

        .member {
            background: white;
            border: 1px solid #ddd;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            width: 200px;
            padding: 20px;
            text-align: center;
        }

        .member img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 15px;
        }

        .member h3, .member h4, .member h5, .member h6 {
            margin: 10px 0 5px;
            font-size: 1.2em;
            color: #333;
        }

        .member p {
            margin: 0;
            font-size: 0.9em;
            color: #666;
        }

        footer {
            text-align: center;
            background-color: #333;
            color: white;
            padding: 10px 0;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header class="banner"> 
        <h1>Our Team</h1>
        <nav>
            <ul>
                <li><a href="res.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administrative 3.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
                <li><a href="booktable.html">Reserve a table!</a></li>
                <li><a href="booktable.html">Reserve a table!</a></li>
            </ul>
        </nav>
    </header>

    <section class="team">        <h2>Meet Our Team</h2>
        <div class="team-members">
            <div class="member">
                <img src="C:\Users\admin\Desktop\resimg\v.jpg" alt="Jimin">
                <h3>V</h3>
                <p>CEO</p>
            </div>
            <div class="member">
                <img src="c:\Users\admin\Desktop\resimg\rosie.jpg" alt="Jin">
                <h3>Rosie</h3>
                <p>Management Team</p>
            </div>
            <div class="member">
                <img src="C:\Users\admin\Desktop\resimg\jennie.jpg" alt="Suga">
                <h3>Jennie</h3>
                <p>Executive Team</p>
                <p></p>
            </div>
            <div class="member">
                <img src="C:\Users\admin\Desktop\resimg\jisoo.jpg" alt="Namjoon">
                <h3>Jisoo</h3>
                <p>Finance Team</p>
            </div>
            <div class="member">
                <img src="c:\Users\admin\Desktop\resimg\jk.jpg" alt="Kookie">
                <h3>Kookie</h3>
                <p>chef</p>
            </div>
            <div class="member">
                <img src="c:\Users\admin\Desktop\resimg\lisa.jpg" alt="Taehyung">
                <h3>Lisa</h3>
                <p>Manager</p>
            </div>
        </div>
    </section>

    <footer>
        <p>Thanushree Vijayakanth - 24900679</p>
    </footer>
</body>
</html>
```
## Reserve A Table Page
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Reserve a Table</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        .container {
            max-width: 600px;
            margin: 50px auto;
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);

        }

        .banner {
            background-color: #4CAF50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        .banner h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            background-color: #333;
        }

        nav ul li {
            margin: 0;
        }

        nav ul li a {
            display: block;
            padding: 10px 20px;
            text-decoration: none;
            color: white;
        }

        nav ul li a:hover {
            background-color: #4CAF50;
        }

        .contact {
            padding: 40px 20px;
            text-align: center;
        }

        .contact h2 {
            margin-bottom: 20px;
            font-size: 2em;
            color: #4CAF50;
        }

        .contact p {
            font-size: 1.2em;
            margin: 10px 0;
            color: #555;
        }

        footer {
            text-align: center;
            background-color: #333;
            color: white;
            padding: 10px 0;
            margin-top: 40px;
        }

        h1 {
            text-align: center;
            color: #333;
        }

        form {
            display: flex;
            flex-direction: column;
        }

        label {
            margin-top: 15px;
            margin-bottom: 5px;
            font-weight: bold;
        }

        input, select, textarea {
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            width: 100%;
            box-sizing: border-box;
        }

        button {
            margin-top: 20px;
            padding: 10px;
            background-color: #28a745;
            color: #fff;
            border: none;
            border-radius: 4px;
            font-size: 16px;
            cursor: pointer;
        }

        button:hover {
            background-color: #218838;
        }

        .note {
            margin-top: 10px;
            font-size: 0.9em;
            color: #666;
        }
    </style>
</head>
<body>
    <header class="banner">
        <h1>Contact Us</h1>
        <nav>
            <ul>
                <li><a href="res.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
                <li><a href="booktable.html">Reserve a table!</a></li>
            </ul>
        </nav>
    </header>

    <div class="container">
        <h1>Reserve a Table</h1>
        <form action="/submit-reservation" method="POST">
            <label for="name">Name</label>
            <input type="text" id="name" name="name" placeholder="Your full name" required>

            <label for="email">Email</label>
            <input type="email" id="email" name="email" placeholder="Your email address" required>

            <label for="phone">Phone Number</label>
            <input type="tel" id="phone" name="phone" placeholder="Your phone number" required>

            <label for="date">Date</label>
            <input type="date" id="date" name="date" required>

            <label for="time">Time</label>
            <input type="time" id="time" name="time" required>

            <label for="guests">Number of Guests</label>
            <select id="guests" name="guests" required>
                <option value="">Select number of guests</option>
                <option value="1">1</option>
                <option value="2">2</option>
                <option value="3">3</option>
                <option value="4">4</option>
                <option value="5">5</option>
                <option value="6">6</option>
                <option value="7">7</option>
                <option value="8">8+</option>
            </select>

            <label for="requests">Special Requests</label>
            <textarea id="requests" name="requests" rows="4" placeholder="Any special requests?"></textarea>

            <button type="submit">Reserve Now</button>
        </form>
        <p class="note">* Please arrive 10 minutes before your reserved time. For any changes, contact us directly.</p>
    </div>

    <footer>
        <p>Thanushree Vijayakanth - 24900679</p>
    </footer>
</body>
</html>
```
## Contact Us Page
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        .banner {
            background-color: #4CAF50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        .banner h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            background-color: #333;
        }

        nav ul li {
            margin: 0;
        }

        nav ul li a {
            display: block;
            padding: 10px 20px;
            text-decoration: none;
            color: white;
        }

        nav ul li a:hover {
            background-color: #4CAF50;
        }

        .contact {
            padding: 40px 20px;
            text-align: center;
        }

        .contact h2 {
            margin-bottom: 20px;
            font-size: 2em;
            color: #4CAF50;
        }

        .contact p {
            font-size: 1.2em;
            margin: 10px 0;
            color: #555;
        }

        footer {
            text-align: center;
            background-color: #333;
            color: white;
            padding: 10px 0;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header class="banner">
        <h1>Contact Us</h1>
        <nav>
            <ul>
                <li><a href="res.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
                <li><a href="booktable.html">Reserve a table!</a></li>
            </ul>
        </nav>
    </header>

    <section class="contact">
        <h2>Get in Touch</h2>
        <p><strong>Address:</strong>2nd main road,Candy Colony,Delicious city-600123</p>
        <p><strong>Phone:</strong> 987654321</p>
        <p><strong>Email:</strong> crunchymunchy@restaurant.com</p>
    </section>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
    <footer>
        <p>Thanushree Vijayakanth - 24900679</p>
    </footer>
</body>
</html>
```
# OUTPUT:
![image](https://github.com/user-attachments/assets/6d1aef93-a93b-419d-9e36-d0c1bd33a451)
![image](https://github.com/user-attachments/assets/990ef768-2429-40b3-9773-3c9f6636d3f5)
![image](https://github.com/user-attachments/assets/dee9fea1-0253-43a7-afdd-a89a0eb4ea30)
![image](https://github.com/user-attachments/assets/9eef5d88-3860-4a6b-8fc1-3d8a0b1d2848)
![image](https://github.com/user-attachments/assets/1f58cb11-989d-443b-adcf-1e33eafa933c)
![image](https://github.com/user-attachments/assets/bdfd288b-f01e-4265-b21c-a9d0e85f9c04)





# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
