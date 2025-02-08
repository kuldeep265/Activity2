<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            height: 100%;
        }
        header {
            width: 100%;
            height: 15%;
            background-color: green;
            color: white;
            text-align: center;
            line-height: 80px;
        }
        nav {
            width: 100%;
            height: 30px;
            text-align: center;
            background-color: green;
            text-decoration: none;
        }
        a {
            text-align: center;
            padding: 0 25px;
            color: white;
            text-decoration: none;
        }
        .container {
            display: flex; 
            padding-top: 50px;
            justify-content: space-around;
            background-color: antiquewhite;
            width: 100%;
            height: 350px;
        }
        .box1, .box3 {
            background-color: white;
            border-radius: 10px;
            width: 30%;
            height: 230px;
            color: green;
            padding: 20px;
            border: 1px solid gray;
            box-shadow: 3px 3px 10px;
            
        }
        .box2{
            background-color: white;
            border-radius: 10px;
            width:580px;
            height: 230px;
            color: green;
            padding: 20px;
            border: 1px solid gray;
            box-shadow: 3px 3px 10px;
            margin-left: 20px;
        }
        div > p {
            color: black;
            font-weight: bold;
            padding: 5%;
            font-family: 'Segoe UI', Tahoma, Verdana, sans-serif;
        }
        .footer {
            background-color: brown;
            width: 100%;
            height: 70px;
            text-align: center;
            justify-content: center;
            display: flex;
            color: antiquewhite;
        }
        .container1{
            background-color: antiquewhite;
            padding: 20px;
            height: 350px;
            padding-left: 168px;
        }
        p{
            padding-top: 25px;
            font-size: x-large;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Your Website Task</h1>
    </header>
    <nav>
        <a href="https://www.google.com/">Home</a>
        <a href="https://chatgpt.com/">About</a>
        <a href="https://indianhelpline.com/">Contact</a>
    </nav>
    <div class="container">
        <div class="box1">
            <h2>About CSS</h2>
            <p >Cascading Style Sheets(CSS) allow you to style and layout you web pages,adding colours, spacing and more.</p>
        </div>
        
        <div class="box3">
            <h2>Box Model</h2>
            <p>The CSS Box Model Describes The Rectangle Boxes Generate Elements And Its Includes Margin, Border, Padding And The Actual Class</p>
        </div>
    </div>
    <div class="container1">
    <div class="box2">
        <h2>Responsive Design</h2>
        <p>Resposive Design Ensures Your Web Page Looks Great on All  Devices</p>
    </div>
    </div>
    <p class="footer" style="font-size: xx-largex-large;">Created by [Deependra Singh Kansana] | Follow us on <a href="https://www.instagram.com/">Instagram</a>| <a href="https://x.com/?lang=en">Twitter </a>| <a href="https://api.linkedin.com/login">LinkedIn </a></p>
</body>
</html>
