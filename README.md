# Ex.07 Software Product Company Website
## Date:28.04.2024

## AIM:
To develop a static company website to display the softwares and services provided by the company.

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

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Software Company</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('image.png');
            background-repeat: no-repeat; 
            background-size: cover; 
            color: #fff; 
        }
        header {
            background-color: #333;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #666;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
        }
        nav a:hover {
            background-color: #999;
        }
        section {
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        h2 {
            text-align: center;
        }
        input[type="text"],
        input[type="password"],
        input[type="submit"] {
            width: 25%;
            padding: 10px;
            margin: 10px 0;
            box-sizing: border-box;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        input[type="submit"] {
            background-color: #333;
            color: #fff;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #555;
        }
    </style>
</head>
<body>
    <header>
        <h1>Software Company</h1>
    </header>
    <nav>
        <a href="http://127.0.0.1:8000/static/home.html">Home</a>
        <a href="http://127.0.0.1:8000/static/product.html">Products</a>
        <a href="http://127.0.0.1:8000/static/people.html">About Us</a>
        <a href="http://127.0.0.1:8000/static/about.html">Contact</a>
    </nav>
    <section id="home">
        <center>
            <h2>Welcome to Our Software Company!</h2>
        </center>
        <center>
            <p>We specialize in developing cutting-edge software solutions for businesses.</p>
        </center>
    </section>
    <div class="container">
        <h2 align="center">Login</h2>
        <center>
            <form action="login.php" method="POST">
                <input type="text" name="username" placeholder="Username" required><br>
                <input type="password" name="password" placeholder="Password" required><br>
                <input type="submit" value="Login">
            </form>
        </center>
    </div>
    <footer>
        <p>&copy; PRADEEP V.(212223240119) All rights reserved.</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Software Company - Products</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            background-image: url('image.png');
            background-repeat: no-repeat;
            background-size: cover;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 5px 0;
            text-align: center;
            margin-bottom: 30px;
        }
        nav {
            background-color: #666;
            padding: 10px 0;
            text-align: center;
            margin-bottom: 20px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
        }
        nav a:hover {
            background-color: #999;
        }
        section {
            padding: 20px;
            text-align: center;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .product {
            width: 300px;
            margin: 20px;
            padding: 20px;
            background-color: #ffffff;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(217, 17, 17, 0.1);
            transition: transform 0.3s ease;
        }
        .product:hover {
            transform: translateY(-5px);
        }
        .product img {
            max-width: 50%;
            border-radius: 5px;
            margin-bottom: 10px;
        }
        .product h3 {
            color: #333;
            font-size: 20px;
            margin-bottom: 10px;
        }
        .product p {
            color: #666;
            margin-bottom: 10px;
        }
        .product a {
            display: inline-block;
            background-color: #333;
            color: #fff;
            text-decoration: none;
            padding: 8px 16px;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }
        .product a:hover {
            background-color: #555;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Software Company</h1>
    </header>
    <nav>
        <a href="home.html">Home</a>
        <a href="product.html">PRODUCT</a>
        <a href="people.html">About Us</a>
        <a href="contact.html">Contact Us</a>
    </nav>
    <section>
        <div class="product">
                      <h3>PYTHON 3</h3>
            <p>
                Python is a versatile and user-friendly programming language with a rich ecosystem of libraries, ideal for a wide range of applications</p>
            <p>$32.35</p>
            <a href="product1.html">Details</a>
        </div>
        <div class="product">
           
            <h3>FRONT END DEVELOPMENT</h3>
            <p>
                Front end development focusing on the presentation layer that users interact with directly.</p>
            <p>$230.45</p>
            <a href="product2.html">Details</a>
        </div>
        <div class="product">
            
            <h3>C  PROGRAM</h3>
            <p>
                C programming is a widely-used, powerful, and efficient programming language known for its versatility and close-to-hardware capabilities.</p>
            <p>$12.45</p>
            <a href="product3.html">Details</a>
        </div>
    </section>
    <footer>
        <p>&copy; PRADEEP V.(212223240119) All rights reserved.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Software Company - People</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            background-image: url('image.png');
            background-repeat: no-repeat;
            background-size: cover;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 5px 0;
            text-align: center;
            margin-bottom: 30px;
        }
        nav {
            background-color: #666;
            padding: 10px 0;
            text-align: center;
            margin-bottom: 20px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
        }
        nav a:hover {
            background-color: #999;
        }
        section {
            padding: 20px;
            text-align: center;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }
        .person {
            margin: 20px;
            text-align: center;
        }
        .person img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            margin-bottom: 10px;
        }
        .person h3 {
            font-size: 20px;
            margin-bottom: 5px;
        }
        .person p {
            color: #0e0101;
            margin-bottom: 10px;
        }
        footer {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 20px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Software Company</h1>
    </header>
    <nav>
        <a href="home.html">Home</a>
        <a href="services.html">Product</a>
        <a href="people.html">About Us</a>
        <a href="contact.html">Contact Us</a>
    </nav>
    <section>
        <div class="person">
            <img src="PHOTO.jpg" alt="Person 1">
            <h3>PRADEEP V</h3>
            <p>Founder</p>
        </div>
        <div class="person">
            <img src="vi.jpg" alt="Person 2">
            <h3>THALAPATHY</h3>
            <p>CEO</p>
        </div>
        <div class="person">
            <img src="Al.jpg" alt="Person 3">
            <h3>ALLU ARJUN</h3>
            <p>FRONT END DEVELOPER</p>
        </div>
        <div class="person">
            <img src="SK.jpg" alt="Person 4">
            <h3>SK</h3>
            <p>PROGRAMMER</p>
        </div>
        <div class="person">
            <img src="dh.jpg" alt="Person 5">
            <h3>MSD</h3>
            <p>SOFTWARE DEVELOPER</p>
        </div>
    </section>
    <footer>
        <p>&copy; Designed by PRADEEP V.(212223240119) All rights reserved.</p>
    </footer>
</body>
</html>
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
            background-image: url('image.png');
            background-repeat: no-repeat;
            background-size: cover;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #666;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
        }
        nav a:hover {
            background-color: #999;
        }
        section {
            padding: 20px;
        }
        .contact-form {
            max-width: 600px;
            margin: 0 auto;
            background-color: #f3f3f3;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(227, 222, 222, 0.1);
            background-image: url(image.png);
        }
        .contact-form label {
            display: block;
            margin-bottom: 5px;
        }
        .contact-form input[type="text"],
        .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            box-sizing: border-box;
            border: 1px solid #e8b1b1;
            border-radius: 5px;
        }
        .contact-form textarea {
            height: 150px;
        }
        .contact-form input[type="submit"] {
            background-color: #333;
            color: #fff;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
        }
        .contact-form input[type="submit"]:hover {
            background-color: #555;
        }
        footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}

    </style>
</head>
<body>
    <header>
        <h1>Contact Us</h1>
    </header>
    <nav>
        <a href="home.html">Home</a>
        <a href="services.html">Product</a>
        <a href="about.html">About Us</a>
        <a href="about.html">Contact Us</a>
    </nav>
    <section>
        <div class="contact-form">
            <form action="#" method="post">
                <label for="name">Your Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Your Email:</label>
                <input type="text" id="email" name="email" required>
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                <input type="submit" value="Send Message">
            </form>
        </div>
    </section>
    <footer>
        <p>&copy; PRADEEP V.(212223240119) All rights reserved.</p>
    </footer>
</body>
</html>



```
## OUTPUT:
![i-1](https://github.com/velupradeep/softweb/assets/150329341/275daad3-69a5-44e6-b28f-d5f92ff88c1b)
![i-2](https://github.com/velupradeep/softweb/assets/150329341/07ad95b9-67c5-412a-8896-5d66d8938a1d)
![i-3](https://github.com/velupradeep/softweb/assets/150329341/93fea0cf-6631-4880-a801-096ccde27d66)
![i-4](https://github.com/velupradeep/softweb/assets/150329341/14fbe320-2667-4701-bc33-da88f84d5d5d)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
