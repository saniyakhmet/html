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
