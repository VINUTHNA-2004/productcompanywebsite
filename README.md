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
<<<<<<< HEAD
<<<<<<< HEAD
Layot css
```
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: #17421d;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px gray;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/img/x1.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #16d1ae;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #5bb045;
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
  color: #16d1ae;
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-color: #cffffd;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
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
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #5bb045;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}
```
home
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title></title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/x2.jpg" alt="Building" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product TallyPrime takes this to a new level, making your
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
        Copyright &#169; 2021 EduSoft Private Limited, Developed by D.R.Vinuthna.
      </div>
    </div>
  </body>
</html>
```
products
```
!DOCTYPE html>
<html lang="en">
<head>
<title></title>
<link rel="stylesheet" href="./css/layout.css" />
<link rel="icon" href="./img/icon.png" type="image/x-icon" />
</head>
<body>
<div class="container">
<div class="banner"></div>
<div class="menu">
<div class="menuitem"><a href="/static/home.html">Home</a></div>
<div class="menuitemselected"><a href="/static/products.html">Products</a></div>
<div class="menuitem"><a href="/static/people.html">People</a></div>
<div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
</div>
<div class="content">
<div class="productcontent">
<h1>Our Premium Products</h1>
<div class="productitems">
<div class="productitem">
<div class="itemimage">
<img src="/static/img/v1.jpg" alt="product image">
</div>
<div class="itemname">Microsoft</div>
<div class="itemprice">Price: Rs.10,ooo </div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/v2.jpg" alt="product image">
</div>
<div class="itemname">Apps & Windows Store</div>
<div class="itemprice">Price: Rs.4,500 </div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/v3.png" alt="product image">
</div>
<div class="itemname">Word</div>
<div class="itemprice">Price: Rs.5000 </div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/v4.png" alt="product image">
</div>
<div class="itemname">Execel</div>
<div class="itemprice">Price: Rs.5500 </div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/v5.png" alt="product image">
</div>
<div class="itemname">Windows phone</div>
<div class="itemprice">Price: Rs.6000 </div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/v6.png" alt="product image">
</div>
<div class="itemname">Skype</div>
<div class="itemprice">Price: Rs.6500</div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/v7.png" alt="product image">
</div>
<div class="itemname">MSN</div>
<div class="itemprice">Price: Rs.7000 </div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/v8.png" alt="product image">
</div>
<div class="itemname">Xbox</div>
<div class="itemprice">Price: Rs.7500 </div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/v9.png" alt="product image">
</div>
<div class="itemname">Share point</div>
<div class="itemprice">Price: Rs.8000 </div>
</div>
<div class="productitem"> 
<div class="itemimage">
<img src="/static/img/v10.png" alt="product image">
</div>
<div class="itemname">Access</div>
<div class="itemprice">Price:4000</div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/v11.png" alt="product image">
</div>
<div class="itemname">OneNote</div>
<div class="itemprice">Price: Rs.9500 </div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/v12.png" alt="product image">
</div>
<div class="itemname">Lync</div>
<div class="itemprice">Price: Rs.10,000 </div>
</div>
</div>
</div>
</div>
</div>
<div class="footer">
Copyright &#169; 2021 EduSoft Private Limited, Developed by D.R.Vinuthna.
</div>
</div>
</body>
</html>
```
people
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>adobe </title>
<link rel="stylesheet" href="./css/layout.css" />
<link rel="icon" href="./img/ail.png" type="image/x-icon" />
</head>
<body>
<div class="container">
<div class="banner"></div>
<div class="menu">
<div class="menuitem"><a href="/static/home.html">Home</a></div>
<div class="menuitem"><a href="/static/products.html">Products</a></div>
<div class="menuitemselected"><a href="/static/people.html">People</a></div>
<div class="menuitem"><a href="/static/contactus.html">Contact Us</a>
</div>
</div>
<div class="content">
<div class="homecontent">
<h1>Our company employees:</h1><br><br>
<div class="productitems">
<div class="productitem">
<div class="itemimage">
<img src="/static/img/d5.jpg" alt="product image">
</div>
<div class="itemname">Ian Joseph</div>
<div class="itemprice">CEO </div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/d6.jpg" alt="product image">
</div>
<div class="itemname">Paul</div>
<div class="itemprice">DSM</div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/d2.jpg" alt="product image">
</div>
<div class="itemname">Louis patridge</div>
<div class="itemprice">Assistant HR </div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/d3.jpg" alt="product image">
</div>
<div class="itemname">Owen joyner</div>
<div class="itemprice">HR </div>
</div>
<div class="productitem">
<div class="itemimage">
<img src="/static/img/d4.jpg" alt="product image">
</div>
<div class="itemname">Aidan</div>
<div class="itemprice">RSM </div>
</div> <div class="productitem">
<div class="itemimage">
<img src="/static/img/d1.jpg" alt="product image">
</div>
<div class="itemname">Thimotee</div>
<div class="itemprice">senior manager</div>
</div>
</div>
</div>
</div>
</div>
<div class="footer">
Copyright &#169; 2021 Adobe Private Limited, Developed by D.R.Vinuthna.
</div>
</div>
contactus
OUTPUT:
</body>
</html>
```
contact  us
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Adobe</title>
<link rel="stylesheet" href="./css/layout.css" />
<link rel="icon" href="./img/ail.png" type="image/x-icon" />
</head>
<body>
<div class="container">
<div class="banner"></div>
<div class="menu">
<div class="menuitem"><a href="/static/home.html">Home</a></div>
<div class="menuitem"><a href="/static/products.html">Products</a></div>
<div class="menuitem"><a href="/static/people.html">People</a></div>
<div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a>
</div>
</div>
<div class="content">
<div class="homecontent">
<h1>Contact Us:</h1><br><br>
<h1>Address:</h1>
<div class="contenttext">
967/4 G.I.D.C., MAKARPURA, VADODARA 390010, GUJARAT, INDIA.
</div><br>
<h1>Phone:</h1><br>
<div class="contenttext">
Mr.Owen joyner(HR):123456789<br><br>
Mr.Louis patridge(Assistant HR):987654321
</div>
<h1>E-Mail:</h1><br>
<div class="contenttext">
Sales:vinuthna2103@gmail.com
</div>
</div>
</div>
<div class="footer">
Copyright &#169; 2021 Adobe Private Limited, Developed by D.R.Vinuthna.
</div>
</div>
</body>
</html>
```

=======
=======
layout,css M
>>>>>>> 92cee082ea923c00408d46e80673f41304f51bf3
```
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: #17421d;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px gray;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/img/adobe.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #16d1ae;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #5bb045;
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
  color: #16d1ae;
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-color: #cffffd;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
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
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #5bb045;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}
```
```
home

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Microsoft privated limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/adobe.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/logo.png" alt="Building" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product TallyPrime takes this to a new level, making your
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
        Copyright &#169; 2021 EduSoft Private Limited, Developed by D.R.Vinuthna
      </div>
    </div>
  </body>
