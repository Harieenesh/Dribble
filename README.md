# Project Responsive Web Design using Bootstrap
## Date:26/12/2024

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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PHARMACY COMPANY</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        /* Global Styles */
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f9fa;
            margin: 0;
            padding: 0;
        }

        /* Navigation Bar */
        .navbar {
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .navbar-brand {
            font-weight: bold;
            color: #007bff;
        }
        .navbar-nav .nav-link {
            color: #555;
            font-weight: 500;
        }
        .navbar-nav .nav-link.active {
            color: #007bff;
        }

        /* Main Content */
        #home h1 {
            font-size: 2.5rem;
            color: #333;
        }
        #home p {
            font-size: 1.2rem;
            color: #666;
        }

        /* About Section */
        #about {
            background-color: #e9ecef;
            padding: 20px;
            border-radius: 5px;
        }

        /* Products Section */
        #products .card {
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        #products .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 12px rgba(0, 0, 0, 0.2);
        }
        #products .card-title {
            color: #007bff;
        }

        /* Contact Section */
        #contact {
            background-color: #f8f9fa;
            padding: 20px;
            border-radius: 5px;
        }
        #contact .btn-primary {
            background-color: #800661;
            border: none;
        }

        /* Footer */
        footer {
            background-color: #0cd88d;
            color: rgb(122, 178, 18);
            padding: 15px 0;
        }
        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Pharmacy&Co.</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">About Us</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#products">Products</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Main Content -->
    <div class="container mt-4">
        <div id="home" class="text-center">
            <h1>Welcome to Pharmacy&Co.</h1>
            <p>Your health is our priority. Explore our range of medicines and healthcare products.</p>
        </div>

        <!-- About Section -->
        <div id="about" class="mt-5">
            <h2>About Us</h2>
            <p>Pharmacy Co. is dedicated to providing high-quality medicines and excellent customer service. With a wide range of products, we strive to ensure the health and well-being of our customers.</p>
        </div>

        <!-- Products Section -->
        <div id="products" class="mt-5">
            <h2>Our Products</h2>
            <div class="row">
                <div class="col-md-4">
                    <div class="card">
                        <div class="card-body">
                            <h5 class="card-title">Product 1</h5>
                            <p class="card-text">Description of Product 1.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <div class="card-body">
                            <h5 class="card-title">Product 2</h5>
                            <p class="card-text">Description of Product 2.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <div class="card-body">
                            <h5 class="card-title">Product 3</h5>
                            <p class="card-text">Description of Product 3.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Contact Section -->
        <div id="contact" class="mt-5">
            <h2>Contact Us</h2>
            <form>
                <div class="mb-3">
                    <label for="name" class="form-label">Name</label>
                    <input type="text" class="form-control" id="name" placeholder="Your Name">
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Email</label>
                    <input type="email" class="form-control" id="email" placeholder="Your Email">
                </div>
                <div class="mb-3">
                    <label for="message" class="form-label">Message</label>
                    <textarea class="form-control" id="message" rows="3" placeholder="Your Message"></textarea>
                </div>
                <button type="submit" class="btn btn-primary">Submit</button>
            </form>
        </div>
    </div>

    <!-- Footer -->
    <footer class="text-center py-3 mt-5">
        <p>Designed and Developed by Mr , SHA Harieenesh</p>
    </footer>

    <!-- Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot 2024-12-26 195711.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
