<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>lab7</title>
    <link rel="stylesheet" href="../bootstrap/css/bootstrap.min.css">
    <link rel="stylesheet" href="../font-awesome/css/font-awesome.min.css">
    <style>
        .card-label {
            position: absolute;
            top: 30%;
            left: 0%;
            transform: translate(-0%, -30%);
        }

        .label-new,
        .label-sale {
            display: inline-block;
            padding: 5px 10px;
            font-size: 14px;
            font-weight: bold;
            color: #fff;
            background-color: #ff0000;
        }

        .carousel-caption {
            text-align: center;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100%;
        }

        .carousel-caption p {
            margin: 0;
        }

        .carousel-caption h3,
        p {
            z-index: 1;
            color: #fff;
        }
        .baner{
            background: url('./img/A-nh-chu-p-Ma-n-hi-nh-2023-03-8597-6748-1679808152.png') no-repeat;
            background-size: 100%;
            padding: 5%;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: #fff;
        }
        .baner p {
            margin: 0;
        }
    </style>
</head>

<body>

    <div class="container-fluid">
        <div class="row row-cols-1 row-cols-sm-2 pt-2 pb-2 bg-success">
            <div class="col d-none d-sm-block">
                <p class="d-inline">Help</p>
                <span class="d-inline text-white"><i class="fa fa-volume-control-phone text-white"
                        aria-hidden="true"></i>+1-202-555-0151</span>
            </div>
            <div class="col text-end">
                <p class="d-inline">My Accout</p>
                <p class="d-inline">Sign In</p>
                <p class="d-inline">Creat Accout</p>
            </div>
        </div>



        <div class="row">
            <nav class="navbar navbar-expand-sm navbar-dark bg-success">
                <div class="container-fluid">
                    <a class="navbar-brand" href="javascript:void(0)">
                        <h3>TSHOP</h3>
                    </a>
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#mynavbar">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse" id="mynavbar">
                        <ul class="navbar-nav me-auto">
                            <li class="nav-item">
                                <a class="nav-link" href="javascript:void(0)">HOME</a>
                            </li>
                            <li class="nav-item dropdown">
                                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">NEW
                                    PRODUCTS</a>
                                <ul class="dropdown-menu">
                                    <li><a class="dropdown-item" href="#">Link</a></li>
                                    <li><a class="dropdown-item" href="#">Another link</a></li>
                                    <li><a class="dropdown-item" href="#">A third link</a></li>
                                </ul>
                            </li>
                            <li class="nav-item dropdown">
                                <a class="nav-link dropdown-toggle" href="#" role="button"
                                    data-bs-toggle="dropdown">SHOP</a>
                                <ul class="dropdown-menu">
                                    <li><a class="dropdown-item" href="#">Link</a></li>
                                    <li><a class="dropdown-item" href="#">Another link</a></li>
                                    <li><a class="dropdown-item" href="#">A third link</a></li>
                                </ul>
                            </li>
                            <li class="nav-item dropdown">
                                <a class="nav-link dropdown-toggle" href="#" role="button"
                                    data-bs-toggle="dropdown">PAGES</a>
                                <ul class="dropdown-menu">
                                    <li><a class="dropdown-item" href="#">Link</a></li>
                                    <li><a class="dropdown-item" href="#">Another link</a></li>
                                    <li><a class="dropdown-item" href="#">A third link</a></li>
                                </ul>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="javascript:void(0)">ALL PAGE LINK</a>
                            </li>
                        </ul>
                        <div class="d-flex">
                            <li class="nav-item dropdown align-items-center d-inline text-white">
                                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">
                                    <i class="fa fa-shopping-cart" aria-hidden="true"></i>
                                    </i>CARTS($210.000)</a>
                                <ul class="dropdown-menu">
                                    <li><a class="dropdown-item" href="#">Product 1</a></li>
                                    <li><a class="dropdown-item" href="#">Product 2</a></li>
                                    <li><a class="dropdown-item" href="#">Product 3</a></li>
                                </ul>

                            </li>
                            <i class="fa fa-search ps-3 text-white" aria-hidden="true"></i>
                        </div>
                    </div>
                </div>
            </nav>
        </div>



        <div id="demo" class="carousel slide" data-bs-ride="carousel">
            <div class="carousel-indicators">
                <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
                <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
                <button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button>
            </div>
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="./img/images.jpg" alt="Los Angeles" class="d-block" style="width:100%">
                    <div class="carousel-caption">
                        <h3>Los Angeles</h3>
                        <p>We had such a great time in LA!</p>
                    </div>
                </div>
                <div class="carousel-item">
                    <img src="./img/lead-singer-455750_960_720-1200x650.jpg" alt="Chicago" class="d-block"
                        style="width:100%">
                    <div class="carousel-caption">
                        <h3>Chicago</h3>
                        <p>Thank you, Chicago!</p>
                    </div>
                </div>
                <div class="carousel-item">
                    <img src="./img/images (1).jpg" alt="New York" class="d-block" style="width:100%">
                    <div class="carousel-caption">
                        <h3>New York</h3>
                        <p>We love the Big Apple!</p>
                    </div>
                </div>
            </div>


            <button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
                <span class="carousel-control-prev-icon"></span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
                <span class="carousel-control-next-icon"></span>
            </button>
        </div>




        <div class="row">
            <div class="col-xl-3 col-lg-3 col-md-3 col-sm-6">
                <div class="card">
                    <img class="card-img-bottom" src="../img/tải xuống.jpg" alt="">
                    <div class="card-body d-flex flex-column">
                        <div class="card-label">
                            <span class="label-new bg-success">New</span>
                            <span class="label-sale bg-danger">15% OFF</span>
                        </div>
                        <h5 class="card-title text-center">Mèo cu te</h5>
                        <p class="card-text text-center text-black">Lorem ipsum dolor sit amet,
                            consectetur adipiscing elit.
                        </p>
                        <p class="card-text text-center">5kg-6kg</p>
                        <p class="card-text text-center"><strong>$100</strong></p>
                        <div class="d-flex justify-content-center">
                            <button class="btn bg-success">
                                <i class="fa fa-shopping-cart" aria-hidden="true"></i>Add to cart
                            </button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-xl-3 col-lg-3 col-md-3 col-sm-6">
                <div class="card">
                    <img class="card-img-bottom" src="../img/tải xuống.jpg" alt="">
                    <div class="card-body d-flex flex-column">
                        <div class="card-label">
                            <span class="label-sale bg-danger">15% OFF</span>
                        </div>
                        <h5 class="card-title text-center">Mèo cu te</h5>
                        <p class="card-text text-center text-black">Lorem ipsum dolor sit amet,
                            consectetur adipiscing elit.
                        </p>
                        <p class="card-text text-center">5kg-6kg</p>
                        <p class="card-text text-center"><strong>$100</strong></p>
                        <div class="d-flex justify-content-center">
                            <button class="btn bg-success">
                                <i class="fa fa-shopping-cart" aria-hidden="true"></i>Add to cart
                            </button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-xl-3 col-lg-3 col-md-3 col-sm-6">
                <div class="card">
                    <img class="card-img-bottom" src="../img/tải xuống.jpg" alt="">
                    <div class="card-body d-flex flex-column">
                        <div class="card-label">
                            <span class="label-new bg-success">New</span>
                        </div>
                        <h5 class="card-title text-center">Mèo cu te</h5>
                        <p class="card-text text-center text-black">Lorem ipsum dolor sit amet,
                            consectetur adipiscing elit.
                        </p>
                        <p class="card-text text-center">5kg-6kg</p>
                        <p class="card-text text-center"><strong>$100</strong></p>
                        <div class="d-flex justify-content-center">
                            <button class="btn bg-success">
                                <i class="fa fa-shopping-cart" aria-hidden="true"></i>Add to cart
                            </button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-xl-3 col-lg-3 col-md-3 col-sm-6">
                <div class="card">
                    <img class="card-img-bottom" src="../img/tải xuống.jpg" alt="">
                    <div class="card-body d-flex flex-column">
                        <h5 class="card-title text-center">Mèo cu te</h5>
                        <p class="card-text text-center text-black">Lorem ipsum dolor sit amet,
                            consectetur adipiscing elit.
                        </p>
                        <p class="card-text text-center">5kg-6kg</p>
                        <p class="card-text text-center"><strong>$100</strong></p>
                        <div class="d-flex justify-content-center">
                            <button class="btn bg-success">
                                <i class="fa fa-shopping-cart" aria-hidden="true"></i>Add to cart
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="baner mt-3">
        <h3>TRUSTED SELLER 500+</h3>
        <P>Lorem ipsum dolor sit amet consectetuer</P>
    </div>

    <footer class="text-center text-lg-start border mt-xl-5 pt-4">

        <div class="container p-4">

            <div class="row">
                <div class="col-lg-2 col-md-6 mb-4 mb-lg-0">
                    <h5 class="text-uppercase mb-4">SUPPORT</h5>
                    <div class="row">
                        <p class="text-dark">Lorem ipsum dolor sit amet connetetur</p>
                        <p class="text-dark"><i class="fa fa-envelope text-dark"
                                aria-hidden="true">contact@example.com</i></p>
                        <p class="text-dark"><i class="fa fa-phone" aria-hidden="true">+48 2345 6788</i></p>
                    </div>
                </div>

                <div class="col-lg-2 col-md-6 mb-4 mb-lg-0">
                    <h5 class="text-uppercase mb-4">SHOP</h5>
                    <div class="row">
                        <p class="text-dark">Men's</p>
                        <p class="text-dark">Women's</p>
                        <p class="text-dark">Kids's</p>
                        <p class="text-dark">Shoe's</p>
                        <p class="text-dark">Gift Cards</p>
                    </div>
                </div>


                <div class="col-lg-2 col-md-6 mb-4 mb-lg-0">
                    <h5 class="text-uppercase mb-4">INFORMATION</h5>
                    <div class="row">
                        <p class="text-dark">Question ?</p>
                        <p class="text-dark">Order status</p>
                        <p class="text-dark">Sizing Charts</p>
                        <p class="text-dark">Return Policy</p>
                        <p class="text-dark">Contact Us</p>
                    </div>
                </div>

                <div class="col-lg-2 col-md-6 mb-4 mb-lg-0">
                    <h5 class="text-uppercase mb-4">MY ACCOUNT</h5>
                    <div class="row">
                        <p class="text-dark">My Account</p>
                        <p class="text-dark">My Address</p>
                        <p class="text-dark">Wish List</p>
                        <p class="text-dark">Order List</p>
                        <p class="text-dark">Order Status</p>
                    </div>
                </div>

                <div class="col-lg-4 col-md-6 mb-4 mb-lg-0">
                    <h5 class="text-uppercase mb-4">STAY IN TOUCH</h5>
                    <div class="row">
                        <button type="submit" class="btn btn-outline-dark btn-block">Email</button>
                        <button type="submit" class="btn btn-outline-dark btn-block bg-success mt-4">Subscribe</button>
                        <div class="mt-4">

                            <a type="button" class="btn btn-floating btn-light btn-lg"><i
                                    class="fa fa-facebook-official" aria-hidden="true"></i></i></a>

                            <a type="button" class="btn btn-floating btn-light btn-lg"><i class="fa fa-dribbble"
                                    aria-hidden="true"></i></a>

                            <a type="button" class="btn btn-floating btn-light btn-lg"><i class="fa fa-twitter"
                                    aria-hidden="true"></i></a>

                            <a type="button" class="btn btn-floating btn-light btn-lg"><i class="fa fa-google-plus"
                                    aria-hidden="true"></i></a>

                        </div>
                    </div>
                </div>

            </div>

        </div>

        <div class="text-left p-3 border-top border-dark">
            <div class="row">
                <div class="col-6 column">
                    © TSHOP 2014.All right reserved
                </div>
                <div class="col-6 d-flex justify-content-end align-items-center">
                    <img class="mx-2" src="../img/visa.jpg" alt="" style="width:35px;">
                    <img class="mx-2" src="../img/viettin.png" alt="" style="width:35px;">
                    <img class="mx-2" src="../img/paypal.png" alt="" style="width:35px;">
                    <img class="mx-2" src="../img/mb.png" alt="" style="width:35px;">
                </div>
            </div>

        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-ENjdO4Dr2bkBIFxQpeoTz1HIcje39Wm4jDKdf19U8gI4ddQ3GYNS7NTKfAdVQSZe"
        crossorigin="anonymous"></script>

</body>

</html>