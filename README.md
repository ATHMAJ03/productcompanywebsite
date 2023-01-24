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
HOME PAGE:
```
<style>
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color:black;
  color:white;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 10px;
  font-weight: bold;
  background-image: url("/static/images/kera.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 130px;
  padding-left:250px;
  color:white;
}



.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color:black;
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
  text-decoration:none;
  color: white;
}
h1 {
    color:white;
}

.content {
  display: block;
  width: 100%;
  background-color: rgb(48,48,48);
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color:rgb(48,48,48);
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
  font-family: Arial, Helvetica, sans-serif;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
  color:honeydew;
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
  background-color:black;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color:white;
}

</style>



<!DOCTYPE html>
<html lang="en">
  <head>
    <title>KERA</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="/static/images/kera.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitem"><a href="/products/">Products</a></div>
        <div class="menuitem"><a href="/people/">People</a></div>
        <div class="menuitem"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="/static/images/kera.png" border-color="yellow" alt="logo" />
          <div class="contenttext">
            KERA Private Limited is an Indian e-commerce company, headquartered in Kerala, and incorporated in Singapore as a private limited company.KERA was founded in October 2007 by Sachin Bansal and Binny Bansal, alumni of the IIT, Delhi and former Amazon employees.
            <br />
            <ul>
              <li>KERA is free to use</li>
              <li>Bulk discounts & Business deals.</li>
              <li>Free delivery </li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 KERA , Designed By Athmaj Venugopal
      </div>
    </div>
  </body>
</html>
```
Product Page:
```
<style>
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color:black;
  color:white;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 10px;
  font-weight: bold;
  background-image: url("/static/images/kera.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 130px;
  padding-left:250px;
  color:white;
}



.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color:black;
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
  text-decoration:none;
  color: white;
}
h1 {
    color:white;
}

.content {
  display: block;
  width: 100%;
  background-color: rgb(48,48,48);
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color:rgb(48,48,48);
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
  font-family: Arial, Helvetica, sans-serif;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
  color:honeydew;
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
  background-color:black;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color:white;
}

</style>


<!DOCTYPE html>
<html lang="en">
  <head>
    <title>KERA</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="/static/images/kera.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitem"><a href="/people/">People</a></div>
        <div class="menuitem"><a href="/contactus/">Contact Us</a></div>
      </div>
      
      <div class="content">
        <div class="productcontent">
            <h1 class="hrr">LAPTOP PRODUCTS</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/lenova3ichromebook.png" alt="product image">
                  </div>
                  <div class="itemname">Lenova IdeaPad Slim 3i Chromebook</div>
                  <div class="itemprice">Price: Rs. 16,990.00  </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/hppavilion.png"  alt="product image">
                  </div>
                  <div class="itemname">HP Pavilion</div>
                  <div class="itemprice">Price: Rs.61,000.00</div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/images/aceraspire.png"  alt="product image">
                </div>
                <div class="itemname">Acer Aspire</div>
                <div class="itemprice">Price:Rs.23,000.00  </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/images/asustuf.png"  alt="product image">
                </div>
                <div class="itemname">ASUS TUF Gaming</div>
                <div class="itemprice">Price: Rs.50,000.00</div>
              </div><div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/apple2020macbook.png"  alt="product image">
                  </div>
                  <div class="itemname">APPLE 2020 Macbook</div>
                  <div class="itemprice">Price: Rs.86,000 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/images/asusvivobook.png"  alt="product image">
                </div>
                <div class="itemname">ASUS Vivobook</div>
                <div class="itemprice">Price: Rs.33,000 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/images/dell.png"  alt="product image">
                </div>
                <div class="itemname">DELL  3.0</div>
                <div class="itemprice">Price:Rs.30,000 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/images/HPathlon.png"  alt="product image">
                </div>
                <div class="itemname">HP Athlon</div>
                <div class="itemprice">Price: Rs.25,000 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/images/infi.png"  alt="product image">
                </div>
                <div class="itemname">INFINIX</div>
                <div class="itemprice">Price: Rs.30,000 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/images/msibravo.png"  alt="product image">
                </div>
                <div class="itemname">MSI Bravo</div>
                <div class="itemprice">Price: Rs.50,000</div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/images/realmebook.png"  alt="product image">
                </div>
                <div class="itemname">Realme Laptop</div>
                <div class="itemprice">Price: 50,000 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/images/redmibook.png"  alt="product image">
                </div>
                <div class="itemname">Redmi Book</div>
                <div class="itemprice">Price: Rs.30,000/div>
             </div>
          </div>
          </div>        
          
        
      <div class="footer">
        Copyright &#169; 2023 KERA , Designed By Athmaj Venugopal
      </div>
    </div>
  </body>
</html>
```
People Page:
```
<style>
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color:black;
  color:white;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 10px;
  font-weight: bold;
  background-image: url("/static/images/kera.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 130px;
  padding-left:250px;
  color:white;
}



.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color:black;
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
  text-decoration:none;
  color: white;
}
h1 {
    color:white;
}

.content {
  display: block;
  width: 100%;
  background-color: rgb(48,48,48);
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color:rgb(48,48,48);
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
  font-family: Arial, Helvetica, sans-serif;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
  color:honeydew;
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
  background-color:black;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color:white;
}

</style>



<!DOCTYPE html>
<html lang="en">
  <head>
    <title>KERA</title>
    <link rel="stylesheet" href="./css/layout.css" />
     <link rel="icon" href="/static/images/kera.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/home/">Home</a></div>
        <div class="menuitem"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitem"><a href="/contactus/">Contact Us</a></div>
      </div>
      
      <div class="content">
        <div class="productcontent">
            <h1>Our Crew Memebers</h1>
                    <div class="productitems">
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="/static/images/sachin.jpeg" alt="people image">
                            </div>
                            <div class="itemname">Chief Executive Officer</div>
                            <div class="itemprice">Sachin Bansal</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="/static/images/amazon.jpeg" alt="people image">
                            </div>
                            <div class="itemname">Chief Financial Officer9</div>
                            <div class="itemprice">Jeff Bezoz</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="/static/images/mukesh.jpeg" alt="people image">
                            </div>
                            <div class="itemname">Chief Operating Officer</div>
                            <div class="itemprice">Mukesh Ambani</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="/static/images/nita.jpeg" alt="people image">
                            </div>
                            <div class="itemname">Chief Marketing Officer</div>
                            <div class="itemprice">Nita Ambani</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="/static/images/anil.jpeg" alt="people image">
                            </div>
                            <div class="itemname">Chief Technology Officer</div>
                            <div class="itemprice">Anil Ambani</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="/static/images/akash.jpeg" alt="people image">
                            </div>
                            <div class="itemname">President</div>
                            <div class="itemprice">Akash Ambani</div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="footer">
        Copyright &#169; 2023 KERA , Designed By Athmaj Venugopal
      </div>
    </div>
  </body>
</html>
```
Contact Us:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>KERA</title>
    <link rel="stylesheet" href="./css/layout.css" />
     <link rel="icon" href="/static/images/kera.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/home/">Home</a></div>
        <div class="menuitem"><a href="/products/">Products</a></div>
        <div class="menuitem"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
          <div class="us">
              <h1>
                  <u>Contact Us</u>
                </h1>
                <h2>For Enquiry</h2>
                        <h3>EMAIL : kera123@limited@gmail.com</h3>
                        <h3>NUMBER: +91 9361199777,+91 8535647625</h3>
                        <h3>ADDRESS: 12B,KERA,Kerala.</h3>
                        <h3>WEBSITE: Kera.com</h3>
          </div>
            </div>
            <div class="footer">
        Copyright &#169; 2023 KERA , Designed By Athmaj Venugopal
      </div>
    </div>
  </body>
</html>

<style>
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color:black;
  color:white;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 10px;
  font-weight: bold;
  background-image: url("/static/images/kera.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 130px;
  padding-left:250px;
  color:white;
}



.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color:black;
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
  text-decoration:none;
  color: white;
}
h1 {
    color:white;
}

.content {
  display: block;
  width: 100%;
  background-color: rgb(48,48,48);
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color:rgb(48,48,48);
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
  font-family: Arial, Helvetica, sans-serif;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
  color:honeydew;
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
  background-color:black;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color:white;
}

</style>
```

## OUTPUT:

### Home Page:

![home](https://user-images.githubusercontent.com/118753139/214310776-810587e8-e372-4bc2-864c-8dd60d912a07.png)

### Product Page:

![product](https://user-images.githubusercontent.com/118753139/214311105-c42e0d61-52ff-4f43-9bc8-475a97a59831.png)

### People Page:

![people](https://user-images.githubusercontent.com/118753139/214311261-32d11e66-997d-4c1d-8b1f-b3715730f6b4.png)

### Contact Us Page:

![contactus](https://user-images.githubusercontent.com/118753139/214311384-a95e3133-72c8-4f7b-afbe-f12325229e2d.png)


## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
