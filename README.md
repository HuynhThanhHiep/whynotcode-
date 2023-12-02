<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./pro2.css">
    <title>Document</title>
</head>
<body>
    <div class="boxbig">
        <div class="banner-welcom">Login<Br>Welcom back!</div>
        <input class="box1" type="text"id="fname" name="fname" value="Enter Your Username / Email">
        <input class="box2" type="password" id="fname" name="fname" value="Enter Your Password">
        <input class="banner-forgotpassword" type="submit" value="Forgot Password?">
        <input class="box3" type="submit" id="fname" name="fname" value="Login">
        <div class="group-signup">
            <input class="banner-donthave" type="text" id="fname" name="fname" value="Don't have an account?">
            <input class="text-signup" type="submit" id="fname" name="fname" value="Signup">
        </div>
        <div class="group-line-or">
            <div class="line-or"></div>
            <input class="text-or" type="text" id="fname" name="fname" value="Or">
            <div class="line-or"></div>
        </div>
        <input class="loginfacebook" type="submit" id="fname" name="fname" value="Login with Facebook">
        <input class="logingoogle" type="submit" id="fname" name="fname" value="Login with Google">
        <div class="logo">
            <div class="img-logo"></div>
            <input class="text-logo" type="text" id="fname" name="fname" value="It's Me Vinsensius Sugito Lein">
        </div>
    </div>
</body>
</html>

.boxbig{
    width: 360px;
    height: 800px;
    background: rgba(217, 217, 217, 0.02);
    border: 1px solid red;
    display: flex;
    flex-direction: column;
}
.banner-welcom{
    font-size: 24px;
    font-weight: 700;
    margin-top: 119px;
    margin-left: 82px;
    margin-right: 84px;
    display: flex;
    text-align: center;
    justify-content: center;
    font-size: 24px;
    font-weight: 700;
}
.box1{
    width: 312px;
    height: 48px;
    display: flex;
    justify-content: center;
    align-items: center;
    border: 1p solid rgba(0, 0, 0, 0.40);
    border-radius: 10px;
    margin-left: 24px;
    margin-right: 24px;
    margin-top: 43px;
}
.box2{
    width: 312px;
    height: 48px;
    display: flex;
    border: 1p solid rgba(0, 0, 0, 0.40);
    border-radius: 10px;
    margin-left: 24px;
    margin-right: 24px;
    margin-top: 28px;
}
.banner-forgotpassword{
    Width:125px;
    Height:21px;
    border: 1px solid white;
    background: white;
    color: #2F89FC;
    margin-top: 12px;
    margin-left: 117px;
}
.box3{
    width: 312px;
    height: 48px;
    border-radius: 5px;
    background: #0E64D2;
    text-align: center;
    color: white;
    margin-top: 20px;
    margin-left: 24px;
}
.group-signup{
    width: 229px;
    height: 21px;
    margin-top: 16px;
    margin-left: 66px;
    border: 1px solid white;
    display: flex;
    flex-direction: row;
}
.banner-donthave{
    font-size: 14px;
    font-weight: 500;
    border: 1px solid white;
}
.text-signup{
    color: #2F89FC;
    font-size: 14px;
    font-weight: 500;
    border: 1px solid white;
    background: white;
}
.group-line-or{
    width: 321px;
    height: 21px;
    display: flex;
    margin-left: 24px;
    margin-top: 17px;
}
.line-or{
    width: 139px;
height: 1px;
background: rgba(0, 0, 0, 0.50);
display: flex;
align-items: center;
justify-content: center;
margin-top: 11px;
}
.text-or{
    width: 17px;
    height: 21px;
    margin-left: 9px;
    margin-right: 9px;
    display: flex;
    align-items: center;
    justify-content: center;
    border: 1px solid white;
}
.loginfacebook{
    width: 312px;
    height: 48px;
    border-radius: 10px;
    background: #0E64D2;
    text-align: center;
    color: white;
    margin-top: 20px;
    margin-left: 24px;
    background-repeat: no-repeat;
    background-position: 9px 7px;
    background-image: url(./image/facebook\ logo.png);
}
.logingoogle{
    width: 312px;
    height: 48px;
    border-radius: 10px;
    background: rgba(255, 255, 255, 0.02);
    text-align: center;
    color: black;
    margin-top: 20px;
    margin-left: 24px;
    background-repeat: no-repeat;
    background-position: 9px 7px;
    background-image: url(./image/google\ logo.png);
}
.logo{
    width: 230px;
    height: 48px;
    border: 1px solid white;
    display: flex;
    flex-direction: row;
    margin-top: 68px;
    margin-left: 24px;

}
.img-logo{
width: 48px;
height: 48px;
margin-right: 6px;
border-radius: 50px;
background-repeat: no-repeat;
    background-image: url(./image/Me\ logo.png);
}
.text-logo{
    border: 1px solid white;
}
