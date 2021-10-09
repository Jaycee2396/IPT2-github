<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>Contact page</title>
<link rel="stylesheet" href="style.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.14.0/css/all.min.css">
<meta name="viewport" content="width=device=width, initial-scale=1">
<style>
body{
    margin: 0;
    padding: 0;
    background: #74ff14;
}
.header{
    width: 100%;
    position: fixed;
}
nav{
    width: 100%;
    background: black;
    overflow: auto;
}
ul{
    margin:0;
    padding:60px 0 0 250px;
    list-style: none;
}
li{
    float: left;
}
.logo img{
    position: absolute;
    width: 200px;
    height: 100px;
    margin-top: 15px;
    margin-left: 10px;
}
nav a{
    width: 100px;
    display: block;
    padding: 20px 15px;
    text-decoration: none;
    font-family: Arial;
    color: #74ff14;
    text-align:center;
}
nav a:hover {
    background: purple;
    transition: 0.5s;
    text-transform: uppercase;
}
*{
    margin: 0;
    padding: 0;
    font-family: "montserrat",sans-serif;
}
.contact-section{
    background: url(contactform.jpg) no-repeat center;
    background-size: cover;
    padding: 122px 666px;
}
.contact-section h1{
    text-align: center;
    color: #74ff14;
    margin-top: 100px;
}
.border{
    width:  100px;
    height: 10px;
    background: #34495e;
    margin: 40px auto;
}
.contact-form{
    max-width: 600px;
    margin: auto;
    padding: 0 10px;
    overflow: hidden;
}
.contact-form-text{
    display: block;
    width: 100%;
    box-sizing: border-box;
    margin: 16px 0;
    border: 0;
    background: #111;
    padding: 20px 40px;
    outline: none;
    color: #74ff14;
    transition: 0.5s;
    text-decoration: #74ff14;
}
.contact-form-text:focus{
    box-shadow: 0 0 10px 4px #74ff14;
}
textarea.contact-form-text{
    resize: none;
    height: 120px;
}
.contact-form-btn{
    float: right;
    border 0;
    background: #34495e;
    color: #fff;
    padding: 12px 50px;
    border-radius: 20px;
    cursor: pointer;
    transition: 0.5s;
}
.contact-form-btn:hover{
    background: #74ff14;
}
</style>
</head>
<body>
<header class="header">
<div class="logo"><a href="#"><img src="logo.jpg"></a>
</div>
<nav>
    <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="Music.html">Music</a></li>
        <li><a href="About.html">About</a></li>
        <li><a href="Contact.html">Contact</a></li>
        <li><a href="Register.html">Register</a></li>
        <li>
        <form class="search-box" action="" method="">
        <input type="text" name="" value="" placeholder="Search">
        <button class="search-btn" type="button" name="button">
        <i class="fas fa-search"></i>
        </button>
        </form>
        </li>
    </ul>
</nav>
</header>
<div class="contact-section">
<h1>Contact Us</h1>
<form class="contact-form" action="#" method="post">
    <input type="text" class="contact-form-text" placeholder="Your name">
    <input type="email" class="contact-form-text" placeholder="Your email">
    <input type="text" class="contact-form-text" placeholder="Your phone">
    <textarea class="contact-form-text"placeholder="Your message"></textarea>
    <input type="submit" class="contact-form-btn" value="Send">
</form>
</div>
</body>
</html>
