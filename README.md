<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>project1</title>
</head>
<style>
    body {
        color: white;
        margin: 0px;
        padding: 0px;
        background-image: url('img/apple-256261_1280.jpg');
        background-size: cover;
        background-repeat: no-repeat;
      
    }

    .left {
        /* border: 2px solid white; */
        display: inline-block;
        position: absolute;
        left: 34px;
        top: 20px;
        text-align: center;
        padding: 8px 20px;
        margin: 47px -424px;
        font-size: 50px;

    }

    .left img {
        display: inline-block;
        width: 12%;
        padding: 2px 18px;
        margin: 2px auto;

    }

    .mid {
        border: 7px solid grey;
        background-color: rgb(46, 36, 36);
        display: inline-block;
        width:  40%;
        padding:  3px 53px 20px 12px;
        margin: 71px 1500px;
        font-size: 50px;
        text-align: center;
        border-radius: 22px;
        font-size: 60px;
        justify-content: space-evenly;
    }

    .right {
        padding:  2px 24px 33px 24px;
        margin: -29px 2px;
        display: inline-block;
        position: absolute;
        right: 141px;
        top: 112px;
        border: 7px solid rgb(163, 163, 151);
        font-size: 106px;
        padding: 8px -16px;
        border-radius: 100px;
    }

    .navbar {
        display: inline-block;
    }

    .navbar li {
        display: inline-block;
    }

    .navbar li a {
        text-decoration: none;
        color: aliceblue;
        padding: 34px 23px;
    }

    .navbar li a:hover,
    .navbar li a:active {
        text-decoration: underline;
        color: skyblue;

    }

    .container {
        border: 10px solid rgb(146, 139, 139);
        border-radius: 30px;
        display: inline-block;
        padding: 96px 90px;
        margin: 310px 2153px;
        width: 33%;
        text-align: center;
        font-size: 50px;

    }

    .formgroup {
        font-size: 50px;
    }

    .container h1 {
        color: beige;
    }

    .form-group input {
        font-size: 50px;
        border-radius: 30px;
        text-align: center;
        display: block;
        width: 800px;
        padding: 5px;
        border: 2px solid green;
        margin: 3px auto;
    }

    .btn {
        font-size: 50px;
        border: 2px solid black;
        padding: 4px 4px;
        cursor: pointer;
    }
    

    .btn:hover {
        background-color: rgb(201, 201, 210);
        
    }
    .navbar li a {
        color: rgb(155, 162, 166);

    }
    #follow {
        color: rgb(0, 1, 8);
        background-color:rgb(226, 159, 159);
        border: 4px solid red;
        padding: 12px 12px;
        border-radius: 90px;

    }
    #follow:hover {
        background-color: white;
        
        
    }

    #subscibe{
        border: 4px solid rgb(17, 2, 2);
        background-color: rgb(254, 3, 3);
        color: black;
        padding: 12px 12px;
        margin: 2px auto;
        /* font-size: 50px; */
        border-radius: 100px;
    }
    #subscibe:hover {
        background-color: white;
        
        
    }
    h1{
        border: 1px solid grey;
        border-radius: 12px;
    }
</style>

<body>
    <header class="header">
        <div class="left">
            <img src="img/logo.jpg" alt="">
            <div>note this </div>
        </div>
        <div class="mid">
            <ul class="navbar">
                <li><a href="#">Home </a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Information</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </div>
        <div class="right">
            <button class="btn" id="follow">Follow</button> <button class="btn" id="subscibe">Subscibe</button>
        </div>
    </header>

    <div class="container">
        <h1>Create your account</h1>
        <form action="noaction.php">
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your name"><br>
                <input type="number" name="" placeholder="Enter a number"><br>
                <input type="occupation" name="" placeholder="Occupation"><br>
                <input type="text" name="" placeholder="Enter your Address"><br>
                <button class="btn">submit </button> <button class="btn" aria-placeholder="">Sign In </button>

            </div>
        </form>

    </div>

</body>

</html>
