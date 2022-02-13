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

'''<!DOCTYPE html>
<html lang="en">
  <head>
    <title>BEAUTELLO</title>
    <link rel="stylesheet" href="layout.css"/>
    <link rel="icon" href="data:image/jpeg;base64,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" type="image/x-icon" />
  </head>

  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" h1ref="./css/layout.css" />
    <link rel="icon" href="data:image/jpeg;base64,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" type="image/x-icon" />

    
  </head>
  <style>
   {
    box-sizing: border-box;
    font-family :, Arial, Helvetica, sans-serif;
  }
  body {
    background-color: rgb(0, 0, 0);
    color: #ff9900;
  }
  .container {
    width: 1250px;
    margin-left: auto;
    margin-right: auto;
    border-width: 1px 1px 1px 1px;
    border-style: solid;
    box-shadow: 15px 15px 15px gray;
  }
  
  .banner {
    display: block;
    width: 100%;
    height: 600px;
    text-align: center;
    border-width: 0ch;
    font-size: 150px;
    background-image: url("https://www.itl.cat/pngfile/big/290-2906372_neon-lemon-girl-dream-fashion-pink-girly-wallpaper.jpg");
    background-size: 100% 100%;
    margin: 1px 1px 1px 1px;
    padding-top:0px;
    color: #0e0f0f;
  }
  
  .menu {
    display: block;
    width: 100%;
    height: 50px;
    font-size: larger;
    background-color: #0b3500;
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
    background-color: #054442;
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
    float: left;
    width: 400px;
    height: 300px;
    margin-left: 10px;
  }
  
  .contenttext {
    text-align: justify;
  }
  
  .productcontent {
    min-height: 800px;
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
    width: 60%;
    height: 450px;
    text-align: center;
  }
  
  .productitem img {
    width: 500px;
    height: 500px;
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
</style>

  <body>
    <div class="container">
      <div class="banner">BEAUTELLO</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <h3>CONTACT</h3> <br>
              email : lathikasunder11@gmail.com<br>
              mob   :  7550340307
          <img style="width:400px" src="https://media.glassdoor.com/l/6d/72/51/e7/the-marketing-team-at-topgolf.jpg" alt="img" />
          <div class="contenttext">
            I am digital marketer who is passinate about helping small business with 
            'out of the box' ideas to acquire new leads and customers leveraging digital 
            marketing technology . I have a background in the fasion industry in marketing 
            and merchanding with leading brands such as Tommy Hilfiger,J C Penney,and Li and Fung.
            I am a certified facilitator with ACTA certification from singapore WDA 
            I provide consulting,digital marketing and training services to companies to help them 
            make the most of digital marketing
            <br />
            Many consumers now discover beauty products on social media like instagram and youtube.
            so it's no suprise that both new and legancy brands are turning increasingly spending
            on digital media,in order to generate engagement and drive sales 
            <ul>
              <li style="font-family: cursive" >Beauty, to me ,is about being comfortable in your own skin.</li>
              <li style="font-family: cursive">Makeup is art .beauty is spirit</li>
              <li style="font-family: cursive">Skin first.makeup second.smile always</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 BEAUTELLO, Developed by Lathika Sunder
      </div>
    </div>
  </body>
</html>
##PRODUCT:

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>BEAUTELLO</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/beauty logo.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">BEAUTELLO</div>
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
                  <img src="https://i.pinimg.com/736x/e4/72/7e/e4727e9973f1178695cdfb944381b88c.jpg" style="size:15cm" alt="product1 image">
                  </div>
                  <div class="itemname"><h1>BEAUTELLO eyeliner</h1></div>
                  <div style="size: 40px"; class="itemprice">Price: Rs.1000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://mir-s3-cdn-cf.behance.net/project_modules/max_1200/bbca9876720185.5c7288938dc5a.jpg" style="size:15cm" alt="product2 image">
                  </div>
                  <div class="itemname"><h1>BEAUTELLO mascara</h1></div>
                  <div style="size: 40px"; class="itemprice">Price: Rs.1000.00</div>
              </div>

              <div class="productitem"> 
                <div class="itemimage">
                <img src="http://www.daniellindh.com/2017/wp-content/uploads/2017/01/lipstick-red-flowers-still-life-dolce-gabbana-daniel-lindh.jpg" style="size:15cm" alt="product3 image">
                </div>
                <div class="itemname"><h1>BEAUTELLO lipstick</h1></div>
                <div style="size: 40px"; class="itemprice">Price: Rs.1000.00</div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://i.pinimg.com/originals/21/e0/11/21e011bc0d8f701fb0d198d3c57784c3.jpg" style="size:15cm" alt="product4 image">
                </div>
                <div class="itemname"><h1>BEAUTELLO foundation</h1></div>
                <div style="size: 40px";class="itemprice">Price: Rs.1000.00</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="https://images.squarespace-cdn.com/content/v1/55f6788be4b04a24f1745947/1598882833674-TX4NFMQYSZPNMPCK34EN/product_photography_barcelona_Photographer_julia_325.jpg?format=1000w" style="size:15cm" alt="product5 image">
              </div>
              <div class="itemname"><h1>BEAUTELLO moisturizer</h1></div>
              <div style="size: 40px"; class="itemprice">Price: Rs.1000.00</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="https://ae04.alicdn.com/kf/H3266dac2aca24385b0a6285b08b0dc197.jpg" style="size:15cm" alt="product6 image">
              </div>
              <div class="itemname"><h1>BEAUTELLO concealer</h1></div>
              <div style="size: 40px"; class="itemprice">Price: Rs.1000.00</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="https://i.pinimg.com/736x/8a/96/99/8a96994295aff1a34ff40980bf134f5b.jpg" style="size:15cm" alt="product7 image">
              </div>
              <div class="itemname"><h1>BEAUTELLO primer</h1></div>
              <div style="size: 40px"; class="itemprice">Price: Rs.1000.00</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="https://mir-s3-cdn-cf.behance.net/projects/404/821d3290947291.Y3JvcCwyNTQxLDE5ODcsMzk2LDI2NA.jpg" style="size:15cm" alt="product8 image">
              </div>
              <div class="itemname"><h1>BEAUTELLO bronzer</h1></div>
              <div style="size: 40px"; class="itemprice">Price: Rs.1000.00</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="https://www.wallpaperflare.com/static/657/887/691/makeup-brush-rouge-pink-wallpaper.jpg" style="size:15cm" alt="product9 image">
              </div>
              <div class="itemname"><h1>BEAUTELLO blush</h1></div>
              <div style="size: 40px"; class="itemprice">Price: Rs.1000.00</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="https://media6.ppl-media.com/tr:h-750,w-750,c-at_max/static/img/product/138359/ny-bae-kohl-black-the-big-apple-of-my-eye_5_display_1630922214_c9e766bb.jpg" style="size:15cm" alt="product10 image">
              </div>
              <div class="itemname"><h1>BEAUTELLO eye kajal</h1></div>
              <div style="size: 40px"; class="itemprice">Price: Rs.1000.00</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="https://media.istockphoto.com/photos/cropped-view-of-woman-applying-lip-pencil-isolated-on-white-picture-id1043608406?k=20&m=1043608406&s=612x612&w=0&h=sezh845IPOmIanE7RKA8lVwJ2C6EmDAV9BJvxMUoXm4=" style="size:15cm" alt="product11  image">
              </div>
              <div class="itemname"><h1>BEAUTELLO lipliner</h1></div>
              <div style="size: 80px"; class="itemprice">Price: Rs.1000.00</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="https://i.pinimg.com/originals/ff/ee/60/ffee60005f44a9755aafdfb625069d70.png" style="size:15cm" alt="product12  image">
              </div>
              <div class="itemname"><h1>BEAUTELLO hydrating serum</h1></div>
              <div style="size: 80px"; class="itemprice">Price: Rs.1000.00</div>
            </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft BEAUTELLO, Developed by Lathika Sunder
      </div>
    </div>
  </body>
</html>

##PEOPLE:

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>BEAUTELLO</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/beauty logo.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">BEAUTELLO</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="peoplecontent">    
          <h1>Our Team</h1>
          <div class="peopleitems">
              <div class="peopleitem"> 
                  <div class="peopleimage">
                  <img style="align-items: center;" src="https://media.istockphoto.com/photos/passport-picture-of-a-smiling-turkish-businesswoman-picture-id856599656?k=20&m=856599656&s=612x612&w=0&h=bIJ3aCa4vWB_-jFRTiPffYyUpw5uPpIHGDHEs4bjEqg=" alt="people1 image">
                  </div>
                  <div class="itemname">MIA BELLA</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://media.istockphoto.com/photos/portrait-of-a-smiling-woman-in-a-blue-shirt-picture-id515630181?k=20&m=515630181&s=612x612&w=0&h=XJnIoZkvMJiL__5OOJikWzgi18u7KklNPl2HfK4KeRg="  alt="people2 image">
                  </div>
                  <div class="itemname">TRES BEAUX</div>
              </div>

              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://media.istockphoto.com/photos/passport-photo-of-a-young-arabic-woman-picture-id564567808?k=20&m=564567808&s=612x612&w=0&h=gbgZ_h49Zu1Og5iwA3EB13T3cianAxk1yuUNZtkSYPs="  alt="people3 image">
                </div>
                <div class="itemname">BELLE CURIS</div>
              </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft BEAUTELLO, Developed by LATHIKA SUNDER
      </div>
    </div>
  </body>
</html>'''

## OUTPUT:
![output](./productwebsite.png)

<<<<<<< HEAD
=======
### Home Page:

<<<<<<< HEAD
![output](./images?productwebsite.png)
>>>>>>> 6c3e6b8e5abddf9b876716510b84fb0a561a89e4
=======
![output](./productwebsite.png)
>>>>>>> 917dacc3a223694b9c34aca79fb61d2d3d759c83

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
