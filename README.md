# Ex.07 Restaurant Website
## Date:

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
restapp.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TRAFFIC JAM RESTAURANT</title>
    <link rel="stylesheet" href="restapp.css">
</head>
<body>
    <header>
        <div>
            <h1>TRAFFIC JAM RESTAURANT</h1>
            <h3><strong aling="center">"Your Table is Ready – A Journey of Taste Awaits You!"</strong></h3>
            <strong>"Welcome to Traffic Jam Restaurant – your go-to destination for authentic Asian cuisine in a cozy, modern setting. At Traffic Jam, we celebrate the rich flavors and culinary traditions of Asia, serving dishes crafted with the freshest ingredients and utmost care. From spicy Thai delicacies to savory stir-fried favorites, each meal is a journey for your taste buds. Whether you're dining with family, friends, or colleagues, our warm hospitality and inviting atmosphere promise a memorable experience. Join us today and let Traffic Jam Restaurant turn your mealtime into a delightful culinary adventure!"Let me know if you’d like any tweaks! 😊</strong>
        </div>
        <nav>
            <ul>
                <li><a href="./restapp.html">Home</a></li>
                <li><a href="./menu.html">Menu</a></li>
                <li><a href="./admin.html">Administration</a></li>
                <li><a href="./contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <section class="promo">
        <div class="promo-text">
          <h2>🎉 New Year Special Offers 🎉</h2>
          <p>Start the year with flavor! Enjoy exclusive discounts and festive dishes this New Year season.</p>
        </div>
    </section>
    <main>
        <div class="card-container">
            <div class="card">
                <h3>Today's Special</h3>
                <img src="Screenshot 2024-12-15 214453.png" alt="Menu">
                <strong>Spicy Thai Basil Chicken</strong>
                <a href="./menu.html">See our new menu</a>
            </div>
            <div class="card">
                <h3>Book a table</h3>
                <img src="WhatsApp Image 2024-12-15 at 21.49.57_4ba9f0c6.jpg" alt="Reserve Now">
                <a href="./contact.html">Book your table now</a>
            </div>
            <div class="card">
                <h3>Working Hours</h3>
                <img src="WhatsApp Image 2024-12-15 at 21.49.57_2a61263b.jpg" alt="Timings">
                <div class="hours">
                </div>
            </div>
        </div>
    </main>
    <footer>
        <p>Designed and Developed by <a href="admin.html">M KRISHNA KUMARAN</a></p>
    </footer>
</body>
</html>
menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Menu | TRACFFIC JAM RESTAURANT</title>
    <link rel="stylesheet" href="menu.css">
</head>
<body>
    <header>
            <h1>TRAFFIC JAM RESTAURANT</h1>
        </div>
        <nav>
            <ul>
                <li><a href="./restapp.html">Home</a></li>
                <li><a href="./menu.html">Menu</a></li>
                <li><a href="./admin.html">Administration</a></li>
                <li><a href="./contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main class="main-container">
        <section class="page-title">
            <div>Our Menu</div>
            <p>Explore our delicious and tasty foods.</p>
        </section>
        <section class="menu-items">
            <div class="menu-card">
                <h3>parotta</h3>
                <img src="WhatsApp Image 2024-12-15 at 21.50.02_3e7e2a2c.jpg" alt="Timings">
                <p> Price: ₹20</p>
            </div>
            <div class="menu-card">
                <h3>ice cream</h3>
                <img src="WhatsApp Image 2024-12-15 at 21.50.02_001ad739.jpg" alt="Timings">
                <p> price: ₹50</p>
            </div>
            <div class="menu-card">
                <h3>Sharwama</h3>
                <img src="WhatsApp Image 2024-12-15 at 21.50.01_529b27aa.jpg" alt="Timings">
                <p>Price: ₹189</p>
            </div>
            <div class="menu-card">
                <h3>Mojito juice </h3>
                <img src="WhatsApp Image 2024-12-15 at 21.50.01_40aa053e.jpg" alt="Timings">
                <p> Price: ₹90</p>
            </div>
            <div class="menu-card">
                <h3>Paneer tikka</h3>
                <img src="WhatsApp Image 2024-12-15 at 21.50.00_2c0d3d29.jpg" alt="Timings">
                <p>Price: ₹159</p>
            </div>
            <div class="menu-card">
                <h3>Chicken biriyani</h3>
                <img src="WhatsApp Image 2024-12-15 at 21.50.00_05b6dafa.jpg" alt="Timings">
                <p> Price: ₹179</p>
            </div>
            <div class="menu-card">
                <h3>Chicken grill</h3>
                <img src="WhatsApp Image 2024-12-15 at 21.50.00_414ae1b6.jpg" alt="Timings">
                <p>Price: ₹189</p>
            </div>
            <div class="menu-card">
                <h3>Noodles</h3>
                <img src="WhatsApp Image 2024-12-15 at 21.49.59_f50082f8.jpg" alt="Timings">
                <p>Price: ₹189</p>
            </div>
        </section>
    </main>
    <footer>
        <p>Designed and Developed by <a href="admin.html">M KRISHNA KUMARAN</a></p>
    </footer>
