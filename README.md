[Pharma_README.md at main · rakshithaprakashkumar11_Pharma.pdf](https://github.com/sakamalesh/Pharma/files/15281134/Pharma_README.md.at.main.rakshithaprakashkumar11_Pharma.pdf)# Project Responsive Web Design using Bootstrap
## Date:

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


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
## HOME.HTML:
'''

        <!DOCTYPE html>
        <html lang="en">
        <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Pharmacy Company</title>
        <!-- Bootstrap CSS -->
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
        <!-- Custom CSS -->
        <style>
            /* Add your custom styles here */
            body {
            background-color: #f8f9fa;
            }
            .jumbotron {
            background-color: #007bff;
            color: #fff;
            }
            .footer {
            background-color: #343a40;
            color: #fff;
            padding: 20px 0;
            }
        </style>
        </head>
        <body>

        <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
            <div class="container">
            <a class="navbar-brand" href="#">MOIS Pharmacy </a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="parm.html">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="products.html">Products</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="about.html">About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="contact.html">Contact</a>
                </li>
                </ul>
            </div>
            </div>
        </nav>

        <div class="jumbotron jumbotron-fluid">
            <div class="container text-center">
            <h1 class="display-4">Welcome to our Pharmacy Company</h1>
            <p class="lead">Providing quality healthcare solutions</p>
            </div>
        </div>

        <div class="container">
            <div class="row">
            <div class="col-md-4 mb-4">
                <div class="card">
                <img src="med.jpeg" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">WORLD CLASS MEDICINE</h5>
                    <p class="card-text">WE PROVIDE WORLD CLASS MEDICINE</p>
                </div>
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="card">
                <img src="CHEM.jpeg" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">WORLD CLASS CHEMIST</h5>
                    <p class="card-text">WE HAVE THE BEST CHEMIST.</p>
                </div>
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="card">
                <img src="LOGO.jpeg" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">MOIS</h5>
                    <p class="card-text">WORLD CLASS BRAND.</p>
                </div>
                </div>
            </div>
            </div>
        </div>

        <footer class="footer text-center">
            <div class="container">
            <span>&copy; 2024 Pharmacy Company. All rights reserved.</span>
            </div>
        </footer>

        <!-- Bootstrap JS and dependencies -->
        <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
        <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
        <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
        </body>
        </html>

'''
  ## PRODUCTS.HTML:

'''

    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pharmacy Company</title>
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <!-- Custom CSS -->
    <style>
        /* Add your custom styles here */
        body {
        background-color: #f8f9fa;
        }
        .jumbotron {
        background-color: #007bff;
        color: #fff;
        }
        .footer {
        background-color: #343a40;
        color: #fff;
        padding: 20px 0;
        }
    </style>
    </head>
    <body>

    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
        <a class="navbar-brand" href="#">MOIS Pharmacy</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
            <li class="nav-item active">
                <a class="nav-link" href="parm.html">Home</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="products.html">Products</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="about.html">About</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="contact.html">Contact</a>
            </li>
            </ul>
        </div>
        </div>
    </nav>

    <div class="jumbotron jumbotron-fluid">
        <div class="container text-center">
        <h1 class="display-4">PRODUCTS</h1>
        <p class="lead">WORLD CLASS MEDICINE</p>
        </div>
    </div>

    <div class="container">
        <div class="row">
        <div class="col-md-4 mb-4">
            <div class="card">
            <img src="citi.jpeg" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">CITIRON</h5>
            
            <a href="#" class="btn btn-primary">Buy Now</a>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="dolo.jpeg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">DOLO 650</h5>
            
            <a href="#" class="btn btn-primary">Buy Now</a>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="amir.jpeg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Amrutanjan BALM</h5>
           
            <a href="#" class="btn btn-primary">Buy Now</a>
          </div>
        </div>
      </div>
    </div>
    </div>

    <footer class="footer text-center">
        <div class="container">
        <span>&copy; 2024 Pharmacy Company. All rights reserved.</span>
        </div>
    </footer>

    <!-- Bootstrap JS and dependencies -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    </body>
    </html>

'''
   ## ABOUT.HTML:

'''

    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pharmacy Company</title>
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <!-- Custom CSS -->
    <style>
        /* Add your custom styles here */
        body {
        background-color: #f8f9fa;
        }
        .jumbotron {
        background-color: #007bff;
        color: #fff;
        }
        .footer {
        background-color: #343a40;
        color: #fff;
        padding: 20px 0;
        }
    </style>
    </head>
    <body>

    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
        <a class="navbar-brand" href="#">MOIS Pharmacy </a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
            <li class="nav-item active">
                <a class="nav-link" href="parm.html">Home</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="products.html">Products</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="about.html">About</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="contact.html">Contact</a>
            </li>
            </ul>
        </div>
        </div>
    </nav>

    <div class="jumbotron jumbotron-fluid">
        <div class="container text-center">
        <h1 class="display-4">ABOUT US</h1>
        <p class="lead">PEOPLE MAKE PLACES STRONGER</p>
        </div>
    </div>

    <div class="container">
        <div class="row">
        <div class="col-md-4 mb-4">
            <div class="card">
            <img src="kamalesh2.jpeg" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">KAMALESH</h5>
                <p class="card-text">FOUNDER</p>
            </div>
            </div>
        </div>
        <div class="col-md-3 mb-4">
            <div class="card">
            <img src="kiran.jpg" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">KIRAN</h5>
                <p class="card-text">MANAGING DIRECTOR</p>
            </div>
            </div>
        </div>
        <div class="col-md-3 mb-4">
            <div class="card">
            <img src="PRADEEP.jpg" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">PRADEEP</h5>
                <p class="card-text">CEO</p>
            </div>
            </div>
        </div>
        </div>
    </div>

    <footer class="footer text-center">
        <div class="container">
        <span>&copy; 2024 Pharmacy Company. All rights reserved.</span>
        </div>
    </footer>

    <!-- Bootstrap JS and dependencies -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    </body>
    </html>

'''
   ## CONTACT.HTML:
'''

        <!DOCTYPE html>
        <html lang="en">
        <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Pharmacy Company</title>
        <!-- Bootstrap CSS -->
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
        <!-- Custom CSS -->
        <style>
            /* Add your custom styles here */
            body {
            background-color: #f8f9fa;
            }
            .jumbotron {
            background-color: #007bff;
            color: #fff;
            }
            .footer {
            background-color: #343a40;
            color: #fff;
            padding: 20px 0;
            }
        </style>
        </head>
        <body>

        <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
            <div class="container">
            <a class="navbar-brand" href="#">MOIS Pharmacy </a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="parm.html">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="products.html">Products</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="about.html">About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="contact.html">Contact</a>
                </li>
                </ul>
            </div>
            </div>
        </nav>

        <div class="jumbotron jumbotron-fluid">
            <div class="container text-center">
                <h1 class="display-4">CONTACT US</h1>
            </div>
            

        </div><div class="container">
            <div class="row">
            <div class="col-md-5 mb-5">
                <div class="card">
                
                    <p> <b >Address</b></p>
                    <p >13 ANNA STREET</p>
                    <p >, ANNA NAGAR</p>
                    <p >TAMIL NADU-600001</p>
                    <b >Email:</b>
                    <p >kdsis@gmail.com</p>
                    <b >Phone</b>
                    <p >9600141495</p>
                </div>
                </div>
            </div>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>

        <footer class="footer text-center">
            <div class="container col-12">
            <span>&copy; 2024 Pharmacy Company. All rights reserved.</span>
            </div>
        </footer>

        <!-- Bootstrap JS and dependencies -->
        <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
        <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
        <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
        </body>
        </html>


'''

## OUTPUT:
## HOME.HTML:
![alt text](<Screenshot 2024-05-11 062220.png>)
## PRODUCTS.HTML:
![alt text](<Screenshot 2024-05-11 062239.png>)
## ABOUT.HTML:
![alt text](<Screenshot 2024-05-11 062333.png>)
## CONTACT.HTML:
![alt text](<Screenshot 2024-05-11 062513.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
