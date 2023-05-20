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
### home.html:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Preethi&Design Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logo.jpg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Preethi&Design Private Limited</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/logo.jpg" alt="Building" />
          <div class="contenttext">
            At Preethi&Design Private Limited ,we believe in making the best and 
            comfortable clothing for all without any drowback. Our main motto is to 
            produce good products with best quality at an affordable price. 
            <br />
            Our company mainly focus on giving the best product for the customers.
            We have collabed with one of the top companies like Louis Vuitton,
            Gucci and Versace.We are proud to start our company in India. We 
            assure you for the brand and quality. 
            <ul>
              <li>Comfy</li>
              <li>Affordable</li>
              <li>Customer satisfaction matters the most</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; Preethi&Design Private.Ltd, Developed by Preethi.
      </div>
    </div>
  </body>
</html>

### products.html:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Preethi&Design Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logo.jpg type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Preethi&Design Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/design1.jpg" alt="product image">
                  </div>
                  <div class="itemname">Lehenga</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/design2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Chudidhar</div>
                  <div class="itemprice">Price: Rs.5,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/design3.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Kurti</div>
                  <div class="itemprice">Price: Rs.2,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/design4.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Saree</div>
                  <div class="itemprice">Price: Rs.7,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/design5.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Chudidhar</div>
                  <div class="itemprice">Price: Rs.5,900.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/design6.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Mini Frock</div>
                  <div class="itemprice">Price: Rs.3,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/m1.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Jumpsuite</div>
                  <div class="itemprice">Price: Rs.2,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/m2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Casuals</div>
                  <div class="itemprice">Price: Rs.1,500.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/m3.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Hoodies</div>
                  <div class="itemprice">Price: Rs.1,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/m4.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Tuxedos</div>
                  <div class="itemprice">Price: Rs.7,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/m5.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Suits</div>
                  <div class="itemprice">Price: Rs.8,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/m6.jpg"  alt="product image">
                  </div>
                  <div class="itemname">TurtleNeck</div>
                  <div class="itemprice">Price: Rs.2,300.00 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; Preethi&Design Private.Ltd, Developed by Preethi.
      </div>
    </div>
  </body>
</html>

### people.html:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Preethi&Design Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css">
    <link rel="icon" href="./img/logo.jpg" type="image/x-icon"/>
  </head>

  <body>
    <div class="container">
      <div class="banner">Preethi&Design Private Limited</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">   
          <h1>CEO of the Brand</h1>
          <div class="productitems">
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/ceo gucci.jpg" alt="product image">
                  </div>
                  <div class="itemname">Marco Bizzarri</div>
                  <div class="itemprice">President & CEO of Gucci</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/ceo louis.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Michael Burke</div>
                  <div class="itemprice">Founder & CEO of Louis Vuitton</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/ceo versace.jpg" alt="product image">
                  </div>
                  <div class="itemname">Emmanuel Gintzburger</div>
                  <div class="itemprice">CEO of Versace</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/gucci.jpg" alt="product image">
                  </div>
                  <div class="itemname">Kim Taehyung</div>
                  <div class="itemprice">Ambassador of Gucci</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/louis.jpg" alt="product image">
                  </div>
                  <div class="itemname">Deepika Padukone</div>
                  <div class="itemprice">Ambassador of Louis Vuitton</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/versace.jpg" alt="product image">
                  </div>
                  <div class="itemname">Zendaya</div>
                  <div class="itemprice">Ambassador of Versace</div>
              </div>

          </div>
          </div>       
      </div>
      <div class="footer">
        Copyright &#169; Preethi&Design Private Limited, Developed by Preethi
      </div>
    </div>
  </body>
</html>

### contact.html:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Preethi&Design Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logo.jpg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Preethi&Design Private Limited</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contacts.html">Contact us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
       
          <div class="contenttext">
           Mail us at  Preethi&Design@gmail.com
           <br>
           Contact us at 220057942
           <br>
           Our main office is at 5th car street,TamilNadu,India.
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; Preethi&Design Private.Ltd, Developed by Preethi.
      </div>
    </div>
  </body>
</html>
```

## OUTPUT:

### Home Page:

![image](https://github.com/PreethiArunachalam/productcompanywebsite/assets/120115840/3589a07b-dc20-4b14-a90e-b26e1214d257)

### Products Page:

![image](https://github.com/PreethiArunachalam/productcompanywebsite/assets/120115840/2f7219bc-f7e7-4da2-8d45-3cdc7438244e)

### People Page:

![image](https://github.com/PreethiArunachalam/productcompanywebsite/assets/120115840/bc2a882b-1907-469e-b9a5-9b268fbe1a86)

### Contact Page:

![image](https://github.com/PreethiArunachalam/productcompanywebsite/assets/120115840/db44b395-f035-4b07-8135-bd9c9f31b7c3)

### Server Output:

![image](https://github.com/PreethiArunachalam/productcompanywebsite/assets/120115840/ec87a569-0e84-4a7a-9264-3e84e58a326f)

### HTML Validator:

![image](https://github.com/PreethiArunachalam/productcompanywebsite/assets/120115840/e200ab96-e2ec-4242-b089-5695727d5fab)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