</body>
</html>
contact.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us | TRACFFIC JAM RESTAURANT</title>
    <link rel="stylesheet" href="contact.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="./images/Asian_Restaurant-removebg.png" alt="Little Lemon Logo">
            <h1>TRACFFIC JAM RESTAURANT</h1>
        </div>
        <nav>
            <ul>
                <li><a href="./restapp.html">Home</a></li>
                <li><a href="./menu.html">Menu</a></li>
                <li><a href="./admin.html">Administration</a></li>
                <li><a href="./contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <div class="contact-banner">
            <h1>Contact Us</h1>
        </div>
        <section class="contact-section">
            <div class="contact-details">
                <p><strong>Address:</strong> No:5,E.B.Road,Trichy-2.</p>
                <p><strong>Phone:</strong> +919952724322</p>
                <p><strong>Email:</strong> trafficjam@gmail.com</p>
            </div>
        </section>
    </main>
    <footer>
        <p>Designed and Developed by <a href="admin.html">M KRISHNA KUMARAN</a></p>
    </footer>
</body>
</html>
admin.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration | TRACFFIC JAM RESTAURANT</title>
    <link rel="stylesheet" href="admin.css">
    <link rel="stylesheet" href="menu.css">
    <link rel="stylesheet" href="admin.css">
    <link rel="stylesheet" href="contact.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="./restapp.html">Home</a></li>
                <li><a href="./menu.html">Menu</a></li>
                <li><a href="./admin.html">Administration</a></li>
                <li><a href="./contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>

        
        <div class="admin-container">   

            <div class="admin-container-right">
                <section class="page-title">
                    <h2>Administration</h2>
                    <p>Founder of the Restaurant</p>
                        <div class="admin-containter-left">
                            <img src="WhatsApp Image 2024-11-12 at 17.28.17_e38470c7.jpg" alt="CEO M krishna kumaran photo" >
                        </div>
                    
                </section>
                <section class="admin-content">
                    <ul>
                    <p>M KRISHNA KUMARAN</p>
                    <p>As a young visionary, M Krishna Kumaran developed a passion for food and hospitality in Trichy. Inspired by bustling city life, he dreamed of creating a unique dining experience. His dedication and creativity led to the establishment of Traffic Jam Restaurant, a haven for food lovers amidst life’s chaos.</p>
                    </ul>
                    
                </section>
            </div>
        </div> 
        
    </main>
    <footer>
        <p>Designed and Developed by M KRISHNA KUMARAN</p>
    </footer>
</body>
</html>
```
```
restapp.css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #e0f7fa; /* Light blue background */
    color: #ffffff; /* White text */
}

header {
    background-color: #0277bd; /* Deep blue */
    padding: 10px 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-bottom: 2px solid #01579b; /* Darker blue */
}

header .logo {
    display: flex;
    align-items: center;
}

header .logo img {
    height: 50px;
    margin-right: 10px;
}

header h1 {
    font-size: 1.8rem;
    color: #ffffff; /* White */
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #ffffff; /* White */
    font-size: 1rem;
    font-weight: bold;
    padding: 5px 10px;
    border-radius: 5px;
}

