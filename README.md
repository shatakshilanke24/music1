
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
    <style>
        *{
    margin:0%;
    padding:0%;
}
.container{

    background-image:url(b2.jpg);
    width:1500px;
    height: 700px;
    background-size: cover;
    background-attachment: fixed;    


    }
.nav{
    width: 88%;
    margin: auto;
    padding: 10px 0;
    display: flex;
    align-items: right;
    text-align: right;
    justify-content: space-between;
    font-weight: 300px;
}
.nav ul li{
    list-style: none;
    display: inline-block;
    margin: 0 15px;
    font-size: 50px;
}
.nav ul li a{
    font-size: 50px;
    text-decoration: none;
    color: whitesmoke;
    font-size: 15px;
    text-align: center;
}
.content{
    width: 100%;
    position: absolute;
    top: 20%;


}
.left-col{
    margin-left: 6%;

}
.left-col h2{
    font-size: 50px;
    color:whitesmoke;
    line-height: 80px;
    float: left;
    margin-top: 9%;
}
.right-col{
    margin-left: 80%;
    margin-right: 6%;
    margin-top: 80px;
    display: flex;

}
.right-col p{
    font-size: 40px;
    font-weight: 300;
    width: 50%;
    height: 10%;
    color:whitesmoke;
    margin-right: 15px;
    margin-top: 5%;
}
    </style>
</head>

<body>
    *{
    margin:0%;
    padding:0%;
}
.container{

    background-image:url(b2.jpg);
    width:1500px;
    height: 700px;
    background-size: cover;
    background-attachment: fixed;    


    }
.nav{
    width: 88%;
    margin: auto;
    padding: 10px 0;
    display: flex;
    align-items: right;
    text-align: right;
    justify-content: space-between;
    font-weight: 300px;
}
.nav ul li{
    list-style: none;
    display: inline-block;
    margin: 0 15px;
    font-size: 50px;
}
.nav ul li a{
    font-size: 50px;
    text-decoration: none;
    color: whitesmoke;
    font-size: 15px;
    text-align: center;
}
.content{
    width: 100%;
    position: absolute;
    top: 20%;


}
.left-col{
    margin-left: 6%;

}
.left-col h2{
    font-size: 50px;
    color:whitesmoke;
    line-height: 80px;
    float: left;
    margin-top: 9%;
}
.right-col{
    margin-left: 80%;
    margin-right: 6%;
    margin-top: 80px;
    display: flex;

}
.right-col p{
    font-size: 40px;
    font-weight: 300;
    width: 50%;
    height: 10%;
    color:whitesmoke;
    margin-right: 15px;
    margin-top: 5%;
}
    <div class="container">
        <div class="nav">
            <ul>
                <li><a href="#" target="_blank">HOME</li>
                <li><a href="#">ABOUT US</li>
                    <li><a href="">CONTACT US</li>
            </ul>
        </div>
        </div>
        </body>
        <div class="content">
            <div class="left-col">
                <h2>THE<br> REAL<br> SOUND</h2><br>
            </div>
            <div class="right-col">
                <p>click here to listen <img src="playm.jpg" width="15px" height="15px" id="icon">  <img src="pause1.png" width="15px" height="15px" id="pause"></p>
                
            </div>
        </div>
        <audio id="mysong">
            <source src="namo.mp3" type="audio/mp3">
        </audio>
        <script>
            var mysong=document.getElementById("mysong");
            var icon=document.getElementById("icon");
            var pause=document.getElementById("pause");

           

            icon.onclick=function(){
                mysong.play();

                }
                pause.onclick=function(){
                    mysong.pause();
                }
                </script>





</body>

</html>
