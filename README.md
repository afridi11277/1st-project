# 1st-project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>gym_world</title>
</head>
<link href="https://fonts.googleapis.com/css2?family=Russo+One&display=swap" rel="stylesheet">
<link rel="stylesheet" href="style.css">

<style>
    body{
        font-family: 'Russo One', sans-serif;
        margin: 0px;
        padding: 0px;
        background: url('img.jpg');
        height: 2px;
    }
    .left{
        text-align: center;
        display: inline-block;
        position: absolute;
        left: 60px;
        top: 20px;
        color: white;
        

    }
    .left img{
        width: 100px;
        filter: invert(100%);
        
    }
    .left div{
        line-height: 19px;
        font-size: 26px;
        text-align: center;
        text-emphasis-color: white;

    }
    
    .right{
        
        display: inline-block;
        position: absolute;
        right: 34px;
        top: 10px;
        cursor: pointer;
        margin: 2px;

    }
    .mid{
        display: block;
        width: 33%;
        margin: 12px auto;
        border: 2px solid rgb(235, 245, 235);
        border-radius: 15px;
    }

    .navbar{
        display: inline-block;

    }
    .navbar li{
        display: inline-block;
        font-size: 15px;
    }
    .navbar li a{
        color: white;
        text-decoration: none;
        padding: 5px;
    }
    .navbar li a:hover, .navbar li a.active{
        text-decoration: underline;
        color: grey;
    }

    .btn{
        font-family: 'Russo One', sans-serif;
        margin: 0px 9px;
        background-color: black;
        color: white;
        padding: 4px 14px;
        border: 2px solid grey;
        border-radius: 10px;
        font-size: 20px;
        cursor: pointer;
    }
    .btn:hover{
        background-color: rgb(26, 23, 23);
        
    }
    .container{
        color: rgb(248, 225, 14);
        margin: 106px 80px;

        padding: 75px;
        width: 33%;
        border-radius: 28px;
    }
    .form-group input{
        font-family: 'Russo One', sans-serif;
        text-align: center;
        display: block;
        width: 300px;
        padding: 1px;
        border: 2px solid black;
        margin: 9px auto;
        border-radius: 10px;
        font-size: 23px;

    }
    .container h1{
        text-align: center;

    }
    .container button{
        display: block;
        width: 74%;
        margin: 20px auto;

    }
</style>
<body
>
    <header class="header">
       
        <div class="left">
            <img src="img3.png" alt="">
            <div>fitness first</div>
        </div>
      
        <div class="mid">
           <ul class="navbar">
               <li><a href="#">HOME</a></li>
               <li><a href="#">FACILITIES</a></li>
               <li><a href="#">ABOUT US</a></li>
               <li><a href="#">CONTACT US</a></li>
           </ul>
        </div>
        

        <div class="right">
            <button class="btn">call us now</button><button class="btn">Email us</button>

        </div>
    </header>
    <div class="container">
        <h1>THE BEST GYM IN HABIGANJ</h1>
        <form action="noaction.php">
            <div class="form-group">
                <input type="text" name="" placeholder="enter your name">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="enter your age">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="enter your height">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="enter your gender">
            </div>
            <button class="btn">submit</button>
        </form>
    </div>

</body>
</html>