nav ul li a:hover {
    background-color: #0288d1; /* Light blue */
}

.promo {
    background: url('pasta.jpg') no-repeat center center/cover;
    text-align: center;
    padding: 50px 20px;
    color: #ffffff; /* White */
}

.promo-text h2 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

.promo-text p {
    max-width: 600px;
    margin: 0 auto;
    line-height: 1.6;
}

main {
    padding: 20px;
}

.card-container {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 20px;
}

.card {
    background-color: #ffffff; /* White */
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    overflow: hidden;
    text-align: center;
    flex: 1 1 calc(33.333% - 20px);
    max-width: calc(33.333% - 20px);
    color: #333333; /* Dark gray text */
}

.card h3 {
    background-color: #0288d1; /* Light blue */
    padding: 15px;
    color: #ffffff; /* White */
    font-size: 1.3rem;
}

.card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.card p {
    padding: 15px;
    font-size: 0.95rem;
    color: #333333; /* Dark gray text */
}

.card a {
    display: block;
    color: #01579b; /* Dark blue */
    font-weight: bold;
    text-decoration: none;
    padding: 10px;
}

.card a:hover {
    color: #0277bd; /* Deep blue */
    text-decoration: underline;
}

.hours p {
    margin: 5px 0;
    color: #333333; /* Dark gray text */
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #0277bd; /* Deep blue */
    color: #ffffff; /* White */
    margin-top: 20px;
}

footer a {
    text-decoration: none;
    color: #ffffff; /* White */
    font-weight: bold;
}

footer a:hover {
    text-decoration: underline;
}
menu.css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #e0f7fa; /* Light blue background */
    color: #ffffff; /* White text */
}

header {
    background-color: #0277bd; /* Deep blue */
    padding: 10px 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-bottom: 2px solid #01579b; /* Darker blue */
}

header .logo {
    display: flex;
    align-items: center;
}

header .logo img {
    height: 50px;
    margin-right: 10px;
}

header h1 {
    font-size: 1.8rem;
    color: #ffffff; /* White */
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #ffffff; /* White */
    font-size: 1rem;
    font-weight: bold;
    padding: 5px 10px;
    border-radius: 5px;
}

nav ul li a:hover {
    background-color: #0288d1; /* Light blue */
}

.menu-title {
    text-align: center;
    margin: 30px 0;
    padding: 10px;
    background-color: #0277bd; /* Deep blue */
    color: #ffffff; /* White */
    font-weight: bold;
    border-radius: 8px;
}

/* Menu Items Container */
.menu-container {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 20px;
    margin: 20px auto;
    padding: 20px;
    max-width: 1200px;
}

.menu-card {
    background-color: #ffffff; /* White */
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    overflow: hidden;
    text-align: center;
    flex: 1 1 calc(33.333% - 20px);
    max-width: calc(33.333% - 20px);
    transition: transform 0.3s ease;
}

.menu-card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.menu-card h3 {
    background-color: #0288d1; /* Light blue */
    padding: 15px;
    color: #ffffff; /* White */
    font-size: 1.3rem;
    margin: 0;
}

.menu-card p {
    padding: 15px;
    font-size: 0.95rem;
    color: #333333; /* Dark gray text */
}

.menu-card:hover {
    transform: scale(1.03);
}

.menu-items {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.page-title {
    text-align: center;
    color: #0277bd; /* Deep blue */
}

.page-title div {
    font-size: 22px;
    margin-top: 30px;
    font-weight: bold;
}

main {
    height: 75vh;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #0277bd; /* Deep blue */
    color: #ffffff; /* White */
    margin-top: 20px;
}

footer a {
    text-decoration: none;
    color: #ffffff; /* White */
    font-weight: bold;
}

footer a:hover {
    text-decoration: underline;
}

/* Responsive Design */
@media (max-width: 768px) {
    .menu-card {
        flex: 1 1 calc(50% - 20px);
        max-width: calc(50% - 20px);
    }
}

@media (max-width: 480px) {
    .menu-card {
        flex: 1 1 100%;
        max-width: 100%;
    }
}
contact.css
/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    background-color: #f4f4f9; /* Light Grey Background */
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #0288d1; /* Light Blue */
    padding: 10px 20px;
    color: #ffffff; /* White */
}

