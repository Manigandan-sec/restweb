# Ex.06 Restaurant Website
## Date:27-12-2025

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
rest.html
<html>
  <head>
    <title>Home</title>
    <link rel="stylesheet" href="style1.css" />
  </head>
  <body>
    <div class="background" >
      <div class="contents">
        <a href="rest.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
      </div>
      <div class="restname">
        <h1><b>STARBUCKS</b></h1>
      </div>
      <div class="line">The taste of USA!</div>
      <div class="lines">
        <i>"Where every bite feels like home in USA."</i>
        <p>
          Starbucks is known for its vast global coffeehouse chain, popularizing specialty coffee consistent branding, and a wide range of customizable drinks, snacks, and retail coffee, making it a lifestyle brand centered on human connection and the coffee experience.
        </p>
      </div>
      <footer class="copyrights">&copy;Manigandan S(25004934)</footer>
    </div>
  </body>
</html>

menu.html
<html>
  <head>
    <title>Home</title>
    <link rel="stylesheet" href="style2.css" />
  </head>
  <body>
    <div class="background">
      <div class="contents">
        <a href="rest.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
      </div>
      <div class="menu">
        <h1><b>MENU</b></h1>
      </div>
      <div class="menugrid">
        <div class="menuitem">
          <img src="chocolate.jpg " width="300" height="150" />
          <h1>Chocolate MilkShake</h1>
          <p>Rs. 190</p>
        </div>
        <div class="menuitem">
          <img src="coffee milk.jpg " width="300" height="150" />
          <h1>Coffee Milkshake</h1>
          <p>Rs. 180</p>
        </div>
        <div class="menuitem">
          <img src="mocha Frappe.jpg" width="300" height="150" />
          <h1>Mocha Frappe</h1>
          <p>Rs. 210</p>
        </div>
        <div class="menuitem">
          <img src="oreo milk.jpg " width="300" height="150" />
          <h1>Oreo Milkshake</h1>
          <p>Rs. 220</p>
        </div>
        <div class="menuitem">
          <img src="strawberry milk.jpg " width="300" height="150" />
          <h1>Strawberry Milkshake</h1>
          <p>Rs. 170</p>
        </div>
      </div>
      <footer class="copyrights">&copy; Manigandan S(25004934)</footer>
    </div>
  </body>
</html>

admin.html
<html>
  <head>
    <title>Home</title>
    <link rel="stylesheet" href="style3.css" />
  </head>
  <body>
    <div class="background">
      <div class="contents">
        <a href="rest.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
      </div>
      <div class="admin">
        <h1><b>ADMINISTRATION TEAM</b></h1>
      </div>
      <div class="admingrid">
        <div class="adminlist">
          <img src="mani.png" width="130" height="250" />
          <h1>Manigandan S</h1>
          <p class="post">CEO</p>
        </div>
        <div class="adminlist">
          <img src="shelby.jpeg" width="130" height="250" />
          <h1>Thomas Shelby</h1>
          <p class="post">Marketing Manager</p>
        </div>
        <div class="adminlist">
          <img src="anade.jpeg" width="130" height="250" />
          <h1>Ana de Armas</h1>
          <p class="post">Operations Manager</p>
        </div>
        <div class="adminlist">
          <img src="vj.jpeg" width="130" height="250" />
          <h1>Thalapathy</h1>
          <p class="post">Chairman</p>
        </div>
        <div class="adminlist">
          <img src="sam.jpeg" width="130" height="250" />
          <h1>Samantha</h1>
          <p class="post">Head Chef</p>
        </div>
        <div class="adminlist">
          <img src="f1.jpeg" width="130" height="250" />
          <h1>Sonny Hayes</h1>
          <p class="post">Food delivery and other services</p>
        </div>
      </div>
      <footer class="copyrights">&copy; Manigandan S {25004934}</footer>
    </div>
  </body>
</html>

contact.html
<html>
  <head>
    <title>Home</title>
    <link rel="stylesheet" href="style4.css" />
  </head>
  <body>
    <div class="background">
      <div class="contents">
        <a href="rest.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
      </div>
      <div class="contact">
        <h1><b>CONTACT</b></h1>
      </div>
      <div class="info">
        <h1>Visit us at:</h1>
        <p>
          STARBUCKS<br />123, Anna nagar,<br />Riverside Street, CA
          191414<br />India
        </p>
        <br />
        <h1>Phone:</h1>
        <p>+91 1234567890</p>
        <br>
        <h1>Email ID:</h1>
        <p>startbucks321@gmail.com</p>
      </div>
      <footer class="copyrights">&copy;Manigandan S(25004934)</footer>
    </div>
  </body>
