<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix Clone</title>
    <link rel="stylesheet" href="http://cdnjs.cloudflare.com/ajax/libs/fontawesome/4.7.0/css/font-awesome.min.css"/>
    <link
        href="https://fonts.googleapis.com/css2?family=Montserrat:wght@100;200;300;400;500;600;700;800;900&display=swap"
        rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    
<body>
    <div class="container">
        <div class="navigation flex">
            <div class="logo">
                <img src="logo.png" alt="logo">
            </div>
            
            <div class="navbar flex" id="navbar">
                <div class="left-nav flex">
                    <ul flex menu>
                        <li>Home</li>
                        <li>Tv Shows</li>
                        <li>Movies</li>
                        <li>New & Populer</li>
                        <li>My List</li>
                    </ul>
                </div>

                <div class="right-nav flex">
                    <span class="fa fa-search fa" aria-hidden="true">
                        <p>Children</p>
                    </span>
                    <span class="fa fa-bell-o fa" aria-hidden="true"></span>
                    <img src="chimping.jpg" alt="">
                    <span class="fa fa-caret-down fa" aria-hidden="true"></span>  
                   
                </div>
            </div>
            <span class="togglebtn" onclick="toggle()">&#9776;</span>
        </div>

        <div class="inner">
            <div class="banner flex">
                <h3>Marvel's Studio's</h3>
                <h1>Iron Man 4 : Trailler </h1>
                <div class="banner-button flex">
                    <button class="btn"><span class="fa fa-play play" aria-hidden="true"></span>Play</button>
                    <button class="btn btn1"><span class="fa fa-info-circle play info" aria-hidden="true"></span>More Info</button>
                </div>
            </div>

            <div class="carousel">
                <h3>New Release</h3>
                <div class="carousel-slider">
                    <div class="carousel-items">
                        <img src="Avenger.jpg" alt="">
                    </div>
                    <div class="carousel-items">
                        <img src="venom.jpg" alt="">
                    </div>
                    <div class="carousel-items">
                        <img src="captain america.jpg" alt="">
                    </div>
                    <div class="carousel-items">
                        <img src="thor.jpg" alt="">
                    </div>
                    <div class="carousel-items">
                        <img src="spiderman.jpg" alt="">
                    </div>
                    <div class="carousel-items">
                        <img src="captain marval.jpg" alt="">
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="video-container">
        <div class="video-overaly"></div>
        <video autoplay loop muted>
            <source src="iron man.mp4">
        </video>
    </div>

    <script src="index.js"></script>
</body>
</html>
