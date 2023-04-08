# shankargiri07.github.io
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
        <link rel="stylesheet" href="style.css">    
       
    </head>
    <body>
        <header>
            <h3 class="logo">Port<span style="color: #fff;">Folio</span></h3>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Service</a></li>
                    <li><a href="#">Contact</a></li>
                    <li><a href="#">Login</a></li>
                </ul>
            </nav>
        </header>

        <main class="maincontainer">
            <div class="mainText">
              <h2>Hello, I'm <span style="color: #22ed22;">Shankar Giri</span>.</h2>
              <h3>I'm a full-stack web developer.</h3>
              <button>view my work 
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-arrow-right" viewBox="0 0 16 16">
                    <path fill-rule="evenodd" d="M1 8a.5.5 0 0 1 .5-.5h11.793l-3.147-3.146a.5.5 0 0 1 .708-.708l4 4a.5.5 0 0 1 0 .708l-4 4a.5.5 0 0 1-.708-.708L13.293 8.5H1.5A.5.5 0 0 1 1 8z"/>
                </svg>
              </button>
           </div>
        </main>

        <div class="iconContainer">
            <div class="imglogocontainer">
                <div class="firstlogo">
                    <img src="img/html.png" alt="">
                </div>
                <div class="firstlogo">
                    <img src="img/css.png" alt="">
                </div>
                <div class="firstlogo">
                    <img src="img/js.png" alt="">
                </div>
                <div class="firstlogo">
                    <img src="img/bootstrap.png" alt="">
                </div>
                <div class="firstlogo">
                    <img src="img/mongo.png" alt="">
                </div>
                <div class="firstlogo">
                    <img src="img/node.png" alt="">
                </div>
                <div class="firstlogo">
                    <img src="img/react.png" alt="">
                </div>
                <div class="firstlogo">
                    <img src="img/jq.png" alt="">
                </div>
                
            </div>
        </div>
        <div class="containerside">
            <div class="sidecontainer1">
                <div class="sideimg">
                    <img src="img/sideimg1.jpg" alt="">
                </div>
                <div class="sidepara">
    
                </div>
            </div>
            <div class="sidecontainer1">
                <div class="sidepara">
    
                </div>
                
                <div class="sideimg">
                    <img src="img/sideimg2.jpg" alt="">
                </div>      
            </div>
            <div class="sidecontainer1">
                <div class="sideimg">
                    <img src="img/sideimg3.jpg" alt="">
                </div>
                <div class="sidepara">
    
                </div>
            </div>
           
        </div>
    </body>
</html>


* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}
header {
    z-index: 2;
    position: sticky;
    top: 0;
    padding: 6px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: black;
    
}
.logo {
    font-size: 28px;
    margin-left: 40px;
    color: rgb(231, 48, 15);
}
ul {
    margin-right: 40px;
    
}
ul li{
    position: static;
    width: 100px;
    border-radius: 100px;
    text-align: center;
    display: inline-block;
    list-style: none;
    justify-content: center;
    padding: 10px;
    
}
ul li a {
   text-decoration: none; 
   font-size: 18px;
   padding: 2px;
   color: whitesmoke;
}
a:hover {
    transition: 1s;
    color: rgb(54, 226, 20);
}

.maincontainer {
    opacity: 0.9;
    background-image: url(img/bg2.avif);
    width: 100%;
    height: 600px;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: 100%;
    text-align: center; 
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
}
.mainText {
    display: block;
    position: absolute;
    top: 40%;
    left: 34%;
    justify-content: center;
    align-items: center;
    color: whitesmoke;
}
.mainText h2 {
    font-size: 34px;
    animation: slide_up 1.4s ease;
}
.mainText h3 {
    font-size: 34px;
    animation: slide_up 2.1s ease;
}
.mainText button {
   text-align: center;
   margin-top: 10px;
   width: 140px;
   padding: 10px;
   background: transparent;
   color: whitesmoke;
   font-size: 16px;
   font-weight: 300px;
   border: 2px solid #fff;
   animation: slide_up 2.7s ease;
}
.mainText button:hover {
    overflow: hidden;
    border: 2px solid #F11353;
    cursor: pointer; 
    transition: 1s;
}
/* .bi-arrow-right {
    margin-top: 10px;
} */
/* .bi-arrow-right {
    position: absolute;
    top: 81px;
    margin-left: 4px;
    animation: slide_up 1.0s ease;
} */
@keyframes slide_up {
    0% {
      transform: translateY(180PX)
    }
    100% {
      transform: translateY(0px);
    }
}
.imglogocontainer {
    overflow: hidden;
    margin: 40px 0;
    padding: 20px;
    background-color: #eee;
    width: 100%;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
}
.firstlogo > img{ 
    width: 170px;
    height: 150px;
    border: 1px solid black;
    border-radius: 15px;
    transition: 1s;
    overflow: hidden;
}
.firstlogo > img:hover {
    padding: 10px;
    width: 170px;
    height: 150px;
    border: 1px solid red;
    border-radius: 15px;
    transition: 1s;
}
.sidecontainer1 {
    margin: 50px;
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
}
.sideimg {
    width: 700px;
    height: 500px;
}
.sideimg > img {
    padding: 10px;
    width: 700px;
    height: 500px; 
    animation: slide_right 1.4s ease;
}
.sidepara {
    width: 700px;
    height: 500px;
    border: 1px solid black;
} 
@keyframes slide_right {
    0% {
      transform: translateX(30PX)
    }
    100% {
      transform: translateX(0);
    }
}