header .logo {
    display: flex;
    align-items: center;
}

header .logo img {
    height: 50px;
    margin-right: 10px;
}

header h1 {
    font-size: 1.5rem;
    margin: 0;
}

nav ul {
    display: flex;
    list-style: none;
    margin: 0;
    padding: 0;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #ffffff; /* White */
    font-weight: bold;
    transition: color 0.3s ease;
}

nav ul li a:hover {
    color: #e1f5fe; /* Light Cyan */
}

/* Contact Banner */
.contact-banner {
    text-align: center;
    padding: 30px 0;
    background-color: #0277bd; /* Deep Blue */
    color: #ffffff; /* White */
    font-size: 2rem;
    font-weight: bold;
    border-radius: 0 0 10px 10px;
}

/* Contact Section */
.contact-section {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 30px 20px;
}

.contact-details {
    max-width: 600px;
    background-color: #ffffff; /* White */
    padding: 20px;
    border: 1px solid #0288d1; /* Light Blue */
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

.contact-details p {
    margin: 10px 0;
    font-size: 1.1rem;
    color: #333333; /* Dark Gray */
}

.contact-details strong {
    color: #01579b; /* Deep Blue */
}

/* Footer */
footer {
    text-align: center;
    background-color: #01579b; /* Dark Blue */
    color: #ffffff; /* White */
    padding: 10px 0;
    font-size: 0.9rem;
}

footer a {
    color: #e1f5fe; /* Light Cyan */
    text-decoration: none;
    font-weight: bold;
}

footer a:hover {
    color: #ffffff; /* White */
    text-decoration: underline;
}

/* Responsive Design */
@media (max-width: 768px) {
    header {
        flex-direction: column;
        text-align: center;
    }

    nav ul {
        flex-direction: column;
    }

    nav ul li {
        margin: 10px 0;
    }

    .contact-details {
        padding: 15px;
    }

    .contact-banner {
        font-size: 1.5rem;
    }
}
admin.css
.admin-title {
    text-align: center;
    margin: 30px 0;
    padding: 10px;
    background-color: #0277bd; /* Deep Blue */
    color: #ffffff; /* White */
    font-size: 2rem;
    font-weight: bold;
    border-radius: 8px;
}

/* Administration List */
.admin-container {
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
    background-color: #ffffff; /* White */
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    height: fit-content;
}

.admin-list {
    list-style: none;
    padding: 0;
}

.admin-list li {
    background-color: #e0f7fa; /* Light Blue */
    margin: 10px 0;
    padding: 15px;
    border: 1px solid #0288d1; /* Light Blue Border */
    border-radius: 5px;
    text-align: center;
    font-size: 1.1rem;
    font-weight: bold;
    color: #0277bd; /* Deep Blue */
    transition: all 0.3s ease;
}

.admin-list li:hover {
    background-color: #0277bd; /* Deep Blue */
    color: #ffffff; /* White */
    cursor: pointer;
}

.admin-container .admin-containter-left {
    width: 300px;
    height: auto;
}

.admin-container .admin-containter-left img {
    width: 100%;
    border-radius: 18px;
    margin-top: 10px;
}

.admin-content ul p {
    text-align: center;
    color: #0277bd; /* Deep Blue */
}

.page-title {
    text-align: center;
    display: flex;
    align-items: center;
    flex-direction: column;
    gap: 10px;
    color: #0277bd; /* Deep Blue */
}

.page-title div {
    font-size: 22px;
    font-weight: bold;
}
```

## OUTPUT:
![alt text](<Screenshot (36).png>)
![alt text](<Screenshot (37).png>)
![Screenshot (40)](https://github.com/user-attachments/assets/ed2de571-ea06-4a4a-8b65-af47fbcd18bd)
![Screenshot (41)](https://github.com/user-attachments/assets/baf532ed-911d-4528-a017-d8bc4fdeaa8f)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
