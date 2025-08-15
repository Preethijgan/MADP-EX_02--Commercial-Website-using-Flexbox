# Ex02 Commercial Website
## Date: 11-08-2025

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM

index.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Handmade Crafts</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Handmade Crafts</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#products">Products</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="about">
        <h2>About Us</h2>
        <p>We create beautiful handmade crafts including jewelry, pottery, and home decor items. Each piece is crafted with care, creativity, and love.</p>
    </section>

    <section id="products">
        <h2>Our Products</h2>

        <h3>Jewelry</h3>
        <div class="product-container">
            <div class="product">
                <img src="images/necklace.jpeg" alt="Jewelry 1">
                <p>Elegant Necklace</p>
            </div>
            <div class="product">
                <img src="images/bracelet.jpeg" alt="Jewelry 2">
                <p>Handmade Bracelet</p>
            </div>
            <div class="product">
                <img src="images/earrings.jpeg" alt="Jewelry 3">
                <p>Beaded Earrings</p>
            </div>
        </div>

        <h3>Pottery</h3>
        <div class="product-container">
            <div class="product">
                <img src="images/ceramic_vase.jpeg" alt="Pottery 1">
                <p>Ceramic Vase</p>
            </div>
            <div class="product">
                <img src="images/clay_mug.jpeg" alt="Pottery 2">
                <p>Clay Mug</p>
            </div>
            <div class="product">
                <img src="images/plate.jpeg" alt="Pottery 3">
                <p>Decorative Plate</p>
            </div>
        </div>

        <h3>Home Décor</h3>
        <div class="product-container">
            <div class="product">
                <img src="images/wall_hanging.jpeg" alt="Home Decor 1">
                <p>Wall Hanging</p>
            </div>
            <div class="product">
                <img src="images/candle_holder.jpeg" alt="Home Decor 2">
                <p>Candle Holder</p>
            </div>
            <div class="product">
                <img src="images/table_centerpiece.jpeg" alt="Home Decor 3">
                <p>Table Centerpiece</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: handmadecrafts@gmail.com</p>
        <p>Phone: +91 9876543210</p>
    </section>

    <footer>
        <p>&copy; Preethi J (212223220080)</p>
    </footer>
</body>
</html>

```

style.css

```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    background-image: url(https://i.pinimg.com/1200x/c1/83/77/c183772756616612be24df7dbd016a05.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    
}

header {
    background: #c97c5d;
    color: white;
    padding: 15px 20px;
    text-align: center;
}

nav a {
    color: white;
    margin: 0 10px;
    text-decoration: none;
}

section {
    padding: 20px;
    text-align: center;
}

.product-container {
    display: flex;
    justify-content: center;
    gap: 15px;
    flex-wrap: wrap;
    margin-bottom: 30px;
}

.product {
    background: #f5f5f5;
    padding: 10px;
    border-radius: 8px;
    width: 150px;
    text-align: center;
}

.product img {
    width: 100%;
    border-radius: 8px;
    
}

footer {
    background: #c97c5d;
    color: white;
    text-align: center;
    padding: 10px;
}


```



## OUTPUT

<img width="1919" height="1079" alt="Screenshot 2025-08-15 220551" src="https://github.com/user-attachments/assets/e1748216-d367-4980-8307-1cce17412a29" />
<img width="1919" height="1079" alt="Screenshot 2025-08-15 220558" src="https://github.com/user-attachments/assets/7b8a2be0-b652-4361-b817-5b90fc062c69" />
<img width="1919" height="1079" alt="Screenshot 2025-08-15 220607" src="https://github.com/user-attachments/assets/0a0cec4c-caf1-444c-b067-7230c31f76a8" />
<img width="1919" height="1079" alt="Screenshot 2025-08-15 220615" src="https://github.com/user-attachments/assets/bfe4d909-e928-4cc1-98a4-75c945f1469c" />












## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
