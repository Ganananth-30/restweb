# Ex.06 Restaurant Website
## Date: 23-12-2025

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
    <title>AMRITHA-Sub Branch OF Darling</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header class="main">
        <nav class="navbar">
            <ul>
                <li><a href="home.html">home</a></li>
                <li><a href="menu.html">menu</a></li>
                <li><a href="admin.html">admin</a></li>
                <li><a href="contact.html">contact</a></li>
            </ul>
        </nav>

        <div class="name">
            <h1>AMRITHA RESTURANT(PURE VEG)</h1>
            <p class="rest-quote"><b>"Experience Pure Vegetarian Elegance at Amirtha Fine Dining"</b></p>
            <p class="rest-description">Delight in the essence of vegetarian luxury at Amirtha Fine Dining. Indulge in carefully curated dishes that celebrate the richness of vegetarian cuisine and elevate your dining experience.
            Order Now</p>
        </div>

        <div class="image-home">
            <div class="dini">
                <img src="di.jpg">
            </div>
            <div class="dini">
                <img src="te.jpg">
            </div>
        </div>

        <footer>
            &copy; GANANANTH H - (25010984)
        </footer>
    </header>

</body>
</html>


menu.html



<html>
<head>
    <title>Menu</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header class="main">
        <nav class="navbar">
            <ul>
                <li><a href="home.html">home</a></li>
                <li><a href="menu.html">menu</a></li>
                <li><a href="admin.html" class="active">admin</a></li>
                <li><a href="contact.html">contact</a></li>
            </ul>
        </nav>
        <h1 class="main-title">MENU</h1>

        <div class="rect">
            <div class="cir">
                <div class="img-container">
                    <img src="f1.jpg" alt="Bun Parotta">
                </div>
                <h3>BUN PAROTTA</h3>
                <p>RS-70</p>
            </div>

            <div class="cir">
                <div class="img-container">
                    <img src="f2.jpg" alt="Paneer Fried Rice">
                </div>
                <h3>PANEER FRIED RICE</h3>
                <p>RS-120</p>
            </div>

            <div class="cir">
                <div class="img-container">
                    <img src="f3.jpg" alt="Buger">
                </div>
                <h3>BURGER</h3>
                <p>RS-150</p>
            </div>

            <div class="cir">
                <div class="img-container">
                    <img src="f5.jpg" alt="Chola Puuri">
                </div>
                <h3>CHOLA PURI</h3>
                <p>RS-90</p>
            </div>

             <div class="cir">
                <div class="img-container">
                    <img src="f6.jpg" alt="Butter Dosa ">
                </div>
                <h3>BUTTER DOSA</h3>
                <p>RS-85</p>
            </div>

             <div class="cir">
                <div class="img-container">
                    <img src="f7.jpg" alt="Naan With Paneer Butter Masala">
                </div>
                <h3>NAAN WITH PANEER BUTTER MASALA</h3>
                <p>RS-200</p>
            </div>
            </div>

        <footer class="footer-credit">
            &copy GANANANTH H - (25010984)
        </footer>
    </header>

</body>
</html>


admin.html 

<html>
<head>
    <title>Administration Team</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header class="main">
        <nav class="navbar">
            <ul>
                <li><a href="home.html">home</a></li>
                <li><a href="menu.html">menu</a></li>
                <li><a href="admin.html" class="active">admin</a></li>
                <li><a href="contact.html">contact</a></li>
            </ul>
        </nav>

        <h1 >ADMINISTRATION TEAM</h1>
        <br>
        <br>
        <br>

        <div class="rect">
            <div class="cir">
                <div class="img-container">
                    <img src="pic.jpg" alt="GANANANTH H">
                </div>
                <h3>GANANANTH H</h3>
                <p>CEO</p>
            </div>

            <div class="cir">
                <div class="img-container">
                    <img src="1.jpg" alt="Kalyani Priyadarshan">
                </div>
                <h3>Kalyani Priyadarshan</h3>
                <p>Marketing Manager</p>
            </div>

            <div class="cir">
                <div class="img-container">
                    <img src="2.jpg" alt="Naruto Uzumaki">
                </div>
                <h3>Naruto Uzumaki</h3>
                <p>Customer Service Manager</p>
            </div>

            <div class="cir">
                <div class="img-container">
                    <img src="3.jpg" alt="Vijay Deverakonda">
                </div>
                <h3>Vijay Deverakonda </h3>
                <p>HR Manager</p>
            </div>

            <div class="cir">
                <div class="img-container">
                    <img src="4.jpg" alt=" Ajith Kumar">
                </div>
                <h3>Ajith Kumar</h3>
                <p>Executive Chef</p>
            </div>

             <div class="cir">
                <div class="img-container">
                    <img src="6.jpg" alt="Allu Arjun">
                </div>
                <h3>Allu Arjun</h3>
                <p>Operations Manager</p>
            </div>
            </div>
        <footer class="footer-credit">
            &copy GANANANTH H - (25010984)
        </footer>
    </header>

