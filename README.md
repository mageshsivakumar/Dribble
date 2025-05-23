# Project Responsive Web Design using Bootstrap
## Date:23-05-25

## AIM:
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
    <title>Dribbble Clone</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons/font/bootstrap-icons.css" rel="stylesheet">
</head>

<body>
    
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a class="navbar-brand" href="#">Dribbble Clone</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#">Shots</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Designers</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Teams</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Jobs</a></li>
                    <li class="nav-item"><a class="btn btn-primary btn-sm" href="#">Sign Up</a></li>
                </ul>
            </div>
        </div>
    </nav>

    
    <div class="bg-dark text-white text-center py-4">
        <h2>What are you working on? Dribbble is show and tell for designers.</h2>
        <div class="mt-3">
            <a href="#" class="btn btn-light btn-sm">Learn more</a>
            <a href="#" class="btn btn-danger btn-sm">Sign up</a>
        </div>
    </div>

    
    <div class="container py-4">
        <h3 class="mb-4">Popular Shots</h3>
        <div class="row g-4">
            
            <div class="col-md-3">
                <div class="card">
                    <img src="2p.png" class="card-img-top" alt="Design 1">
                    <div class="card-body">
                        <p class="card-text">Famous</p>
                        <p><i class="bi bi-eye"></i> 4,044 | <i class="bi bi-heart"></i> 290</p>
                    </div>
                </div>
            </div>
            
            <div class="col-md-3">
                <div class="card">
                    <img src="images.jpeg" class="card-img-top" alt="Design 2">
                    <div class="card-body">
                        <p class="card-text">Balkan Brothers</p>
                        <p><i class="bi bi-eye"></i> 2,404 | <i class="bi bi-heart"></i> 236</p>
                    </div>
                </div>
            </div>
            
            <div class="col-md-3">
                <div class="card">
                    <img src="4p.png" class="card-img-top" alt="Design 3">
                    <div class="card-body">
                        <p class="card-text">Roman reigns</p>
                        <p><i class="bi bi-eye"></i> 3,885 | <i class="bi bi-heart"></i> 264</p>
                    </div>
                </div>
            </div>
            
            <div class="col-md-3">
                <div class="card">
                    <img src="5p.png" class="card-img-top" alt="Design 4">
                    <div class="card-body">
                        <p class="card-text">The Rock</p>
                        <p><i class="bi bi-eye"></i> 2,602 | <i class="bi bi-heart"></i> 186</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    
    <footer class="bg-light text-center py-3">
        <p class="mb-0"> S MAGESH (2025 Dribbble Clone.)</p>
    </footer>


    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>

```


## OUTPUT:
![Screenshot 2025-05-23 101329](https://github.com/user-attachments/assets/7521caec-e0ce-45b9-89a0-414fd20d3d51)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
