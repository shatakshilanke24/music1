
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
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