</html>

style1.css
.background {
    width: 1470px;
    height: 680px;
    color:black;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image: url(starbucksin.jpg );
    background-size: cover;
}

.contents {
    width: 550px;
    height: 25px;
    border: 2px solid black;
    padding: 10px;
    background-color: aliceblue;
    text-align: center;
    top: 5px;
    left: 900px;
    position: relative;
    word-spacing: 70px;
}

.restname {
    color: paleturquoise;
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 300%;
    top: -50px;
}

.line {
    color: beige;
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 250%;
    top: -120px;
    left: 10px;
}

.lines {
    color: white;
    font-family: Verdana;
    text-align: center;
    position: relative;
    font-size: 130%;
    top: -100px;
}


.copyrights{
    width: 1510px;
    height: 20px;
    background-color: gray;
    text-align: center;
    top: 100px;
    left: -20px;
    position: relative;
}

style2.css
.background {
    width: 1470px;
    height: 680px;
    color:black;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image: url(starbucksin.jpg );
    background-size: cover;
}

.contents {
    width: 550px;
    height: 25px;
    border: 2px solid black;
    padding: 10px;
    background-color: aliceblue;
    text-align: center;
    top: 5px;
    left: 900px;
    position: relative;
    word-spacing: 70px;
}

.menu {
    color: paleturquoise;
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 300%;
    top: -50px;
}

.menugrid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(90px, 1fr));;
    gap: 50px;
    justify-items: center;
    padding: 20px;
    margin-top: -50px;
}

.menuitem {
    background-color: beige;
    border-radius: 10px;
    text-align: center;
    padding: 20px;
    width: 100%;
}

.menuitem img {
    border-radius: 10px;
    width: 100%;
    height: 180px;
    object-fit: cover;
}

.menuitem h1 {
    font-size: 1.5em;
    color: black;
    margin-top: 15px;
}

.menuitem p {
    color: black;
    margin-bottom: 0px;
}

.copyrights{
    width: 1510px;
    height: 20px;
    background-color: gray;
    text-align: center;
    top: 100px;
    left: -20px;
    position: relative;
}

style3.css
.background {
    width: 1470px;
    height: 680px;
    color:black;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image: url(starbucksin.jpg );
    background-size: cover;
}

.contents {
    width: 550px;
    height: 25px;
    border: 2px solid black;
    padding: 10px;
    background-color: aliceblue;
    text-align: center;
    top: 5px;
    left: 900px;
    position: relative;
    word-spacing: 70px;
}

.admin {
    color: paleturquoise;
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 300%;
    top: -50px;
}

.admingrid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(90px, 1fr));;
    gap: 50px;
    justify-items: center;
    padding: 20px;
    margin-top: -50px;
}

.adminlist{
    background-color: beige;
    border-radius: 10px;
    text-align: center;
    padding: 20px;
    width: 100%;
}

.adminlist img {
    border-radius: 10px;
    width: 100%;
    height: 250px;
    object-fit: cover;
    border-radius: 50% / 35%;
}

.adminlist h1 {
    font-size: 1.5em;
    color: black;
    margin-top: 15px;
}

.adminlist p {
    color: black;
    margin-bottom: 0px;
}

.copyrights {
    width: 1510px;
    height: 20px;
    background-color: gray;
    text-align: center;
    top: 30px;
    left: -20px;
    position: relative;
}

style4.css
.background {
    width: 1470px;
    height: 680px;
    color:black;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image: url(starbucksin.jpg );
    background-size: cover;
}

.contents {
    width: 550px;
    height: 25px;
    border: 2px solid white;
    padding: 10px;
    background-color: white;
    text-align: center;
    top: 5px;
    left: 900px;
    position: relative;
    word-spacing: 70px;
}

.contact {
    color: paleturquoise;
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 300%;
    top: -50px;
}

.info {
    color: white;
    font-family: Times New Roman;
    position: relative;
    top: -70px;
    left: 50;
}

.copyrights{
    width: 1510px;
    height: 20px;
    background-color: gray;
    text-align: center;
    top: -20px;
    left: -20px;
    position: relative;
}

```

## OUTPUT:
![alt text](<restapp/static/Screenshot (88).png>)
![alt text](<restapp/static/Screenshot (89).png>)
![alt text](<restapp/static/Screenshot (90).png>)
![alt text](<restapp/static/Screenshot (91).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
