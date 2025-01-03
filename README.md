# Project Responsive Web Design using Bootstrap
## Date:30/12/2024

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
    <title>Dribbble</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand fw-bold text-warning" href="#">Dribbble</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav me-auto">
                    <li class="nav-item"><a class="nav-link text-white" href="#">Designers</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Teams</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Community</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Jobs</a></li>
                </ul>
            </div>
            <a class="btn btn-outline-light me-2" href="#">Sign in</a>
            <a class="btn btn-outline-light me-2 btn bg-primary" href="#">Log In</a>
            
        </div>
    </nav>
    <header class="bg-dark text-white py-3">
        <div class="container text-center">
            <h1>Dribbble</h1>
            <p>Discover the world’s top designers & creatives</p>
        </div>
    </header>

    <main class="container my-4">
        <div class="row">
            
            <div class="col-md-4">
                <div class="card">
                    <img src="Fibo Studio.png" class="card-img-top" alt="Design 1">
                    <div class="card-body">
                        <h5 class="card-title">Fibo Studio</h5>
                        <h4><a href="#" class="btn btn-primary">Discover</a> 🩷3k  👁️5k</h4>
                    </div>
                </div>
            </div>

            
            <div class="col-md-4">
                <div class="card">
                    <img src="Illiyin Studio.png" class="card-img-top" alt="Design 2">
                    <div class="card-body">
                        <h5 class="card-title">Illiyin Studio</h5>
                        <h4><a href="#" class="btn btn-primary">Discover</a> 🩷8k  👁️8.23k</h4>
                    </div>
                </div>
            </div>

            
            <div class="col-md-4">
                <div class="card">
                    <img src="Kasper Carlsen.png" class="card-img-top" alt="Design 3">
                    <div class="card-body">
                        <h5 class="card-title">Kasper Carlsen</h5>
                        <h4><a href="#" class="btn btn-primary">Discover</a> 🩷8k  👁️11.5k</h4>
                    </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="card">
                    <img src="khibib.png" class="card-img-top" alt="Design 3">
                    <div class="card-body">
                        <h5 class="card-title">khibib</h5>
                        <h4><a href="#" class="btn btn-primary">Discover</a> 🩷7k  👁️2.6k</h4>
                    </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="card">
                    <img src="Lumios Digital.png" class="card-img-top" alt="Design 3">
                    <div class="card-body">
                        <h5 class="card-title">Lumios Digital</h5>
                        <h4><a href="#" class="btn btn-primary">Discover</a> 🩷9k  👁️10.2k</h4>
                    </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="card">
                    <img src="Lyssna.png" class="card-img-top" alt="Design 3">
                    <div class="card-body">
                        <h5 class="card-title">Lyssna</h5>
                        <h4><a href="#" class="btn btn-primary">Discover</a> 🩷800k  👁️2.2k</h4>
                    </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="card">
                    <img src="Modall.png" class="card-img-top" alt="Design 3">
                    <div class="card-body">
                        <h5 class="card-title">Modall</h5>
                        <h4><a href="#" class="btn btn-primary">Discover</a> 🩷1.1k  👁️1.8k</h4>
                    </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="card">
                    <img src="Renato Mandic.png" class="card-img-top" alt="Design 3">
                    <div class="card-body">
                        <h5 class="card-title">Renato Mandic</h5>
                        <h4><a href="#" class="btn btn-primary">Discover</a> 🩷3.2k  👁️4.2k</h4>
                    </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="card">
                    <img src="strangelabs.png" class="card-img-top" alt="Design 3">
                    <div class="card-body">
                        <h5 class="card-title">strangelabs</h5>
                        <h4><a href="#" class="btn btn-primary">Discover</a> 🩷5k  👁️5.2k</h4>
                    </div>
                </div>
            </div>
        </div>
    </main>

    <footer class="bg-dark text-white text-center py-3">
        <p>&copy; 2024 Dribbble. All Rights Reserved.<br>
                   Designed & Developed by B.THAVANESH</p>
    </footer>
</body>
</html>

```


## OUTPUT:

![alt text](<Screenshot (77).png>)
![alt text](<Screenshot (78).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
