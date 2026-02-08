# Project Responsive Web Design using Bootstrap
# Date:08-02-2026
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
```
html 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Dribbble Style Landing Page</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

    <!-- Custom CSS -->
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

<!-- NAVBAR -->
<nav class="navbar navbar-expand-lg navbar-light bg-white shadow-sm fixed-top">
    <div class="container">
        <a class="navbar-brand fw-bold text-pink" href="#">Dribbble</a>

        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarMenu">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarMenu">
            <ul class="navbar-nav ms-auto align-items-center">
                <li class="nav-item"><a class="nav-link" href="#">Discover</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Jobs</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Designers</a></li>
                <li class="nav-item ms-2">
                    <a class="btn btn-pink" href="#">Sign Up</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<!-- HERO SECTION -->
<section class="hero-section text-center">
    <div class="container">
        <h1 class="fw-bold">Explore Creative Designs</h1>
        <p class="lead mt-3">
            Discover the world’s best UI, branding, and illustration work.
        </p>
        <p class="text-muted">
             <img src="sunmoon.jpg" alt="">
             </p>
        <div class="mt-4">
            <a href="#" class="btn btn-pink btn-lg me-2">Get Started</a>
            <a href="#" class="btn btn-outline-dark btn-lg">Learn More</a>
        </div>
    </div>
</section>

<!-- DESIGN CARDS -->
<section class="container my-5">
    <h2 class="text-center fw-bold mb-4">Popular Designs</h2>

    <div class="row g-4">
        <div class="col-lg-4 col-md-6">
            <div class="design-card">
                <img src="https://via.placeholder.com/400x260" alt="">
                <div class="p-3">
                    <h5>Mobile App UI</h5>
                    <p class="text-muted">Modern interface design</p>
                </div>
            </div>
        </div>

        <div class="col-lg-4 col-md-6">
            <div class="design-card">
                <img src="https://via.placeholder.com/400x260" alt="">
                <div class="p-3">
                    <h5>Brand Identity</h5>
                    <p class="text-muted">Creative branding concept</p>
                </div>
            </div>
        </div>

        <div class="col-lg-4 col-md-6">
            <div class="design-card">
                <img src="https://via.placeholder.com/400x260" alt="">
                <div class="p-3">
                    <h5>Illustration Art</h5>
                    <p class="text-muted">Digital illustration</p>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- CALL TO ACTION -->
<section class="cta-section text-center">
    <div class="container">
        <h2 class="fw-bold">Ready to showcase your work?</h2>
        <p class="mt-2">Join thousands of designers sharing their creativity.</p>
        <a href="#" class="btn btn-light btn-lg mt-3">Join Now</a>
    </div>
</section>

<!-- FOOTER -->
<footer class="footer text-center">
    <p class="mb-0">© 2025 Dribbble Clone | Responsive Web Design Project</p>
</footer>

<!-- Bootstrap JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>

css

body {
    font-family: 'Segoe UI', sans-serif;
    padding-top: 70px;
}

/* Pink Theme */
.text-pink {
    color: #ea4c89;
}

.btn-pink {
    background-color: #ea4c89;
    color: #fff;
    border-radius: 25px;
    padding: 10px 25px;
}

.btn-pink:hover {
    background-color: #d83c74;
    color: #fff;
}

/* Hero Section */
.hero-section {
    background: linear-gradient(135deg, #fdf0f6, #f9f8fd);
    padding: 100px 20px;
}

/* Cards */
.design-card {
    background: #fff;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 6px 15px rgba(0,0,0,0.1);
    transition: transform 0.3s;
}

.design-card img {
    width: 100%;
}

.design-card:hover {
    transform: translateY(-6px);
}

/* CTA Section */
.cta-section {
    background-color: #ea4c89;
    color: white;
    padding: 70px 20px;
}

/* Footer */
.footer {
    background-color: #111;
    color: #ccc;
    padding: 20px;
}
```
# OUTPUT:
<img width="1022" height="477" alt="image" src="https://github.com/user-attachments/assets/9f370659-4ec8-40f0-b022-6bfec1fee4c2" />
<img width="1017" height="455" alt="image" src="https://github.com/user-attachments/assets/8d5ce77e-836a-4291-ab41-d11c2af89c29" />


# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
