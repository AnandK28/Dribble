# Project Responsive Web Design using Bootstrap
## Date:
28-12-2054
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dress Shop</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand fw-bold text-danger" href="#">Dress Shop</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav me-auto">
                    <li class="nav-item"><a class="nav-link text-white" href="#">Home</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#collection">Collection</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#about">About Us</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#contact">Contact</a></li>
                </ul>
            </div>
            <a class="btn btn-outline-light me-2" href="#">Sign in</a>
            <a class="btn btn-outline-light me-2" href="#">Sign Up</a>
            <input type="search" class="form-control w-auto" placeholder="Search" style="margin: 20px;">
        </div>
    </nav>

    <section id="home" class="bg-light py-5" style="height: 45vh;">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-6 text-center text-md-start">
                    <h1 class="display-4 fw-bold">Discover Your Perfect Look</h1>
                    <p class="my-3">Explore our collection of elegant and trendy dresses for every occasion.</p>
                    <button class="btn btn-secondary me-2">Shop Now</button>
                    <button class="btn btn-primary">Learn More</button>
                </div>
                <div class="col-md-6 text-center" height="100">
                    <img src="fa1.jpg" class="img-fluid" alt="Fashionable Dresses" style="height: 45vh;">
                </div>
            </div>
        </div>
    </section>

    <section id="collection" class="py-5">
        <div class="container">
            <div class="row mb-4">
                <div class="col-md-4">
                    <h2 class="fw-bold">Our Collection</h2>
                </div>
                <div class="col-md-4 text-center">
                    <button class="btn btn-outline-dark">New Arrivals</button>
                    <button class="btn btn-outline-dark">Best Sellers</button>
                </div>
            </div>
            <div class="row g-4">
                <div class="col-md-3 col-sm-6">
                    <div class="card" height="100">
                        <img src="fa2.jpg" class="card-img-top" alt="Dress 1">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">Elegant Evening Gown</p>
                            <p class="text-muted">$120.00</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card" height="100">
                        <img src="fa3.jpg" class="card-img-top" alt="Dress 2">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">Casual Summer Dress</p>
                            <p class="text-muted">$80.00</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card" height="100">
                        <img src="fa4.jpg" class="card-img-top" alt="Dress 3">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">Classic Black Dress</p>
                            <p class="text-muted">$100.00</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card" height="100">
                        <img src="fa5.jpg" class="card-img-top" alt="Dress 4">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">Floral Maxi Dress</p>
                            <p class="text-muted">$95.00</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-dark text-white py-3">
        <div class="container text-center">
            <p class="mb-0">Designed and developed by Anand K (24900721)</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```


## OUTPUT:
![Uploading image.png…]()
![Uploading image.png…]()



## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
