<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Foodie's Paradise</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
    <style>
        /* Custom CSS styles */
        .carousel-caption {
            background-color: rgba(0, 0, 0, 0.5);
            padding: 20px;
            border-radius: 10px;
        }
        .card-img-overlay {
            background-color: rgba(0, 0, 0, 0.5);
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Foodie's Paradise</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#about">About</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#menu" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Menu
                </a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#starters">Starters</a></li>
                  <li><a class="dropdown-item" href="#mains">Mains</a></li>
                  <li><a class="dropdown-item" href="#desserts">Desserts</a></li>
                </ul>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#contact">Contact</a>
              </li>
            </ul>
            <form class="d-flex" role="search">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-outline-success" type="submit">Search</button>
            </form>
          </div>
        </div>
      </nav>

      <!-- Carousel -->
      <div id="carouselExampleDark" class="carousel carousel-dark slide" data-bs-ride="carousel">
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="https://source.unsplash.com/1600x900/?food,restaurant" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Welcome to Foodie's Paradise</h5>
                    <p>Indulge in a culinary journey like no other.</p>
                </div>
            </div>
            <!-- Add more carousel items as needed -->
        </div>
        <!-- Carousel controls -->
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
      <br>

      <div class="container">
        <!-- About Section -->
        <div id="about">
            <h2 class="text-center">About Foodie's Paradise</h2>
            <br>
            <p class="text-center">At Foodie's Paradise, we don't just serve food; we create memories. Our passion for cooking and dedication to quality ensure that every dish we serve is a masterpiece. Come, experience culinary bliss with us!</p>
            <hr>
        </div>

        <!-- Menu Section -->
        <div id="menu">
            <h2 class="text-center">Our Menu</h2>
            <br>
            <div class="row row-cols-1 row-cols-md-3 g-4">
                <!-- Starters -->
                <div class="col">
                    <div class="card h-100">
                        <img src="https://source.unsplash.com/400x300/?starters" class="card-img-top" alt="...">
                        <div class="card-img-overlay d-flex align-items-end">
                            <h5 class="text-light">Starters</h5>
                        </div>
                    </div>
                </div>
                <!-- Mains -->
                <div class="col">
                    <div class="card h-100">
                        <img src="https://source.unsplash.com/400x300/?mains" class="card-img-top" alt="...">
                        <div class="card-img-overlay d-flex align-items-end">
                            <h5 class="text-light">Mains</h5>
                        </div>
                    </div>
                </div>
                <!-- Desserts -->
                <div class="col">
                    <div class="card h-100">
                        <img src="https://source.unsplash.com/400x300/?desserts" class="card-img-top" alt="...">
                        <div class="card-img-overlay d-flex align-items-end">
                            <h5 class="text-light">Desserts</h5>
                        </div>
                    </div>
                </div>
            </div>
            <br><br>
        </div>

        <!-- Contact Section -->
        <div id="contact">
            <h2 class="text-center">Contact Us</h2>
            <br>
            <div class="container-sm d-flex justify-content-center">
                <p class="text-center">Ready to embark on a culinary adventure? Reach out to us!</p>
            </div>
           
