//home page of the website ("Anelya_project")
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="project_styles.css">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    <title>Life Stream</title>
</head>
<body>
    <!-- whole white page -->
    <div class="page">
        <!-- name of site -->
        <header>
            <div class="container-fluid">
                <div class="row" id="header-name">
                    <div class="col-lg-4 col-md-4 col-sm-1"></div>
                    <div class="col-lg-4 col-md-4 col-sm-10">
                        <h4 class="text-center"><a href="#" onclick="home()">Life Stream</a></h4>
                    </div>
                    <div class="col-lg-4 col-md-4 col-sm-1"></div>
                </div>
            </div>
        </header>
        <!-- all information -->
        <div>
            <header> <!-- menu -->
                <nav class="nav navbar navbar-expand-md navbar-dark sticky-top" style="background-color: black;">
                    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarResponsive"><span class="navbar-toggler-icon"></span></button>
						<div class="collapse navbar-collapse" id="navbarResponsive">
				        <div class="container-fluid">
                            <a class="nav-link" href="#" style="color: #fec22d;" onclick="home()">Home</a>
                            <a class="nav-link" href="#" onclick="tips()">Tips</a>
                            <a class="nav-link" href="#" onclick="food()">Food</a>
                            <a class="nav-link" href="#" onclick="fashion()">Fashion</a>
                            <a class="nav-link" href="#" onclick="beauty()">Beauty</a>
                            <a class="nav-link" href="#" onclick="diy()">DIY</a>
                            <a class="nav-link" href="#" onclick="environment()">Environment</a>
                            <a class="nav-link" href="#" onclick="about()">About</a>
                        </div>
                        </div>
                </nav>
            </header>
            <br>
            <div>
                <main>
                    <section> <!-- carousel of news -->

                    </section>
                    <section class="border-top">
                        <h5 class="pt-3">Tips</h5>
                        <div class="container-fluid" id="container-mainpage">
                            <div class="row justify-content-center align-items-start" id="posts">
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center" onclick="article1()">
                                        <img src="postphotobag.jpg" alt="">
                                        <p>3 Types of Shopping Bags that are Eco-friendly</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </section>
                    <section class="border-top">
                        <h5 class="pt-3">Fashion</h5>
                        <div class="container-fluid" id="container-mainpage">
                            <div class="row justify-content-center align-items-start">
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </section>
                    <section class="border-top">
                        <h5 class="pt-3">Beauty</h5>
                        <div class="container-fluid" id="container-mainpage">
                            <div class="row justify-content-center align-items-start">
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </section>
                    <section class="border-top">
                        <h5 class="pt-3">DIY</h5>
                        <div class="container-fluid" id="container-mainpage">
                            <div class="row justify-content-center align-items-start">
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </section>
                    <section class="border-top">
                        <h5 class="pt-3">Environment</h5>
                        <div class="container-fluid" id="container-mainpage">
                            <div class="row justify-content-center align-items-start" id="posts">
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </section>
                    <section class="border-top">
                        <h5 class="pt-3">Food</h5>
                        <div class="container-fluid" id="container-mainpage">
                            <div class="row justify-content-center align-items-start">
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                                <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6 col-12">
                                    <div class="text-center">
                                        <img src="bulk.jpg" alt="">
                                        <p>10 Tips for Eco-Friendly Grocery Shopping</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </section>
                    <!-- email subscription 
                    <section> 
                         
                    </section> -->
                </main>
            </div>
        </div>

        <footer> <!-- menu, all rights... -->
            <nav class="nav" style="background-color: rgba(0, 0, 0, 0.068);">
                <a class="nav-link" href="#" style="color: #fec22d;" onclick="home()">Home</a>
                <a class="nav-link" href="#" onclick="tips()">Tips</a>
                <a class="nav-link" href="#" onclick="food()">Food</a>
                <a class="nav-link" href="#" onclick="fashion()">Fashion</a>
                <a class="nav-link" href="#" onclick="beauty()">Beauty</a>
                <a class="nav-link" href="#" onclick="diy()">DIY</a>
                <a class="nav-link" href="#" onclick="environment()">Environment</a>
                <a class="nav-link" href="#" onclick="about()">About</a>
            </nav>
        </footer>
    </div>
    <script src="project_js.js"></script>
    <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
</body>
</html>



