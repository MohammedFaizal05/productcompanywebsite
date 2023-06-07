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
```
Developed by: Mohammed Faizal.J
Reg no:212222100027
```
## Sample.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>FAIZO PRIVATE LIMITED</title>
    <link rel="stylesheet" href= "./css/layout.css" />
    <link rel="icon" href="/static/img/lamlo.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>FAIZO PRIVATE LIMITED.</b></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/sample.html">Home</a></div>
        <div class="menuitem"><a href="/static/product.html">products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="/static/img/lamlo.png" alt="Building" />
          <div class="contenttext">
            FAIZO PRIVATE LIMITED  is the exclusive dealer for LAMBORGHINI across Tamil Nadu and runs world class 4S (Sales, Service, Spares, Systems) facilities across the state. Trusted by many proud owners and adding more to the LAMBORGHINI family, FAIZO PRIVATE LIMITED continues to remain committed in setting high benchmarks in sales and after sales in the luxury automotive sector across Tamil Nadu in Chennai, Ambattur, Coimbatore and in Puducherry.

            FAIZO PRIVATE LIMITED team works with one motto - providing you with facts and details to make an informed decision and thereby helping you find the right LAMBORGHINI for yourself. We believe that it is essential to completely understand customer requirements and showcase the options that would best match his or her style, comfort and finances. All of this is further made easy by financing and leasing options made available by our BMW Financial Services team.

            FAIZO PRIVATE LIMITED takes great pride in its state-of-art LAMBORGHINI Certified Service facilities across Tamil Nadu. Each of these facilities is fully equipped equipment and LAMBORGHINI trained technicians. With all these facilities we are ready to cater to our customers desires and exceed with LAMBORGHINI their expectations.

You know you have come to the right place when you reach a FAIZO PRIVATE LIMITED facility. Feel free to walk into any of our facilities across Tamil Nadu or call us. It would be our pleasure to welcome you to any of our offices at your convenience. We look forward to share the sheer driving pleasure experience of a LAMBORGHINI with you.
            <br />
            
            <ul>
              <li>MODERN</li>
              <li>LUXURY</li>
              <li>CLASSIC</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 FAIZO PRIVATE LIMITED DEVELOPED BY Mohammed Faizal.J.
      </div>
    </div>
  </body>
</html>
```

## Product.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>FAIZO Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="/static/img/bmw.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>FAIZO PRIVATE LIMITED.</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/sample.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/product.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1><b>OUR PREMIUM PRODUCTS</b></h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/avento.png" alt="product image">
                  </div>
                  <div class="itemname">Aventador</div>
                  <div class="itemprice">Price: Rs.6.25 Cr </div>
              </div>
          <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/harac.png"  alt="product image">
                  </div>
                  <div class="itemname">Huracán</div>
                  <div class="itemprice">Price: Rs. 4.99 Cr </div>
              </div>
          <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/urus.jpg" alt="product image">
                  </div>
                  <div class="itemname">Urus</div>
                  <div class="itemprice">Price: Rs 4.22 Cr</div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/gallado.png" alt="product image">
                </div>
                <div class="itemname">Gallardo</div>
                <div class="itemprice">Price: Rs. 3.06 Cr</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/counta.jpg" alt="product image">
                </div>
                <div class="itemname">Countach</div>
                <div class="itemprice">Price: Rs: 25 Cr</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/hevo.png" alt="product image">
                </div>
                <div class="itemname">Huracan EVO</div>
                <div class="itemprice">Price: Rs.4.99 Cr.</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/avas.png" alt="product image">
                </div>
                <div class="itemname">Aventador S</div>
                <div class="itemprice">Price: Rs. 5.01 Cr</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/road.png" alt="product image">
                </div>
                <div class="itemname">Aventador Roadster</div>
                <div class="itemprice">Price: Rs. 5.62 Cr</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/hsto.jpg" alt="product image">
                </div>
                <div class="itemname">Huracan STO</div>
                <div class="itemprice">Price: Rs 4.99 Cr</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/diab.jpg" alt="product image">
                </div>
                <div class="itemname">Diablo</div>
                <div class="itemprice">Price: Rs 4.22 Cr.</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/miura.jpg" alt="product image">
                </div>
                <div class="itemname">Miura</div>
                <div class="itemprice">Price: Rs. 21 Cr</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/400gt.jpg" alt="product image">
                </div>
                <div class="itemname">400 GT</div>
                <div class="itemprice">Price: 3.73 Cr</div>
            </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 FAIZO PRIVATE LIMITED DEVELOPED BY Mohammed Faizal.J.
      </div>
    </div>
  </body>
</html>
```

## People.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>NK PRIVATE LIMITED</title>
    <link rel="stylesheet" href="./css/contact.css" />
    <link rel="icon" href="/static/img/bmw.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>NK PRIVATE LIMITED.</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/sample.html">Home</a></div>
        <div class="menuitem"><a href="/static/product.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <body>
          <div class="content">
              <h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Our Proud Management Crew!!!</h2>
              <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/yogi.jpg" height="600" width="600"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                    YOGESHVAR (Chairman)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/dk.jpg" height="600" width="600"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  DINESH KARTHICK (Head Executive)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/ss.jpg" height="600" width="600"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                 SRIRAM (Head Executive)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/leann.jpg" height="600" width="600"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  LEANN JOBY MATHEW (Manager)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/teja.jpg" height="600" width="600"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                 TEJESWINI (Manager)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/kaviya.jpg" height="600" width="600"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  KAVIYA SHREE (Deputy Manager)</h2></centre>
      </div>
      <div class="footer">
        Copyright &#169; 2023 NK PRIVATE LIMITED DEVELOPED BY G.R.NANDHAKUMAR.
      </div>
    </div>
  </body>
