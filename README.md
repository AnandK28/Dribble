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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribble Clone</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body class="d-flex flex-column" style="height: 100vh;">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Dribble Clone</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Features</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Pricing</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Contact</a>
                    </li>
                    <li class="nav-item">
                        <button class="btn btn-outline-primary me-2">Sign In</button>
                    </li>
                    <li class="nav-item">
                        <button class="btn btn-primary">Sign Up</button>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="container-fluid mt-5 flex-grow-1">
        <div class="row">
            <div class="col-md-6">
                <h1>Welcome to Dribble Clone</h1>
                <p>Explore stunning designs and showcase your creative projects.</p>
                <button class="btn btn-primary">Get Started</button>
            </div>
            <div class="col-md-6">
                <img src="" class="img-fluid" alt="">
            </div>
        </div>
    </div>

    <div class="container-fluid mt-5 flex-grow-1">
        <div class="row text-center">
            <div class="col-md-3">
                <div class="card">
                    <img src="fa2.jpg" class="card-img-top" alt="White Frock" style="height: 400px; object-fit: cover;">
                    <div class="card-body">
                        <h5 class="card-title">White Frock</h5>
                        <p class="card-text">Price: ₹5000</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3">
                <div class="card">
                    <img src="fa3.jpg" class="card-img-top" alt="Sun Dress" style="height: 400px; object-fit: cover;">
                    <div class="card-body">
                        <h5 class="card-title">Sun Dress</h5>
                        <p class="card-text">Price: ₹7500</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3">
                <div class="card">
                    <img src="fa4.jpg" class="card-img-top" alt="Black Frock" style="height: 400px; object-fit: cover;">
                    <div class="card-body">
                        <h5 class="card-title">Black Frock</h5>
                        <p class="card-text">Price: ₹10000</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3">
                <div class="card">
                    <img src="fa5.jpg" class="card-img-top" alt="Flower Frock" style="height: 400px; object-fit: cover;">
                    <div class="card-body">
                        <h5 class="card-title">Flower Frock</h5>
                        <p class="card-text">Price: ₹8000</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <footer class="bg-light text-center py-3 mt-auto" style="width: 100%; max-width: 90%; margin: 0 auto;">
        <p>DESIGNED AND DEVELOPED BY ANAND K 24900721</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>


```


## OUTPUT:

![image](https://github.com/user-attachments/assets/9b5609ae-c4af-4511-8cc8-c15dea60a20f)





## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