</html>

products
```
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Adobe Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>
  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/v1.jpg" alt="product image">
                  </div>
                  <div class="itemname">microsoft</div>
                  <div class="itemprice">Price: Rs.10000 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/v2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">apps and windows store</div>
                  <div class="itemprice">Price: Rs.4500 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/v3.png"  alt="product image">
                </div>
                <div class="itemname">word</div>
                <div class="itemprice">Price: Rs.5000 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/v4.png"  alt="product image">
              </div>
              <div class="itemname">Execel</div>
              <div class="itemprice">Price: Rs.5500 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/v5.png"  alt="product image">
            </div>
            <div class="itemname">windows phone</div>
            <div class="itemprice">Price: Rs.6000 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/v6.png"  alt="product image">
          </div>
          <div class="itemname">Skype</div>
          <div class="itemprice">Price: Rs.6500</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/v7.png"  alt="product image">
        </div>
        <div class="itemname">MSN</div>
        <div class="itemprice">Price: Rs.7000 </div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/v8.png"  alt="product image">
      </div>
      <div class="itemname">Xbox</div>
      <div class="itemprice">Price: Rs.7500</div>
  </div>
  <div class="productitem"> 
    <div class="itemimage">
    <img src="/static/img/v9.png"  alt="product image">
    </div>
    <div class="itemname">Share point</div>
    <div class="itemprice">Price: Rs.8000 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/v10.png"  alt="product image">
  </div>
  <div class="itemname">Access</div>
  <div class="itemprice">Price: Rs.4000 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/v11.png"  alt="product image">
  </div>
  <div class="itemname">Onenote</div>
  <div class="itemprice">Price: Rs.9,500 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/v12.png"  alt="product image">
  </div>
  <div class="itemname">Lync</div>
  <div class="itemprice">Price: Rs.10,000 </div>
</div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by D.R.Vinuthna
      </div>
    </div>
  </body>
</html>

people

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>microsoft</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
    </head>
    <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
      <div class="content">
        <div class="homecontent">
          <h1>Our company employees:</h1><br><br>
          <div class="productitems">
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/d5.jpg" alt="product image">
                </div>
                <div class="itemname">Ian Joseph</div>
                <div class="itemprice">CEO </div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/d6.jpg"  alt="product image">
                </div>
                <div class="itemname">Paul</div>
                <div class="itemprice">DSM</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/d2.jpg"  alt="product image">
              </div>
              <div class="itemname">Louis patridge</div>
              <div class="itemprice">Assistant HR </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/d3.jpg"  alt="product image">
              </div>
              <div class="itemname">Owen joyner</div>
              <div class="itemprice">HR </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/d4.jpg"  alt="product image">
            </div>
            <div class="itemname">Aidan</div>
            <div class="itemprice">RSM </div>
        </div>  <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/d1.jpg"  alt="product image">
          </div>
          <div class="itemname">Thimotee</div>
          <div class="itemprice">senior manager</div>
      </div>
          </div>
        </div>
        </div>        
    </div>
    <div class="footer">
      Copyright &#169; 2021 Adobe Private Limited, Developed by D.R.Vinuthna
    </div>
  </div>
</body>
</html>
````
```
contact us

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Adobe</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us:</h1><br><br>
          <h1>Address:</h1>
          <div class="contenttext">
            28-44/231/v5,SRI NAGAR,MADANAPALLI,CHITTOR 
          </div><br>
          <h1>Phone:</h1><br>
          <div class="contenttext">
              Mr.Ian Joseph(HR):8234567890<br><br>
              Mr.Louis patridge(Assistant HR):789898989
          </div>
          <h1>E-Mail:</h1><br>
          <div class="contenttext">
              Sales:vinuthna2103@gmail.com
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021  Adobe Private Limited, Developed by D.R.Vinuthna
      </div>
    </div>
  </body>
</html>


## OUTPUT:

### Home Page:

<<<<<<< HEAD
![output](https://github.com/VINUTHNA-2004/productcompanywebsite/blob/main/home.PNG?raw=tru)
## products
![output](https://github.com/VINUTHNA-2004/productcompanywebsite/blob/main/products.PNG?raw=true)
## people
![output](https://github.com/VINUTHNA-2004/productcompanywebsite/blob/main/people.PNG?raw=true)
## contact us
![output](https://github.com/VINUTHNA-2004/productcompanywebsite/blob/main/contact.PNG?raw=true)
=======
![output](https://github.com/VINUTHNA-2004/productcompanywebsite/blob/main/home.PNG?raw=true)

## Products
![output](https://github.com/VINUTHNA-2004/productcompanywebsite/blob/main/products.PNG?raw=true)

## People
![output](https://github.com/VINUTHNA-2004/productcompanywebsite/blob/main/people.PNG?raw=true)

## contact us
![output](https://github.com/VINUTHNA-2004/productcompanywebsite/blob/main/contact.PNG?raw=true)

>>>>>>> 92cee082ea923c00408d46e80673f41304f51bf3

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
