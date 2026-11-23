
# GRAND PLAZA MALL
### Shopping Mall Website Using HTML Frames

**Developed by:** Jayapradan M  
**Register Number:** 2122242420061

## Technologies Used
- HTML
- CSS
- Frameset and Frame

## 1. index.html

```html
<!DOCTYPE html>
<html>
<head>
    <title>Grand Plaza Mall</title>
</head>

<frameset rows="20%,80%">
    <frame src="header.html" name="header">

    <frameset cols="25%,75%">
        <frame src="navigation.html" name="navigation">
        <frame src="home.html" name="content">
    </frameset>
</frameset>

</html>
```

## 2. header.html

```html
<!DOCTYPE html>
<html>
<head>
<style>
body {
    background-color: #14213d;
    color: white;
    text-align: center;
    font-family: Arial;
}
h1 {
    padding-top: 15px;
}
p {
    color: orange;
}
</style>
</head>
<body>
    <h1>GRAND PLAZA MALL</h1>
    <p>SHOP • DINE • ENTERTAIN</p>
</body>
</html>
```

## 3. navigation.html

```html
<!DOCTYPE html>
<html>
<head>
<style>
body {
    background-color: #eeeeee;
    font-family: Arial;
}
h2 {
    background-color: orange;
    padding: 15px;
    text-align: center;
}
a {
    display: block;
    padding: 15px;
    margin: 10px;
    background-color: white;
    color: black;
    text-decoration: none;
}
a:hover {
    background-color: #14213d;
    color: white;
}
</style>
</head>
<body>
    <h2>MALL DIRECTORY</h2>

    <a href="home.html" target="content">Home</a>
    <a href="fashion.html" target="content">Fashion & Apparel</a>
    <a href="food.html" target="content">Food Court</a>
    <a href="cinema.html" target="content">Cinema</a>
    <a href="contact.html" target="content">Contact Us</a>
</body>
</html>
```

## 4. home.html

```html
<!DOCTYPE html>
<html>
<body style="background-color:#f5f5f5;
font-family:Arial; text-align:center;">

<h1>Welcome to Grand Plaza Mall</h1>
<h3>Your Happy Place for Shopping & More</h3>
<p>Discover the latest trends, enjoy delicious food,
and experience blockbuster movies.</p>
<p>Everything you need under one roof!</p>

</body>
</html>
```

## 5. fashion.html

```html
<!DOCTYPE html>
<html>
<body style="background-color:#f5f5f5;
font-family:Arial; text-align:center;">

<h1>Fashion & Apparel</h1>
<p>Explore the latest fashion trends.</p>
<p>Clothing, footwear and accessories for everyone.</p>

<img src="images/fashion.jpg" width="450" height="250">

</body>
</html>
```

## 6. food.html

```html
<!DOCTYPE html>
<html>
<body style="background-color:#f5f5f5;
font-family:Arial; text-align:center;">

<h1>Food Court</h1>
<p>Enjoy delicious food and beverages.</p>

<img src="images/food.jpg" width="450" height="250">

</body>
</html>
```

## 7. cinema.html

```html
<!DOCTYPE html>
<html>
<body style="background-color:#f5f5f5;
font-family:Arial; text-align:center;">

<h1>Cinema</h1>
<p>Watch the latest blockbuster movies.</p>

<img src="images/cinema.jpg" width="450" height="250">

</body>
</html>
```

## 8. contact.html

```html
<!DOCTYPE html>
<html>
<body style="background-color:#f5f5f5;
font-family:Arial; text-align:center;">

<h1>Contact Us</h1>
<p>Email: info@grandplazamall.com</p>
<p>Phone: +91 98765 43210</p>

</body>
</html>
```

## Project Structure

```text
Shopping-Mall-Website/
│
├── index.html
├── header.html
├── navigation.html
├── home.html
├── fashion.html
├── food.html
├── cinema.html
├── contact.html
│
└── images/
    ├── fashion.jpg
    ├── food.jpg
    └── cinema.jpg
```

---

## Output:
<img width="1531" height="778" alt="image" src="https://github.com/user-attachments/assets/677bc5e5-9003-437b-90a7-c5c9affdab12" />

**Project Developed by Jayapradan M**
