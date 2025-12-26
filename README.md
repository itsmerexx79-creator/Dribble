<img width="1052" height="522" alt="image" src="https://github.com/user-attachments/assets/bb5b32af-710c-4372-b100-11e88ff0f411" /># Project Responsive Web Design using Bootstrap
## Date:22.12.25

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
Design a navigation bar with links: Inspiration, Find Work, Learn Design, Go Pro, Sign In, Sign Up.

### Step 5:
Add a catchy headline with a search bar.

### Step 6:
Use ```<div>``` containers for each dribbble shot thumbnail.

### Step 7:
Include designer name and likes count below each image.

### Step 8:
Include text like “Find your next design inspiration” with a button (“Join Dribbble” or “Explore”).

### Step 9:
Create a footer with your name and register number.

### Step 10:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Responsive Bootstrap Page</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">My WebPage</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav me-auto">
          <li class="nav-item"><a class="nav-link active" href="#home">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        </ul>

        <!-- Search Bar -->
        <form class="d-flex" role="search">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-outline-light" type="submit">Search</button>
        </form>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section id="home" class="bg-light text-center py-5">
    <div class="container">
      <h1 class="display-4 fw-bold">Welcome to My Responsive Page</h1>
      <p class="lead">Designed using Bootstrap for a clean and modern look.</p>
      <a href="#about" class="btn btn-primary mt-3">Learn More</a>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="py-5">
    <div class="container">
      <h2 class="text-center mb-4">About</h2>
      <div class="row">
        <div class="col-md-6">
          <p>
            This is a simple responsive website built using Bootstrap. It includes a navbar, content sections, a footer, and now a search bar.
          </p>
        </div>
        <div class="col-md-6">
          <img src="images/ipl.png.png" class="img-fluid rounded shadow" alt="About image">
        </div>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="bg-light py-5">
    <div class="container">
      <h2 class="text-center mb-4">Projects</h2>
      <div class="row g-4">
        <div class="col-md-4">
          <div class="card shadow-sm">
            <img src="images/ipl1.png.png" class="card-img-top" alt="Project 1">
            <div class="card-body">
              <h5 class="card-title">Project One</h5>
              <p class="card-text">A short description of your project goes here.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card shadow-sm">
            <img src="images/ipl2.png.png" class="card-img-top" alt="Project 2">
            <div class="card-body">
              <h5 class="card-title">Project Two</h5>
              <p class="card-text">A short description of your project goes here.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card shadow-sm">
            <img src="images/ipl3.png.png" class="card-img-top" alt="Project 3">
            <div class="card-body">
              <h5 class="card-title">Project Three</h5>
              <p class="card-text">A short description of your project goes here.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-5">
    <div class="container text-center">
      <h2>Contact</h2>
      <p class="lead">You can reach me at <a href="mailto:example@email.com">example@email.com</a></p>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-3">
    <p class="mb-0">Designed by <strong>SANTHOSH REDDY K </strong></p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```


## OUTPUT:
<img width="1036" height="584" alt="Screenshot 2025-12-26 231714" src="https://github.com/user-attachments/assets/b013f04f-55e4-4a8e-9f0d-dcd0e37e301d" />
<img width="1052" height="522" alt="Screenshot 2025-12-26 231728" src="https://github.com/user-attachments/assets/3490cc5b-181b-436f-a36a-3e5b04a636f7" />


## RESULT:
The project for responsive web design in creating a clone of dribble.com is completed successfully.
