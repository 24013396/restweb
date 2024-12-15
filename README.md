# Ex.07 Restaurant Website
## Date:15-12-2024

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

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Little Lemon Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="background"></div>

    <nav class="navbar">
        <div class="logo">Little Lemon Restaurant</div>
        <img src="Images/Asset 7@4x.png" alt="">
        <ul class="nav-links">
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#menu">Menu</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <div class="bg">
        <div class="menu-container">
            <div class="card">
                <img src="biryani.jpeg" alt="biryani">
                <div class="card-content">
                    <h3>biryani</h3>
                    <p>chicken biryani</p>
                    <span class="price">Rs. 30</span>
                </div>
            </div>
            
            <div class="card">
                <img src="dal rice.jpeg"Dal Rice">
                <div class="card-content">
                    <h3>Dal Rice</h3>
                    <p>Traditional Indian Dal and Rice.</p>
                    <span class="price">Rs. 50</span>
                </div>
            </div>
        
            <div class="card">
                <img src="vada.jpeg" alt="Vada">
                <div class="card-content">
                    <h3>Vada</h3>
                    <p>Crispy and Crunchy Vada.</p>
                    <span class="price">Rs. 10</span>
                </div>
            </div>
        </div>

        <div class="menu-container">
            <div class="card">
                <img src="coffee.jpeg" alt="Coffee">
                <div class="card-content">
                    <h3>Coffee</h3>
                    <p>A delightful Coffee.</p>
                    <span class="price">Rs. 10</span>
                </div>
            </div>
            
            <div class="card">
                <img src="chapathi.jpeg" alt="Chappathi">
                <div class="card-content">
                    <h3>Chappathi</h3>
                    <p>Soft Chapathi.</p>
                    <span class="price">Rs. 15</span>
                </div>
                <div class="card">
                    <img src="noddle.jpeg" alt="Noodles">
                    <div class="card-content">
                        <h3> noodles</h3>
                        <p>crispy noodles</p>
                        <span class="price">Rs. 90</span>
                    </div>
            </div>

            <div class="card">
                <img src="sandwich.jpeg" alt="sandwich">
                <div class="card-content">
                    <h3>sandwich</h3>
                    <p>veg sandwich</p>
                    <span class="price">Rs. 70</span>
                </div>

                <div class="card">
                    <img src="pulihora.jpeg" alt="">
                    <div class="card-content">
                        <h3>pulihora</h3>
                        <p>tasty pulihora</p>
                        <span class="price">Rs. 110</span>
                    </div>

                    <div class="card">
                        <img src="burger.jpeg" alt="">
                        <div class="card-content">
                            <h3>burger</h3>
                            <p>pannir burger</p>
                            <span class="price">Rs. 150</span>
                        </div>
        
            <div class="card">
                <img src="" alt="">
                <div class="card-content">
                    <h3></h3>
                    <p></p>
                    <span class="price">Rs. 120</span>
                </div>
            </div>
        </div>
    </div>
    
</body>
</html>

