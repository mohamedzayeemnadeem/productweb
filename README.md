# Product Company Website
## AIM:
To develop a static company website to display the sale of products.

## Design Steps:

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

## Code:
```
home.html

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>MUSIC WEBSITE</title>
    <link rel="stylesheet" href="../css/layout.css" />
    <link rel="icon" href="/static/images/music.jpg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">MUSIC</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Product</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./images/product.png" alt="Image" />
          <div class="contenttext">
            Welcome to MUSIC WEBSITE!
            Music is one of the many joys in life. It brings people together, 
            can make or break your mood, 
            remind you of a specific memory or time in your life, and make us dance.
            So whether you require tunes to work and keep you focused or when you are out for a drive,
            clearing your head, there are numerous music streaming services available today. 
            <br />
            We've listed services here with completely free tiers, 
            though you can upgrade to a higher level of service to remove ads,
            increase the size of the music library, allow more skips, or improve stream quality in bitrate. 
           
            <ul>
              <li>Simple to listen, easier to use</li>
              <li>Note worthy website</li>
              <li>Anywhere, anytime access</li>
            </ul>
          </div>
        </div>
    </div>
  </body>
</html>
product.html

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>MUSIC WEBSITE</title>
    <link rel="stylesheet" href="../css/layout.css" />
    <link rel="icon" href="/static/images/music.jpg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">MUSIC WEBSITE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/product.html">Products</a></div>  
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Music product</h1>
          <div class="productitems">

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/spotify.png" alt="product image">
                  </div>
                  <div class="itemname">spotify</div>
                  <div class="itemprice">Price:Rs.1,00,000</div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/Apple Music.png"  alt="product image">
                  </div>
                  <div class="itemname">Apple Music</div>
                  <div class="itemprice">Price:Rs.1,20,000</div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/wynk.png"  alt="product image">
                  </div>
                  <div class="itemname">wynk</div>
                  <div class="itemprice">Price: Rs.10,00,000</div>
              </div>

            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/images/juckbox.png"  alt="product image">
              </div>
              <div class="itemname">juckbox</div>
              <div class="itemprice">Price: Rs.20,00,000</div>
          </div>

          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/images/Gaana.png"  alt="product image">
            </div>
            <div class="itemname">Gaana</div>
            <div class="itemprice">Price: Rs.12,00,000 </div>
        </div>

        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/images/Google Play Music.png"  alt="product image">
          </div>
          <div class="itemname">Google Play Music</div>
          <div class="itemprice">Price: Rs.5,00,000</div>
      </div>

      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/images/orange.png"  alt="product image">
        </div>
        <div class="itemname">orange</div>
        <div class="itemprice">Price: Rs.1,20,000 </div>
    </div>

    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/images/amazonmusic.png"  alt="product image">
      </div>
      <div class="itemname">amazonmusic</div>
      <div class="itemprice">Price: Rs.19,90,080</div>
    </div>

    <div class="productitem"> 
       <div class="itemimage">
       <img src="/static/images/youtube.png"  alt="product image">
       </div>
       <div class="itemname">youtube</div>
       <div class="itemprice">Price: Rs.3,00,000 </div>
      </div>
    </div>
  </div>        
  </div>
</html>
people.html

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>MUSIC WEBSITE</title>
    <link rel="stylesheet" href="../css/layout.css"/>
    <link rel="icon" href="/static/images/music.jpg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">MUSIC WEBSITE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Product</a></div>  
        <div class="menuitemselected"><a href ="/static/people.html"></a>People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact</a></div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/images/AniruthRavichandran.jpg"  alt="product image">
      </div>
         <div class="itemname">Singer
           <br>
           (AniruthRavichandran)
         </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/images/ar.jpg"  alt="product image">
      </div>
         <div class="itemname">Singer
           <br>
           (A.R.Rahman)
         </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/images/jonita.jpg"  alt="product image">
      </div>
         <div class="itemname">Singer <br>(Jonitogandhi)</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/images/swea.jpg"  alt="productimage">
      </div>
         <div class="itemname">Singer <br> (Sweetha)</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/images/u1.jpg"  alt="product image">
      </div>
         <div class="itemname">Singer <br>Yuvan shankar raja</div>
      </div>
  </body>
</html>
#contact.html

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>MUSIC WEBSITE</title>
    <link rel="stylesheet" href="../css/layout.css" />
    <link rel="icon" href="/static/images/music.jpg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">MUSIC WEBSITE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/product.html">Product</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contact.html">Contact</a></div>
      </div>
      <div class="content">
          <ul>
              <li>Address:CHENNAI<br></li>
              <li>Contact:8263322458;<br></li>
              <li>nmzayeem@gmail.com<br></li>
              <br>VERIFIED*
          </ul>    
        </div>
    </div>
    </div>
    </div>
  </body>
</html> 
```
## Output:


![Screenshot (136)](https://user-images.githubusercontent.com/119476069/215671448-b6bb25c4-071b-4aed-815a-f5246828f698.png)

![Screenshot (138)](https://user-images.githubusercontent.com/119476069/215671475-ba97057c-06ce-48dc-b615-f8bd4a320963.png)

![Screenshot (140)](https://user-images.githubusercontent.com/119476069/215671503-133931f6-71fe-42b4-b64c-60f535427cb8.png)

![Screenshot (143)](https://user-images.githubusercontent.com/119476069/215671530-a9e9770b-09a6-4d34-bf25-bdde3bce5145.png)

## Result:
The program for designing company website for sale of products using HTML and CSS is completed successfully.
