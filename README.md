# Ex.07 Restaurant Website
# Date:16/11/2024
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```python

MAIN PAGE:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>restaurant</title>
</head>
<style>
    body{
        background-image: url("c:\\Users\\admin\\Downloads\\main.webp");
    }
    .ref{
        position: absolute;
        font-size: 400%;
        top: 55%;
        left: 5%;
    }
    .ref1 a{
        font-size: 142%;
        position: relative;
        top: 420px;
    }
    header{
        font-size: 568%;
    }
    footer{
        background-color: black;
        position: relative;
        top: 615px;
        font-size: 70px;
        left:8px
    }

</style>
<body>
    <center>
        <header style="color: rgb(245, 59, 59);">
            ℌѦʊη†℮∂ ⚠️ ґ℮s†Ѧʊґ℮η†
        </header>
        <div class="ref">
        <a>†</a>
        <a href="file:///C:/Users/admin/Desktop/html/home.html" style="color: aliceblue;">HOME</a>
        <a>†</a>
        <a href="file:///C:/Users/admin/Desktop/html/menu.html" style="color: rgb(255, 0, 34);">MENU</a>
        <a>†</a>
        <a href="file:///C:/Users/admin/Desktop/html/about.html" style="color: aliceblue;">ABOUT</a>
        <a>†</a>
        <a href="file:///C:/Users/admin/Desktop/html/contact.html" style="color: rgb(255, 0, 34);">CONTACT</a>
        <a>†</a>
        </div>
        <footer style="color: rgb(255, 255, 255);">
            KISHORE
        </footer>
    </center>
   
</body>
</html>


HOME PAGE CODE:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>home</title>
</head>

<style>
    body{
        background-image: url("c:\\Users\\admin\\Downloads\\hauntesss.jpg");
        background-repeat: no-repeat;
        background-size: 100%;
    }
    header{
        font-size: 620%;
    }
    .content{
        font-size: larger;
        font-family: cursive;
    }
    .content p{
        position: relative;
        top: 80px;
    }
    footer{
        font-size: 420%;
        position: relative;
        top: 250px;
    }
</style>
<body>
    <center>
        <header style="color: crimson;">
            ℌѦʊη†℮∂ ⚠️ ґ℮s†Ѧʊґ℮η†
        </header>

        <div class="content" style="color: #ffffff;">
        <p>Welcome to The Haunted Restaurent: A Dining Experience Like No Other
           Step into a world where the past lingers and the dining experience is far from ordinary. Nestled in the heart of Chennai, The Haunted Tavern invites you to enjoy delicious food and drink surrounded by eerie tales, ghostly encounters, and the kind of atmosphere that leaves you questioning what’s real and what’s supernatural.
           A Spine-Chilling History This historic restaurant is built on the grounds of a centuries-old mansion, once home to legendary figure. Over the years, it has earned a reputation for being one of the most haunted locations in the area. From the flickering lights to the mysterious sounds echoing through the halls, you’re bound to feel the presence of spirits who never quite left.
           An Unearthly Atmosphere The moment you step inside, you’ll be transported to another time. Dim lighting, vintage décor, and walls lined with photographs of the building’s mysterious past create an atmosphere filled with intrigue. Every corner tells a story of the ghosts that roam within, waiting for you to discover their tales.
           Gastronomic Delights with a Twist Our menu offers a unique blend of contemporary cuisine with a spooky twist. Whether you’re feasting on a hearty entrée or indulging in our signature haunted cocktails, you’ll enjoy flavors that are both comforting and unexpected. Don’t miss our “Phantom Specials,” seasonal dishes inspired by the mysterious spirits that haunt our halls.
           Ghostly Encounters For those seeking a more thrilling experience, we offer ghost tours and paranormal investigations. Join our expert guides as they take you on a journey through the haunted halls, sharing chilling stories of ghostly apparitions, unexplained phenomena, and eerie occurrences that will keep you on the edge of your seat.
           Reserve Your Table Today Dare to dine where the past refuses to rest.</p>
        </div>
        <footer>
            <a href="file:///C:/Users/admin/Desktop/html/kitchen%20menu.html" style="color: #e90606;">BACK</a>
        </footer>
    </center>

</body>
</html>


ABOUT PAGE CODE:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>administartion</title>
</head>

<style>
    body{
        background-color: rgb(0, 0, 0);
    }
    header{
        font-size: 450%;
    }
    footer{
        font-size: 350%;
    }
    .content{
        color: rgb(255, 255, 255);
    }
    h1{
        color: #e90606;
    }
    h2{
        color: chartreuse;
    }
</style>

<body>
    <center>
    <header style="color: #e90606;">
        ℌѦʊη†℮∂ ⚠️ ґ℮s†Ѧʊґ℮η†
    </header>
    <h2 style="font-size: 72px;">OUR BACKBONES</h2>

    <div class="content">
    <img src="c:\\Users\\admin\\Downloads\\chef1.webp" width="300" height="300">
    <h1>Chef Arnold</h1>
    <p style="font-size: x-large;">'CHEIF CHEF'</p>
    <P style="font-size: x-large;">Head of the kitchen. Responsible for menu creation, kitchen management, and overall operations.</P>

    <img src="c:\\Users\\admin\\Downloads\\chef2.webp" width="300" height="300">
    <h1>Chef Rooney</h1>
    <p style="font-size: x-large;">'EXECUTIVE CHEF'</p>
    <P style="font-size: x-large;">Second-in-command. Assists the Cheif Chef in managing the kitchen and oversees day-to-day operations.</P>

    <img src="c:\\Users\\admin\\Downloads\\chef3.webp" width="300" height="300">
    <h1>Chef Bayley</h1>
    <p style="font-size: x-large;">'PASTRY CHEF'</p>
    <P style="font-size: x-large;">Head of the bakery and pastery.Manages desserts and baked goods.</P>
    
    <img src="c:\\Users\\admin\\Downloads\\chef4.webp" width="300" height="300">
    <h1>Chef Grylls</h1>
    <p style="font-size: x-large;">'JUNIOR CHEF'</p>
    <P style="font-size: x-large;">Works under the Chef de Partie to learn and assist in different stations.</P>

    <img src="c:\\Users\\admin\\Downloads\\chef5.webp" width="300" height="300">
    <h1>Chef Johnny</h1>
    <p style="font-size: x-large;">'STATION CHEF'</p>
    <P style="font-size: x-large;">In charge of a specific section of the kitchen (e.g., grill, pastry, or sauté station).</P>
    
    <img src="c:\\Users\\admin\\Downloads\\chef6.webp" width="300" height="300">
    <h1>Chef Angeline</h1>
    <p style="font-size: x-large;">'SAUCE CHEF'</p>
    <P style="font-size: x-large;">Specializes in making sauces, stews, and sautéed dishes.</P>
    </div>
       
    
    <footer>
        <a href="file:///C:/Users/admin/Desktop/html/kitchen%20menu.html" style="color: #e90606;">BACK</a>
    </footer>
    </center>
</body>
</html>


MENU PAGE CODE:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <center>
        
        </center>
        <div>
    <title>Restaurant Menu</title>
        </div>

    <style>
        body{
            background-color: #000000;
        }
     
    
        .menu-container {
            width: 80%;
            margin: 50px auto;
            background-color: rgba(255, 255, 255, 0.9);
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            color: #ffffff;
        }

        header {
            text-align: center;
            padding: 20px 0;
            color: #e90606;
            background-color: #000000;
            border-radius: 15px 15px 0 0;
        }

        header h1 {
            margin: 0;
            font-size: 78px;
        }

        footer{
            font-size: 420%;
        }

        h2 {
            text-align: center;
            color: #000000;
            border-bottom: 2px solid #817c7c;
            font-size: 56px;
            margin-bottom: 20px;
        }

        .menu-item {
            display: flex;
            justify-content: space-between;
            margin-bottom: 20px;
            align-items: center;
        }

        .menu-item img {
            width: 150px;
            height: 100px;
            border-radius: 10px;
            object-fit: cover;
        }

        .menu-item-name {
            font-size: 34px;
            font-weight: bold;
            color: #7900e3;
        }

        .menu-item-price {
            font-size: 28px;
            color: #e74c3c;
        }

    </style>
</head>
<body>
    <center>

<header>
    <h1>ℌѦʊη†℮∂ ⚠️ ґ℮s†Ѧʊґ℮η†</h1>    
</header>
<div class="menu-container">

    <div class="menu-section">
        <h2>STARTERS</h2>
        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\tikka.jpg">
            <p class="menu-item-name">Chicken Tikka</p>
            <p class="menu-item-price">₹199</p>
        </div>

        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\thandhoori.jpg">
            <p class="menu-item-name">Chicken Tandhoori</p>
            <p class="menu-item-price">₹299</p>
        </div>

        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\lollipop.jpg">
            <p class="menu-item-name">Chicken Lollipop</p>
            <p class="menu-item-price">₹199</p>
        </div>
        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\manch.jpg">
            <p class="menu-item-name">Chicken Manchurian</p>
            <p class="menu-item-price">₹299</p>
        </div>
    </div>

<center>
    <img src="c:\Users\admin\Downloads\h1.avif" width="1200" height="700">
    </center>
    <div class="menu-section">
        <h2>MAIN COURSES</h2>
        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\briyani.jpg">
            <p class="menu-item-name">Chicken Briyani</p>
            <p class="menu-item-price">₹199</p>
        </div>
        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\fried rice.webp">
            <p class="menu-item-name">Fried Rice</p>
            <p class="menu-item-price">₹199</p>
        </div>
        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\meals.webp">
            <p class="menu-item-name">Chicken Meals</p>
            <p class="menu-item-price">₹199</p>
        </div>
        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\shawarma-biryani.jpg">
            <p class="menu-item-name">Shawarma Briyani</p>
            <p class="menu-item-price">₹299</p>
            </div>
    </div>

<center>
    <img src="c:\Users\admin\Downloads\h2.jpg">
</center>
    <div class="menu-section">
        <h2>DESSERTS</h2>
        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\brownie.jpg">
            <p class="menu-item-name">Brownie</p>
            <p class="menu-item-price">₹99</p>
        </div>
        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\cakes.avif">
            <p class="menu-item-name">Cakes</p>
            <p class="menu-item-price">₹149</p>
        </div>
        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\ice cream.jpg">
            <p class="menu-item-name">Ice Cream</p>
            <p class="menu-item-price">₹199</p>
        </div>
        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\kunafa.jpg">
            <p class="menu-item-name">Kunafa</p>
            <p class="menu-item-price">₹299</p>
        </div>
    </div>
</div>
<footer>
    <a href="file:///C:/Users/admin/Desktop/html/kitchen%20menu.html" style="color: #e90606;">BACK</a>
</footer>
    </center>

</body>
</html>


CONTACT PAGE CODE:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>contact</title>
</head>
<style>
    header{
        font-size:80px;
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    }
    .address{
        font-size: x-large;
    }
    .contact{
        font-size: larger;
        font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    }
    footer{
        font-size: 360%;
    }
</style>
<body>
    <center>
        <header style="color: rgb(176, 20, 20);">ℌѦʊη†℮∂~ґ℮s†Ѧʊґ℮η†</header>
        <img src="c:\\Users\\admin\\Downloads\\skull.png" width="200" height="200">
        <div class="address">
        <p>No.0 Dubai Cross Street opp to TVK vijay house</p>
        <p>Chettipedu,Chennai,608652,Tamilnadu</p>
        </div>
        <img src="c:\\Users\\admin\\Downloads\\more.jpg" width="150" height="150">
        <div class="contact">
        <p>E-mail:hauntedrestaurentchennai@gmail.com</p>
        <p>Phone:+9786577281</p>
        <p>Tel:+9360865567</p>
        </div>
        <footer>
            <a href="file:///C:/Users/admin/Desktop/html/kitchen%20menu.html" style="color: #e90606;">BACK</a>
        </footer>
    </center>
    
</body>
</html>

```
# OUTPUT:
MAIN PAGE:
![Screenshot 2024-12-08 161641](https://github.com/user-attachments/assets/b8e32d55-cfa2-43d8-8fe2-c6bc1cdcd978)
HOME PAGE:
![Screenshot 2024-12-08 161830](https://github.com/user-attachments/assets/0b372307-ccb0-45ef-8fda-f4c68c753578)
ADMIN PAGE:
![Screenshot 2024-12-08 161917](https://github.com/user-attachments/assets/7e16cd7f-3da6-46bc-98f2-5effbcb05fb4)
![Screenshot 2024-12-08 161933](https://github.com/user-attachments/assets/486cd8f1-c098-42f5-b6e6-abcfb97274d1)
![Screenshot 2024-12-08 161952](https://github.com/user-attachments/assets/fc28fe86-0e73-4970-b10d-7abaa9e5f8cd)
![Screenshot 2024-12-08 162005](https://github.com/user-attachments/assets/ac548ed6-00f8-4288-a7ca-282b9bbd3b63)
![Screenshot 2024-12-08 162014](https://github.com/user-attachments/assets/8c15a817-789b-4c0c-9bed-81ed3eda0b9f)
MENU PAGE:
![Screenshot 2024-12-08 162055](https://github.com/user-attachments/assets/c43af274-c170-4e1a-a2eb-095749021fce)
![Screenshot 2024-12-08 162112](https://github.com/user-attachments/assets/195f70ea-f09f-438a-88e1-776e4d29f70a)
![Screenshot 2024-12-08 162123](https://github.com/user-attachments/assets/808b2103-21eb-433a-ade9-994618e89f48)
CONTACT PAGE:
![Screenshot 2024-12-08 162137](https://github.com/user-attachments/assets/22b8d27e-b1df-4584-b06b-5052fe25d804)
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
