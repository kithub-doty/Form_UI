# Form_UI
<!DOCTYPE html>
<html>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>logIn</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css" type="text/css" />
    
    <style type="text/css" media="all">
    
        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: sans-serif;
        }
        body{
            
        }
        .loginForm{
            font-weight: bold;
            width: 300px;
            height: 555px;
            padding:15px;
            border: 2px solid #BCBBB3;
            margin: 10px;
            border: 1px solid #9A9A9E;
            border-radius: 20px;
            background: linear-gradient(145deg, #ffffff, #e3e3e3);
            box-shadow: 3px 3px 3px #b5b5b5,
            -2px 0px 1px #C2C3CD;
        }
        .loginForm legend img{
            margin-bottom: 24px;
        }
        i{
            padding:5px;
        }
        .input label{
            font-weight: bold;
            display: block;
            margin: 10px;
            color: #5D5D61;
        }
        .input input{
            font-weight: bold;
            display:block;
            margin-bottom: 15px;
            width: 300px;
            height: 40px;
            color:#4E4E53;
            outline: none;
            padding: 20px;
            border:hidden;
            border-radius: 20px;
            background: #ffffff;
            box-shadow: inset 3px 3px 2px #9D9EA3,
            inset -3px -3px 2px #DDDDE1;
            
        }
        .signIn input{
            font-weight: bold;
            font-size: 15px;
            color: #ffffff90;
            outline:none;
            width: 250px;
            height: 40px;
            margin:25px;
            margin-bottom: 50px;
            padding: 10px 15px;
            border:hidden;
            border-radius: 20px;
            background:#2E3CD5;
            box-shadow: 3px 3px 3px #9D9EA3,
            -2px -2px 1px #D8D9E5;
        }
        .signIn input:active{
            background: #2E3CD590;
        }
        .link{
            display:inline-flex;
        }
        .link hr{
            width: 120px;
            margin-top: 30px;
            color:#A8A8A9;
            
        }
        .fPassword{
            
        }
        .else{
            margin-left: 20px;
            margin-right: 20px;
            margin-top: 35px;
            font-weight: bold;
            color:#A8A8A9;
        }
        .acc-create{
            text-decoration: none;
            margin-left: 15px;
            cursor: text;
            user-select: none;
            transition: 0.5ms;
        }
        .acc-create:active{
            border-radius:15px;
            padding: 7px;
            background:#CACACB;
            color:#3540BB;
        }
        .for-password{
            text-decoration: none;
            margin-left: 5px;
            cursor: text;
            user-select: none;
            transition: 0.5ms;
        }
        .for-password:active{
            border-radius:15px;
            padding: 7px;
            background:#CACACB;
            color:#3540BB;
        }
        .list{
            display:inline-flex;
            margin-left:50px;
            margin-top: 5px;
        }
        .list li{
            list-style-type: none;
            margin-right: 20px;
        }
        .siteBox{
            margin-top: 20px;
        }
        .siteBox li a{
            border-radius 60px;
            cursor:text;
            user-select: none;
        }
        
        .siteBox li a .goLink1{
        transition: 1ms;
        }
        .siteBox li a .goLink2{
        transition: 1ms;
        }
        .siteBox li a .goLink3{
        transition: 1ms;
        }
        .siteBox li a .goLink1:active{
            background-image:url('access/googleFull.png');
            background-image: no-repeat;
            user-select: none;
        }
        .siteBox li a .goLink2:active{
            background-image:url('access/facebookFull.png');
            background-image: no-repeat;
            user-select: none;
        }
        .siteBox li a .goLink3:active{
            background-image:url('access/twitterFull.png');
            background-image: no-repeat;
            user-select: none;
        }
    </style>
</head>

<body>
    
    <div>
        <fieldset class="loginForm">
            <legend>
                <img src="access/movie-projector.png" alt="movie-projector"/>
            </legend>
            <form class="inputForm" action="#" method="get" accept-charset="utf-8">
                <div class="input">
                    <label for="name">
                        <i class="fas fa-user"></i>Username
                    </label>
                    <input type="username" name="name" id="name" placeholder="example@gmail.com" required="">
                </div>
                <div class="input">
                    <label for="passWord">
                        <i class="fas fa-key"></i>Password
                    </label>
                    <input type="password" name="password" id="passWord" placeholder="••••••••" required="">
                </div>
                <div class="signIn">
                    <input type="submit" name="click" id="logIn" value="Sign In">
                </div>
            </form>
            <div class="link">
                <div class="reg-link">
                    <a  class="acc-create" href="signUp_Form.html">Create Account</a>
                    <hr />
                </div>
                <p class="else">or</p>
                <div class="fPassword">
                    <a  class="for-password" href="#">Forgot Password?</a>
                    <hr />
                </div>
            </div>
            <div class="siteBox">
                <ul class="list">
                    <li>
                            <a href="#">
                                <img class="goLink1" src="access/google.png" alt="" />
                            </a>
                    </li>
                    <li>
                            <a href="#">
                                <img class="goLink2" src="access/facebook.png" alt="" />
                            </a>
                    </li>
                    <li>
                            <a href="#">
                                <img class="goLink3" src="access/twitter.png" alt="" />
                            </a>
                    </li>
                </ul>
            </div>
            
        </fieldset>
    </div>

</body>

</html>
