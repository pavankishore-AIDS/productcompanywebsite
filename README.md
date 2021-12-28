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

### Layout:

### Home Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Anycook Private Ltd.</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Anycook Private Ltd.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/bake.jpg" alt="Building" />
          <div class="contenttext">
            Anycook Private Ltd., is one of only a handful few enduring Craft Bakeries in rameswaram
            island.
            We have assembled our notoriety on consolidating great quality conventional
            heating with a great incentive for cash.
            <br>
            We offer our clients a full scope of bread, forte bread, morning merchandise,
            cakes, and baked goods.
            <br>
            Our bread is heated day by day at our pastry shop in rameswaram and is conveyed
            to our new branch in ramnad too.
            We utilize profoundly gifted specialty dough punchers to guarantee each portion
            of bread is flawless without fail.
            <br>
            Our pastry specialists work during that time with the goal that the portion of 
            bread you purchase toward the beginning of the day is crisp out of the stove!
            <br>
            avalible productitems
            <ul>
              <li>CUP CAKE (BEST SELLER)</li>
              <li>BIRTHDAY CAKES</li>
              <li>SWEETS</li>
              <li>BREADS,etc</li>
            </ul>
            <marquee behavior="scroll" direction="left"><h2>---**HOME DELIVERY AVAILABLE**---</h2></marquee>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Anycook Private Ltd., Developed by: Pavan Kishore M.
      </div>
    </div>
  </body>
</html>
~~~
### Products:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Anycook Private Ltd.</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products :</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro1.jpg" alt="product image">
                  </div>
                  <div class="itemname">CUP CAKE</div>
                  <div class="itemprice">Price: Rs.75 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/pro2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">STEP CAKE</div>
                  <div class="itemprice">Price: Rs.700 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/pro3.jpg" alt="product image">
                </div>
                <div class="itemname">NORMAL CAKE</div>
                <div class="itemprice">Price: Rs.250 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/pro4.jpg" alt="product image">
              </div>
              <div class="itemname">CHOCO LAVA CAKE</div>
              <div class="itemprice">Price: Rs.500</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/pro5.jpg" alt="product image">
            </div>
            <div class="itemname">BLACK FOREST</div>
            <div class="itemprice">Price: Rs. 800</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/pro6.jpg" alt="product image">
          </div>
          <div class="itemname">BREAD</div>
          <div class="itemprice">Price: RS.50 </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/pro7.jpg" alt="product image">
        </div>
        <div class="itemname">MODEL CAKES</div>
        <div class="itemprice">Price: Rs.900 </div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/pro8.jpg" alt="product image">
      </div>
      <div class="itemname">PIECE CAKE</div>
      <div class="itemprice">Price: Rs.50 </div>
  </div>
  <div class="productitem"> 
    <div class="itemimage">
    <img src="/static/img/pro9.jpg" alt="product image">
    </div>
    <div class="itemname">BUNS</div>
    <div class="itemprice">Price: Rs.30 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/pro10.jpg" alt="product image">
  </div>
  <div class="itemname">SWEETS</div>
  <div class="itemprice">Price: Rs.500/KG </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/pro11.jpg" alt="product image">
  </div>
  <div class="itemname">CHOCOLATES</div>
  <div class="itemprice">Price: Rs.100/KG </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/pro12.jpg" alt="product image">
  </div>
  <div class="itemname">SPECIAL COFFEE</div>
  <div class="itemprice">Price: Rs.150 </div>
</div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Anycook Private Ltd., Developed by: Pavan Kishore M.
      </div>
    </div>
  </body>
</html>
~~~
### People:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Anycook Private Ltd.</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
            <h1>Best chefs in the world</h1>
            <div class="productitems">
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/sanji.jpg" alt="product image">
                    </div>
                    <div class="itemname">chef sanji</div>
                    <div class="itemprice">Head chef</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/soma.jpg"  alt="product image">
                    </div>
                    <div class="itemname">chef soma</div>
                    <div class="itemprice">Head chef</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/gordan.jpg"  alt="product image">
                    </div>
                    <div class="itemname">chef gordan</div>
                    <div class="itemprice">one of the best chef in the world</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/kunal.jpg"  alt="product image">
                    </div>
                    <div class="itemname">EMPLOYE</div>
                    <div class="itemprice">WORKING IN BAKERY</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/rin.jpg"  alt="product image">
                    </div>
                    <div class="itemname">EMPLOYE</div>
                    <div class="itemprice">WORKING IN BAKERY</div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/jamo.jpg"  alt="product image">
                    </div>
                    <div class="itemname">chef jamo</div>
                    <div class="itemprice">Assistant Baker</div>
                </div>

          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Anycook Private Ltd., Developed by: Pavan Kishore M.
      </div>
    </div>
  </body>
</html>

~~~
### Contact Us:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Anycook Private Ltd.</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
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
        
            <H1>Address:</H1><br>
                No: 8, TG Road, <br><br>
                Vanagaran, Ayyampakkam road,<br><br>
                Anna Nagar,<br><br>
                Chennai - 600053 <br<br>
              Contact:8056663183;<br><br>
              E-mail:anycook2021@gmail.com<br>
              <br>VERIFIED*
          </ul>    
        </div>
    </div>
    </div>
    </div>
      <div class="footer">
        Copyright &#169; 2021 Anycook Private Ltd., Developed by: Pavan Kishore M.
      </div>
    </div>
  </body>
</html>
~~~
## OUTPUT:

### Home Page:

![output](./images/homepage.jpg)

### Products:

![output](./images/homepage.jpg)

### Peoples:

![output](./images/homepage.jpg)

### Contact Us:

![output](./images/homepage.jpg)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
