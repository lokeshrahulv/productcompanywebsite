# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

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

### Step 6:

Publish the website in the given URL.

## PROGRAM :
### home.html
````
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./layout.css">
    <link rel="icon" href="w0.jpg" type="images/x-icon">
  </head>
  <body>
      <h1 class="head">EduSoft Private Limited.</h1>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/home/" class="home1">Home</a></div>
        <div class="menuitemselected"><a href="/products/" class="home1">Products</a></div>
        <div class="menuitemselected"><a href="/people/" class="home1">People</a></div>
        <div class="menuitemselected"><a href="/contactus/" class="home1">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          
          <div class="contenttext">
            At Edusoft, we understand the importance of technology in enhancing business efficiency and empowering 
            entrepreneurs. That's why we design our products to be user-friendly and adaptable to your specific needs.
            Our latest offering, Edusoft Prime, takes this to the next level by making the 
            transition to automation and our platform simpler than ever before.
            With an intuitive interface and customizable features, you can easily discover the 
            full potential of the product without needing to learn any new skills.
            Edusoft Prime adapts to your unique business and working style,
            providing greater flexibility and a transformed look and feel
            that will make you love it even more.

            Our new product takes this to a new level, making your
            start to automation, or your switch to Tally simpler than ever
            before. You can now discover the product much more easily and make
            the product do more for you, without learning anything new. There is
            greater flexibility as the product adapts to your business and your
            way of working. And the transformed look and feel will only make you
            love the product even more.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 EduSoft Private Limited, Developed by Lokesh Rahul V V      
      </div>
    </div>
  </body>
</html>
````
### people.html
````
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    
     <link rel="stylesheet" href="./layout.css">
    <link rel="icon" href="w0.jpg" type="image/x-icon">
    
  </head>

  <body>
      <h1 class="head">EduSoft Private Limited</h1>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>PEOPLE AT EDUSOFT</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="images/p1.jpg" alt="product image">
                  </div>
                  <div class="itemname">Mickel</div>
                  <div class="itemprice">Managing Director</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="images/p2.png"  alt="product image">
                  </div>
                  <div class="itemname">Franklin</div>
                  <div class="itemprice">Co-founder and Chairman of the Board </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="images/p3.png" alt="product image">
                  </div>
                  <div class="itemname">Trevor</div>
                  <div class="itemprice">Lead Independent Director </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="images/p4.jpg" alt="product image">
                  </div>
                  <div class="itemname">TOM</div>
                  <div class="itemprice">Independent Director India </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="images/p5.jpg" alt="product image">
                  </div>
                  <div class="itemname">Walker</div>
                  <div class="itemprice">Independent Director </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="images/p6.webp" alt="product image">
                  </div>
                  <div class="itemname">Musk</div>
                  <div class="itemprice">Independent Director</div>
              </div>
             
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 EduSoft Private Limited, Developed by Lokesh Rahul V V
      </div>
    </div>
  </body>
</html>
````
### product.html
````
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
     <link rel="stylesheet" href="./layout.css">
    <link rel="icon" href="w0.jpg" type="image/x-icon">
    
  </head>

  <body>
      <h1 class="head">EduSoft Private Limited</h1>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
     <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="g1.jpg" alt="product image">
                  </div>
                  <div class="itemname">Amazon Echo Dot</div>
                  <div class="itemprice">Price: Rs.4,499 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="g2.webp"  alt="product image">
                  </div>
                  <div class="itemname">Apple Iphone 12</div>
                  <div class="itemprice">Price: Rs.54,499 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="g3.jpg" alt="product image">
                  </div>
                  <div class="itemname">Marshall Headphones</div>
                  <div class="itemprice">Price: Rs.12,999 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="g4.webp" alt="product image">
                  </div>
                  <div class="itemname">TMacBook Air M1</div>
                  <div class="itemprice">Price: Rs.99,990 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="g5.webp" alt="product image">
                  </div>
                  <div class="itemname">Apple Watch SC</div>
                  <div class="itemprice">Price: Rs.54,000 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="g6.jpg" alt="product image">
                  </div>
                  <div class="itemname">VR</div>
                  <div class="itemprice">Price: Rs.66,900 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="g7.jpg" alt="product image">
                  </div>
                  <div class="itemname">DSLR</div>
                  <div class="itemprice">Price: Rs.52,900 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="g8.jpg" alt="product image">
                  </div>
                  <div class="itemname">DJI MAVIC AIR 2S</div>
                  <div class="itemprice">Price: Rs.99,999 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="g9.webp" alt="product image">
                  </div>
                  <div class="itemname">SAMSUNG TV</div>
                  <div class="itemprice">Price: Rs.44,900 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="g10.webp" alt="product image">
                  </div>
                  <div class="itemname">PowerBank 20000mah</div>
                  <div class="itemprice">Price: Rs.3999 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="g11.jpg" alt="product image">
                  </div>
                  <div class="itemname">Hoverboard</div>
                  <div class="itemprice">Price: Rs.13,999</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="g12.jpg" alt="product image">
                  </div>
                  <div class="itemname">Joystick</div>
                  <div class="itemprice">Price: Rs.1999 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 EduSoft Private Limited, Developed by Lokesh Rahul V V
      </div>
    </div>
  </body>