//style CSS of the website ("project_styles")
html, body {
    height: 100%;
    margin: 0;
    padding: 0;
}
/* background */
body {
    background: #67D728; /* for browsers that do not support gradients */
    background: linear-gradient(135deg, #fec22d 0%, #a4c223 47%, #7ac21f 70%, #46c119 100%);
    background-attachment: fixed;	
    background-size: cover;
}
/* whole page */
div.page {
    background-color: white;
    height: auto;
    margin: 0 30px;
}/*
div.page:child {
    margin: 0 !important;
}*/
/* website name */
h4 {
    text-align: center;
}
h4 a {
    text-decoration: none;
    color: #a4c223;
    font-family: Optima, sans-serif;
    font-size: 70px;
    font-weight: 700;
    text-transform: uppercase;
    text-shadow: -2px -2px 0px #a4c223;
    background: repeating-linear-gradient(45deg, #7ac21f, #7ac21f 1px, white 2px, white 3px);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    display: table;
}
h4 a:hover {
    text-decoration: none;
}
/* menu navbar */
nav a {
    text-decoration: none;
    color: white;
    font-family: Didot, sans-serif;
    font-weight: 500;
    transition: all .7s ease-in-out;
    justify-self: center;
}
nav a:hover {
    text-decoration: none;
    color: #fec22d;
}
/*
.dropdown {
    position: relative;
    display: inline-block;
}
.dropdown-content {
    display: none;
    position: absolute;
    background-color: white;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
}
.dropdown:hover .dropdown-content {
    display: block;
}
.dropdown-content a {
  color: black;
  text-decoration: none;
  display: block;
  text-align: center;
}*/
h5 {
    font-family: "Palatino Linotype", "Book Antiqua", Palatino, serif;
    font-size: 24px;
    letter-spacing: 2.4px;
    word-spacing: 0px;
    color: #000000;
    font-weight: 400;
    text-decoration: none;
    text-transform: uppercase;
    text-align: center;
}
#container-mainpage img {
    width: 170px;
    height: 170px;
}
#posts p {
    padding: 0 5px;
}
/*
bootstrap-sm: 576px; for xs
bootstrap-md: 768px; for sm
bootstrap-lg: 992px; for md
bootstrap-xl: 1200px; for lg
*/
@media (min-width: 1200px) {
    /* menu */
    nav {
        justify-content: space-around;
    }
}
@media (max-width: 1200px) {
    #container-mainpage img {
        width: 210px;
        height: 210px;
    }
    /* menu center */
    nav {
        justify-content: center; 
    }
}
@media (max-width: 992px) {
    #container-mainpage img {
        width: 205px;
        height: 205px;
    }
}
@media (max-width: 768px) {
    #container-mainpage img {
        width: 220px;
        height: 220px;
    }
}
@media (max-width: 576px) {
    #container-mainpage img {
        width: 250px;
        height: 250px;
    }
}
/* how each page of menu look except HOME & ABOUT */
.eachpage-main-flex-column {
    display: flex;
    flex-direction: column;
    flex-wrap: nowrap;
    margin: 20px;
}
.flex-row {
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 10px;
}
.flex-row:nth-child(even) {
    justify-content: flex-end;
}
.flex-row p {
    padding-left: 10px;
}
.flex-row:nth-child(even) p {
    padding-left: 0;
    padding-right: 10px;
}
#mainpage-flex img {
    width: 250px;
    height: 250px;
}
@media (min-width: 576px) {
    #mainpage-flex img {
        width: 270px;
        height: 270px;
    }
}
@media (min-width: 768px) {
    #mainpage-flex img {
        width: 350px;
        height: 350px;
    }
}
@media (min-width: 992px) {
    #mainpage-flex img {
        width: 290px;
        height: 290px;
    }
}
@media (min-width: 1200px) {
    #mainpage-flex img {
        width: 250px;
        height: 250px;
    }
}
h2 {
    color: #fec22d;
    padding-bottom: 12px;
}
.flex-text {
    text-align: center;
    display: flex;
    flex-direction: column;
    margin: 10px;
}
.flex-text p {
    font-family: 'Times New Roman', Times, serif;
    font-size: 20px;
}
.flex-text img {
    display: block;
    margin: auto;
    width: 50%;
    height: 50%;
}



//JS code
function home(){
    window.location.assign("project_Anelya.html");
}
function tips(){
    window.location.assign("tips.html");
}
function food(){
    window.location.assign("food.html");
}
function fashion(){
    window.location.assign("fashion.html");
}
function beauty(){
    window.location.assign("beauty.html");
}
function diy(){
    window.location.assign("diy.html");
}
function environment(){
    window.location.assign("environment.html");
}
function about(){
    window.location.assign("about.html");
}
function article1(){
    window.open("article1.html");
}