</body>
</html>



contact.html


<html>
<head>
    <title>Contact - Amrita Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body class="tat">

    <header >
        <nav class="navbar">
            <ul>
                <li><a href="home.html">home</a></li>
                <li><a href="menu.html">menu</a></li>
                <li><a href="admin.html" class="active">admin</a></li>
                <li><a href="contact.html">contact</a></li>
            </ul>
        </nav>

    <main class="contact-container">
        <h1 class="main-title">CONTACT</h1>

        <section class="info-section">
            <div class="info-group">
                <h3>Visit us at:</h3>
                <p>Amritha Hotel (Pure Veg)<br>
                   Katpadi - Vellore Rd, Suthanthira Ponvizha Nagar,Gandhi Nagar,Silk Mill<br>
                   Vellore,Tamil Nadu-632006,<br>
                   India</p>
            </div>

            <div class="info-group">
                <h3>Phone:</h3>
                <p>+91 9047139999</p>
                <p>MON-SUN : 7am-10.30pm</p>
            </div>

            <div class="info-group">
                <h3>Email ID:</h3>
                <p>amirthavegclassic@gmail.com</p>
            </div>
        </section>
    </main>

    <footer class="footer">
        &copy GANANANTH H - (25010984)
    </footer>

</body>
</html>



styles.css


* 
{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Arial', sans-serif;
}

.main {
    background: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.3)), 
    url('am.jpeg'); 
    background-size: cover;
    background-position: center;
    min-height: 100vh;
    padding: 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
    position: relative;
}

h1 
{
    padding-top: 75px;
    font-size: 70px;
    color:coral;
    letter-spacing: 20px;
}
.navbar
{
    position: absolute;
    top: 20px;
    right: 30px;
    background: whitesmoke; 
    padding: 10px 40px;
    border-radius: 30px;
}
.navbar ul 
{
    list-style: none;
    display: flex;
    gap: 40px;
}

.navbar ul li a 
{
    color: indigo;
    font-weight: bold;
    font-size: 14px;
}

.rect 
{
    display: flex;
    justify-content: center;
    gap: 15px;
    flex-wrap: wrap;
    width: 100%;
}

.cir
{
    background-color: papayawhip; 
    width: 200px;
    padding: 10px 5px;
    border-radius: 5px;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0,0,0,0.3);
}

.img-container {
    width: 150px;
    height: 200px;
    margin: 0 auto 30px;
    border-radius: 50%; 
}

.img-container img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.cir h3 {
    font-size: 18px;
    margin-bottom: 5px;
    color: black;
}

.cir p 
{
    font-size: 15px;
    color: black;
    font-weight: 500;
    font-weight: bold;
}

.tat 
{
    height: 100vh;
    width: 100%;
    background: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.3)), 
    url('am.jpeg');
    background-size: cover;
    background-position: center;
    position: relative;
    color: cyan;
    text-align: left;

}

.contact-container {
    padding: 50px;
    flex: 1;

}

.main-title {
    font-size: 80px;
    color: gold;
    letter-spacing: 5px;
    margin-bottom: 40px;
    font-weight: bold;
}

.info-section {
    max-width: 400px;


}

.info-group {
    margin-bottom: 30px;
}

.info-group h3 {
    font-size: 30px;
    font-family: 'Georgia', serif;
    margin-bottom: 10px;
}

.info-group p {
    font-size: 20px;
    line-height: 1;
    font-weight: 300;

}

.name 
{
    padding-top: 75px;
    padding-left: 50px;
}

h1 
{
    font-size: 70px;
    color:coral;
    letter-spacing: 5px;
}

.rest-quote 
{
    font-style: italic;
    font-size: 20px;
    text-align: center;
    margin-top: 20px;
    color: gold;
}

.rest-description 
{
    text-align: left;
    max-width: 800px;
    margin: 25px auto;
    font-size: 20px;
    color: gold;
}

.image-home {
    display: flex;
    justify-content: center;
    gap: 30px;
    margin-top: 20px;
    padding: 0 50px;
}

.dini 
{
    width: 450px;
    height: 300px;
    object-fit: fit;
    border: 8px solid goldenrod;
}

img{
    height: 285px;
    width: 435px;
}
footer {
    position: absolute;
    bottom: 1px;
    width: 100%;
    text-align: center;
    font-size: 25px;
    color: black;
    background-color: azure;
}




```

## OUTPUT:

![alt text](<Screenshot (43).png>)

![alt text](<Screenshot (44).png>)

![alt text](<Screenshot (45).png>)

![alt text](<Screenshot (46).png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