</html>
````
### contact.html
````
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
   <link rel="stylesheet" href="../css/layout.css">
    <link rel="icon" href="/static/icon.png" type="image/x-icon">
     
  </head>

  <body>
      <h1 class="head">EduSoft Private Limited</h1>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
          
            <h1>Contact Us</h1>
  <p>If you have any questions or feedback, please don't hesitate to reach out to us.</p>
  <ul>
    <li>Address: 123,Mr John Smith. 132, My Street, Kingston, New York 12401.</li>
    <li>Phone: +91 8765432109</li>
    <li>Email: contact@edusoft.com</li></ul>
  
<h2> Sales Inquiries</h2>

<ul><li>UK 1800 103 11231800 572 3535</li></ul>
    <h2>Press Inquiries</h2> 
<ul><li>press@edusoft.com</li>

<li>Trevor</li>
<li>Trevor@edusoft.com</li></ul>
    <h2>Analyst Relations</h2> 

    <ul><li>Franklin</li>
    <li>+1-925-924-9500</li>
    <li>Franklin@edosoft.com</li></ul>
        <h2>Customer Relations</h2> 

    <ul><li>Mickel</li>
    <li>Director of Sales & Customer Service</li>
    <li>Mickel@edusoft.com</li>
    </ul>
    
  </div>
   <div class="footer">
        Copyright &#169; 2023 EduSoft Private Limited, Developed by B.Mohamed Athil.
      </div>
      </div>
</body>
</html>
````
### layout.css
````
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: black;
  color:white;
}
.container {
  width: 100%;
  margin-left: auto;
  margin-right: auto;
  border-width: 5px 5px 5px 5px;
  border-style: solid;
}

.banner {
  display: block;
  width: 100%;
  height: 100px;
  text-align: center;
  font-size: 10px;
  background-image: url("w1layout.css");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #2e2e2e;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color:rgb(59, 59, 59);
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}

.menuitem a {
  text-decoration: none;
  color:white;
}

.home1{
    color: #fff;
    
}

.content {
  display: block;
  width: 100%;
  background-color: #000000;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 5px;
  border-color:rgb(255, 255, 255);
  border-style: solid;
}
.homecontent {
  min-height: 550px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  font-size: xx-large;
}
.homecontent img {
  float: right;
  width: 320px;
  height: 150px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  font-size: x-large;
  color: white;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  font-size: xx-large;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 400px;
  height: 250px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 300px;
  margin-bottom: 70px;
}

.productitem .itemname {
  display: block;
  text-decoration: #ffffff;
  font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
  font-size: larger;
  font-weight: 1000px;
}
.productitem .itemprice {
  display: block;
  font-family: Georgia, 'Times New Roman', Times, serif;
  font-style: italic;
  font-size: large;
}

.peoplecontent {
  min-height: 10px;
  margin: 10px 10px 10px 10px;
}

.peoplecontent h1 {
  text-align: left;
}

.peopletitems {
  display: block;
}

.peopleitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.peopleitem img {
  width: 400px;
  height: 250px;
  display: block;
}
.peopleitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 300px;
  margin-bottom: 70px;
}

.peopleitem .itemname {
  display: block;
  text-decoration: #ffffff;
  font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
  font-size: larger;
  font-weight: 1000px;
}
.peopleitem .itemprice {
  display: block;
  font-family: Georgia, 'Times New Roman', Times, serif;
  font-style: italic;
}
.contactcontent {
  min-height: 550px;
  margin: 10px 10px 10px 10px;
}
.contactcontent h1 {
  text-align: left;
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  font-size: xx-large;
}
.contactcontent img {
  float: center;
  width: 70px;
  height: 90px;
  margin-left: 10px;
}
.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #ffffff;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #000000;
}

.head{
    color: #fff;
    position: absolute;
    top: 8%;
    left: 40%;
}
````

## OUTPUT:
### Home Page:
![Screenshot (35)](https://github.com/lokeshrahulv/productcompanywebsite/assets/118423842/572e7f86-d95f-455c-92b3-60a453c4f6c1)

### people.html
![Screenshot (36)](https://github.com/lokeshrahulv/productcompanywebsite/assets/118423842/7f946c6c-d700-46ea-9c96-5d3f3d44c2bc)

### product.html
![Screenshot (37)](https://github.com/lokeshrahulv/productcompanywebsite/assets/118423842/abc1bd55-e34a-487d-94fe-b59553930226)
![Screenshot (38)](https://github.com/lokeshrahulv/productcompanywebsite/assets/118423842/76f8355f-99d3-454d-aef7-4f1d42ccdeaa)

### contact.html
![Screenshot (39)](https://github.com/lokeshrahulv/productcompanywebsite/assets/118423842/2c1d5075-1614-4147-b5b0-90c8fec63bba)

## Result:
Thus a website is designed for the software product company and the HTML,CSS code are validated.