</html>
```

## Contact.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>FAIZO PRIVATE LIMITED </title>
    <link rel="stylesheet" href="./css/contact.css" />
    <link rel="icon" href="/static/img/bmw.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>FAIZO PRIVATE LIMITED.</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/sample.html">Home</a></div>
        <div class="menuitem"><a href="/static/product.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <body>
          <div class="content">
            <h1>&emsp;Contact Us</h1>
                    <p><b>&emsp;Here are the details listed below. Do contact us for any need</b></p>
                    <b><h2>&emsp;Contact Information:</h2></b>
                    <p><b>&emsp;&ensp;Address:</b>
                         No:6A,Thirumangalaam main road,Chennai,Tamilnadu,India.
                    </p>
                    <ul>
                        <li><b>&emsp;Phone</b>:&emsp;+919847625484</li>
                        <li><b>&emsp;Shop owner no</b>:&emsp;+918875496248</li>
                        <li><b>&emsp;Shop Manager Number:</b>+917339846582</li>
                        <li><b>&emsp;Email Id:</b>&emsp;FAIZOprivatelimited1@gmail.com</li>
                        <li><b>&emsp;Email Id:</b>&emsp;FAIZOprivatelimited2@gmail.com</li>
                    </ul>
          </div>
          </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 FAIZO PRIVATE LIMITED DEVELOPED BY Mohammed Faizal.J.
      </div>
    </div>
  </body>
</html>
```

## layout.css
```css
*{
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
  }
  
  body {
    background-color:darkblue;
    color:#09d7ee;
    background-image: url("/static/img/llam.jpg");
    background-repeat: no-repeat;
    background-size: cover;
  }
  .container {
    width: 1080px;
    margin-left: auto;
    margin-right: auto;
    border-width: 1px 1px 1px 1px;
    border-style: solid;
    box-shadow: 15px 15px 8px white;
  }
  
  .banner {
    display: block;
    width: 100%;
    height: 250px;
    text-align: center;
    font-size: 60px;
    font-family: inherit;
    background-image: url("/static/img/laml.jpg");
    background-color: aquamarine;
    background-size: 100% 100%;
    margin: 0px 0px 0px 0px;
    padding-top: 150px;
    color: #09d7ee;
  }
  
  .menu {
    display: block;
    width: 100%;
    height: 50px;
    font-size: larger;
    background-color:  #09d7ee;
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
    color:  #09d7ee;
  }
  
  .menuitem a {
    text-decoration: none;
    color: darkblue;
  }
  
  .content {
    display: block;
    width: 100%;
    background-color:darkblue;
    min-height: 500px;
    margin: 0px 0px 0px 0px;
    border-width: 1px;
    border-color: #09d7ee;
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
    background-color: #09d7ee;
    text-align: center;
    padding-top: 10px;
    margin: 0px 0px 0px 0px;
    color: #1b044ce5;
  }
```
  
## Contact.css
```css
* {
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
  }
  body {
    background-color: darkblue;
    color: #09d7ee;
    background-image: url("/static/img/background2.jpg");
    background-repeat: no-repeat;
    background-size: cover;
  }
  .container {
    width: 1080px;
    margin-left: auto;
    margin-right: auto;
    border-width: 1px 1px 1px 1px;
    border-style: solid;
    box-shadow: 15px 15px 8px white;
  }
  
  .banner {
    display: block;
    width: 100%;
    height: 250px;
    text-align: center;
    font-size: 60px;
    font-family: inherit;
    background-image: url("/static/img/Hero-banner.jpg");
    background-size: 100% 100%;
    margin: 0px 0px 0px 0px;
    padding-top: 150px;
    color: #09d7ee;
  }
  
  .menu {
    display: block;
    width: 100%;
    height: 50px;
    font-size: larger;
    background-color: #09d7ee;
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
    color: #09d7ee;
  }
  
  .menuitem a {
    text-decoration: none;
    color: darkblue;
  }
  
  .content {
    display: block;
    width: 100%;
    background-color: darkblue;
    font-size: 20px;
    min-height: 500px;
    margin: 0px 0px 0px 0px;
    border-width: 1px;
    border-color:#09d7ee;
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
    background-color:#09d7ee;
    text-align: center;
    padding-top: 10px;
    margin: 0px 0px 0px 0px;
    color: darkblue;
  }
```

## OUTPUT:

### Home Page:

![image](https://github.com/MohammedFaizal05/productcompanywebsite/assets/120553195/83f79360-bd4e-48fb-be69-433e27654408)

### Product Page:

![image](https://github.com/MohammedFaizal05/productcompanywebsite/assets/120553195/7e7cc2c3-c51d-4d1d-abab-8639b4e0c4a3)

### People Page:

![image](https://github.com/MohammedFaizal05/productcompanywebsite/assets/120553195/0348d752-6b88-4e11-9501-9887a9d4bf0f)

### Contact Page:

![image](https://github.com/MohammedFaizal05/productcompanywebsite/assets/120553195/9db1ee7b-97c1-45ca-94ff-a1627e26824b)

### Server Page:

![image](https://github.com/MohammedFaizal05/productcompanywebsite/assets/120553195/9657aeeb-5525-424e-a4a7-d9432f081df9)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
