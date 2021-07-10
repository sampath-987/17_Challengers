 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
         header{ 
            margin: 0px;
            padding: 0px;
            background-image: url('img/bgi.jpg');
            height: 100vh;
            background-size: cover;
            background-position: center;

        }
        ul{
            float: right;
            list-style-type: none;
            margin-top: 25px;

         }
        ul li{
            display: inline-block;


        }
        ul li a{
            text-decoration: none;
            color: #000;
            padding: 5px 20px;
            border: 1px solid transparent;
            transition: 0.6s ease;

        }

        ul li a:hover{
            background-color: #fff;
            color: #000;
        }
         .title{
             position :absolute;
             top:50%;
             left:50%;
             transform : translate(-50%,-50%);
            
        }
        .title h1{
            color: #000 ;
            font-size: 70px;
        }
        .button{
            position :absolute;
             top:62%;
             left:50%;
              transform : translate(-50%-50%);

        }
    .btn{
        border: 1px solid #fff;
        padding: 10px 30px;
        text-decoration: none;
        transition: 0.6s ease;
        color: #000;

    }
        .btn:hover{
            background-color: #fff;
            color: #000;

}
        .logo img{
            float: left;
            width: 150px;
            height: auto;
            padding-left: 34px;
            padding-top: 24px;
        }
        .main{
                max-width: 1200px;
                margin: auto;
        }
        ul li.active a{
            background-color: #fff;
            color: #000;
        
        }
        
        img{
            padding-left: 100px;
            padding-right: 20px;
            
        }
        .container{
            background-color: rgb(250 246 246);

        }
    
        

    </style>
</head>
<body>
    <header >
        <div class="main">
            <div class="logo">
                <img src="img/bg.jpg" alt="error">
            </div>
        <ul>
            <li class="active"><a href="#">Home</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Gallery</a></li>
            <li><a href="#">About</a></li>
        </ul>
            <div class="title">
                <h1> MIND + BODY DESIGN</h1>
            </div>
            <div class="button">
                <a href="#"class="btn">Mental health</a>
                <a href="#"class="btn">Physical health</a>
                
            </div>
            
        </header>
        <br>
        <div class="container">
        <img src="img/bg2.jpg" alt="img" width="350">
        <img src="img/bg3.jpg" alt="img" width="350">
        <img src="img/bg4.jpg" alt="img" width="350">
        </div>
        <br>
        <hr>
        <video src="img/bg5.mp4" width="400px" controls></video>
</body>
</html>