admin.html

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chefs</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Caveat:wght@700&family=Pacifico&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background-color:yellow;
        }

        header {
            text-align: center;
            background-color: #0e6ff5;
            padding: 20px 0;
        }

        header h1 {
            font-family: "Caveat", cursive;
            font-size: 50px;
            color: white;
            margin: 0;
        }


        .chefs-container {
            display: flex;
            gap: 20px;
            padding: 40px;
            margin: auto;
        }

        .chef-card {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            text-align: center;
        }

        .chef-card:hover {
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }

        .chef-card img {
            width: 100%;
            object-fit: contain; 
            max-height: 300px; 
        }

        .chef-details {
            padding: 20px;
        }

        .chef-details h1 {
            font-size: 20px;
            color: rgb(181, 101, 29);
            margin: 10px 0;
        }

        .chef-details h2,
        .chef-details h3 {
            font-size: 16px;
            color: rgb(85, 85, 85);
            margin: 5px 0;
        }

       
        footer {
            text-align: center;
            background-color:aliceblue;
            color:brown;
            padding: 10px 0;
            margin-top: 20px;
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>

  
    <header>
        <h1>Cooking chef</h1>
    </header>

    
    <div class="chefs-container">
        <div class="chef-card">
            <img src="me.jpg" alt="Shaik hazeedmasthan">
            <div class="chef-details">
                <h1>shaik Hazeedmasthan</h1>
                <h2>CEO</h2>
                
            </div>
        </div>
        
        <div class="chef-card">
            <img src="manish.jpeg" alt="Manish Mehrotra">
            <div class="chef-details">
                <h1>Manish Mehrotra</h1>
                <h2>Designation: Executive Chef</h2>
                <h3>Experience: 7 years</h3>
            </div>
        </div>
        <div class="chef-card">
            <img src="sanjeev.jpg" alt="Sanjeev Kapoor">
            <div class="chef-details">
                <h1>Sanjeev Kapoor</h1>
                <h2>Designation: celebrity Chef</h2>
                <h3>Experience: 2 years</h3>
            </div>
        </div>
        <div class="chef-card">
            <img src="vikkas.jpeg" alt="Vikas Khanna">
            <div class="chef-details">
                <h1>Vikas Khanna</h1>
                <h2>Designation: Michelin Star Chef, Restaurateur, Author</h2>
                <h3>Experience: 5 years</h3>
            </div>
        </div>
        <div class="chef-card">
            <img src="ranveeer.jpeg" alt="Ranveerbrar">
            <div class="chef-details">
                <h1>Miss Cheruba</h1>
                <h2>Designation:Celebrity Chef, Restaurateur, Television Host</h2>
                <h3>Experience: 3 years</h3>
            </div>
        </div>
        
       
    <footer>
        <p>&copy; 2024 Foodie's Paradise. All rights reserved.</p>
    </footer>

</body>
</html>

style.css

@import url('https://fonts.googleapis.com/css2?family=Delius&family=Pacifico&family=Quicksand:wght@300..700&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: "Quicksand", sans-serif;
    font-optical-sizing: auto;
    font-weight: 10;
    font-style: bold;
}

.background {
    position: fixed;
    inset: 0;
    background-image: url("https://wallpaperboat.com/wp-content/uploads/2020/02/table-03.jpg");
    background-size: cover;
    background-position: center;
    z-index: -1;
    filter: blur(4px);
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #FFC20D;
    padding: 10px 20px;
}

.navbar img{
    display: flex;
    height: 70px;
    width: 40px;
}

.navbar .logo {
    color: #028940;
    font-size: 3em;
    font-weight: bold;
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 15px;
}

.nav-links li {
    display: inline;
    font-size: 1.5em;
}

.nav-links a {
    color: green;
    text-decoration: none;
    padding: 8px 15px;
    transition: background 0.3s;
}

.nav-links a:hover {
    background-color: #ffffffbe;
    border-radius: 4px;
}

.menu-container {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    padding: 20px;
    margin-top: 60px;
    justify-content: center;
}

.card {
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    overflow: hidden;
    width: 300px;
    transition: transform 0.3s;
}

.card:hover {
    transform: scale(1.05);
}

.card img {
    width: 100%;
    height: 150px;
    object-fit: cover;
}

.card-content {
    padding: 15px;
    text-align: center;
}

.card-content h3 {
    font-size: 1.25em;
    margin-bottom: 10px;
    color: #333;
}

.card-content p {
    font-size: 0.9em;
    color: #777;
    margin-bottom: 10px;
}

.price {
    display: block;
    font-size: 1.1em;
    font-weight: bold;
    color: #e67e22;
}


```

## OUTPUT:
![alt text](<Screenshot 2024-12-15 210616.png>)
![alt text](<Screenshot 2024-12-15 210704.png>)
![alt text](<Screenshot 2024-12-15 210744.png>)
![alt text](<Screenshot 2024-12-15 210835.png>)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
