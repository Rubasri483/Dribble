# Project Responsive Web Design using Bootstrap
## Date:14/05/2025

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
<head>
  <title>Dribble | Kdrama website</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .heading {
      font-family: Arial, Helvetica, sans-serif;
      font-style: italic;
      background-color: rgba(206, 136, 32, 0.89);
      color: black;
      text-align: center;
      padding: 20px 0;
    }

    body {
      background-color: #f5f5f569;
      margin: 0;
      font-family: Arial, sans-serif;
    }

    .card-container {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
      margin-top: 30px;
    }

    .card {
      width: 300px;
      border: 1px solid #ddd;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      overflow: hidden;
      background-color: #fff;
      transition: transform 0.3s;
     
    }

    .card:hover {
      transform: scale(1.03);
    }

    /* Increase the size of the image */
    .card img {
      width: 100%;
      height: 200px;  /* Increased image height */
      object-fit: cover;  /* Keep the aspect ratio of the image */
    }

    /* Decrease the card content */
    .card-content {
      padding: 10px 15px;  /* Reduced padding */
      text-align: center;
      font-size: 14px;  /* Decreased font size */
    }

    .card-content h3 {
      margin: 5px 0;  /* Reduced margin */
      font-size: 18px;  /* Smaller font size for the title */
    }

    .card-content p {
      color: #7a0a4c;
      font-size: 12px;  /* Decreased font size for description */
    }

    .text {
      background-color: #555555de;
      color: rgb(224, 221, 10);
      text-align: center;
      padding: 10px 0;
    }
    .heading1{
         font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
         font-style: italic;
    }

  </style>
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-light bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#" style="font-family: fantasy; color: aliceblue;">Dribbble</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="home.html" style="color: aliceblue;">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="search.html" style="color: aliceblue;">Search</a></li>
          <li class="nav-item"><a class="nav-link" href="login.html" style="color: aliceblue;">Login Up</a></li>
          <li class="nav-item"><a class="nav-link" href="sub.html" style="color: aliceblue;">Subscribe</a></li>
        </ul>
      </div>
    </div>
  </nav>
  
  <div class="heading">
    <h1>Explore All Asian Dramas Here!!!</h1>
  </div>
<div class="heading1">
    <h4>Adventurous and Thrilling</h4>
  </div><hr color="black">
  <div class="card-container">
    <div class="card">
      <img src="drama1.1.jpg" alt="Drama Image">
      <div class="card-content">
        <h3>VINCENZO</h3>
        <p>Created by: Studio Dragon
            Genres: Korean drama, Action, Thriller, Crime, Comedy, Mafia · </p>
      </div>
    </div>
    <div class="card">
      <img src="drama2.jpg" alt="Drama Image">
      <div class="card-content">
        <h3>TAXI DRIVER</h3>
        <p>No. of seasons: 2
        First episode date: 9 April 2021 (South Korea)
        Genres: Action, Thriller, Drama, Revenge tragedy, Crime · See more
        Directed by: Park Joon-woo (season 1) </p>
      </div>
    </div>
    <div class="card">
      <img src="drama3.jpg" alt="Drama Image">
      <div class="card-content">
        <h3>BEYOND EVIL</h3>
        <p>No. of episodes: 16
         Genres: Korean drama, Drama, Suspense, Thriller, Mystery Composer: Ha Geun-young </p>
      </div>
    </div>
    <div class="card">
      <img src="drama4.jpg" alt="Drama Image">
      <div class="card-content">
        <h3>A SHOP FOR KILLERS</h3>
        <p>Starring: Lee Dong-wook; Kim Hye-jun
         No. of episodes: 8 
          No. of seasons: 2</p>
      </div>
    </div>
  </div><br>
  <div class="heading1">
    <h4>Fantasy</h4>
  </div><hr color="black">
<div class="card-container">
    <div class="card">
      <img src="drama5.1.jpg" alt="Drama Image">
      <div class="card-content">
        <h3>GUARDIAN</h3>
        <p>Created by: Lee Eun Bok
           n his quest for a bride to break his immortal curse, Dokkaebi, a 939-year-old guardian of souls, meets a grim reaper and a sprightly student with a tragic past. </p>
      </div>
    </div>
    <div class="card">
      <img src="drama6.jpg" alt="Drama Image">
      <div class="card-content">
        <h3>DASHING YOUTH  </h3>
        <p>Dashing Youth is a 2024 Chinese action fantasy drama directed by Chen Zhou Fei, based on the novel Shao Nian Bai Ma Zui Chun Feng </p>
      </div>
    </div>
    <div class="card">
      <img src="drama7.jpg" alt="Drama Image">
      <div class="card-content">
        <h3>Doom At your service  </h3>
        <p>Genres: Romance, Horror, Action, Comedy, War, Musical No. of episodes: 16</p>
      </div>
    </div>
    </div>
</body>
serach page
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Search Page</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .hero-section {
      background-color: #f8f9fa;
      padding: 50px 0;
      text-align: center;
    }
    .search-container {
      max-width: 600px;
      margin: 0 auto;
    }
    .heading {
      font-family: Arial, Helvetica, sans-serif;
      font-style: italic;
      background-color: rgba(206, 136, 32, 0.89);
      color: black;
      text-align: center;
      padding: 20px 0;
    }

    body {
      background-color: #f5f5f569;
      margin: 0;
      font-family: Arial, sans-serif;
    }
    .bgimage{
        background-image: url("search1.jpg");
        height: 100vh;
        background-size: cover;
    }
    
  </style>
</head>
<body>
    <div class="bgimage">
  <!-- Hero Section -->
   <nav class="navbar navbar-expand-lg navbar-light bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#" style="font-family: fantasy; color: aliceblue;">Dribbble</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="home.html" style="color: aliceblue;">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="search.html" style="color: aliceblue;">Search</a></li>
          <li class="nav-item"><a class="nav-link" href="login.html" style="color: aliceblue;">Login Up</a></li>
          <li class="nav-item"><a class="nav-link" href="sub.html" style="color: aliceblue;">Subscribe</a></li>
        </ul>
      </div>
    </div>
  </nav>
  <div class="hero-section">
    <div class="container">
      <h1 class="display-4">Welcome to DRIBBLE </h1>
      <p class="lead">Find whatever drama you want in our website</p>
    </div>
  </div>

  <!-- Search Form -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <div class="search-container">
          <form action="#" method="get">
            <div class="input-group">
              <input type="text" class="form-control" placeholder="Search..." name="search" id="search" required>
              <div class="input-group-append">
                <button class="btn btn-primary" type="submit">
                  <i class="fas fa-search"></i> Search
                </button>
              </div>
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>

  <!-- Search Results (Optional) -->
  <div class="container mt-5">
    <h3>Search Results:</h3>
    <div class="list-group" id="search-results">
      <!-- Dynamic results will be added here -->
    </div>
  </div>

  <!-- Bootstrap and FontAwesome JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
  <script src="https://kit.fontawesome.com/a076d05399.js"></script>
  </div>
</body>
</html>
subscribe
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Subscription Page</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .hero-section {
      background-color: #f8f9fa;
      padding: 60px 0;
      text-align: center;
      color: #495057;
    }
    .subscription-container {
      max-width: 600px;
      margin: 0 auto;
      padding: 30px;
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }
    .subscription-form input {
      border-radius: 30px;
    }
    .btn-subscribe {
      border-radius: 30px;
    }
    .footer {
      background-color: #343a40;
      color: white;
      padding: 20px 0;
      text-align: center;
    }
  </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#" style="font-family: fantasy; color: aliceblue;">Dribbble</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="home.html" style="color: aliceblue;">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="search.html" style="color: aliceblue;">Search</a></li>
          <li class="nav-item"><a class="nav-link" href="login.html" style="color: aliceblue;">Login Up</a></li>
          <li class="nav-item"><a class="nav-link" href="subscription.html" style="color: aliceblue;">Subscribe</a></li>
        </ul>
      </div>
    </div>
  </nav>
  <!-- Hero Section -->
  <div class="hero-section">
    <div class="container">
      <h1 class="display-4">Stay Updated with Our Latest News!</h1>
      <p class="lead">Subscribe to our newsletter and never miss an update.</p>
    </div>
  </div>

  <!-- Subscription Form -->
  <div class="container mt-5">
    <div class="subscription-container">
      <h2 class="text-center">Subscribe Now</h2>
      <form action="#" method="POST" class="subscription-form">
        <div class="form-group">
          <label for="email">Enter your email address:</label>
          <input type="email" class="form-control" id="email" name="email" placeholder="Email address" required>
        </div>
        <div class="form-group text-center">
          <button type="submit" class="btn btn-primary btn-subscribe">Subscribe</button>
        </div>
      </form>
      <p class="text-center text-muted">No spam, we promise!</p>
    </div>
  </div>

  <!-- Footer Section -->
  <div class="footer">
    <p>&copy; 2025 Dribble. All rights reserved.</p>
  </div>

  <!-- Bootstrap JS and dependencies -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
  
</body>
</html>
login page
<html>
    <head>
        <title>Contact Us|The Gilded Spoon</title>
          <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

        <style>
     nav {
      background-color: black;
      color: white;
      padding: 10px;
      display: flex;
      justify-content: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
    }
    .heading{
        background-color: rgba(0, 0, 0, 0.384);
        color: rgba(219, 235, 8, 0.719);
        font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        font-style:italic;
        text-align:center;
    }
    .text1{
        height:500px;
        width:500px;
        background-color: rgba(4, 70, 145, 0.678);
        color:black;
        text-align: left;
        border-radius:5px;
        border-width: 10px solid black;
   
    }
    .align{
        text-align: center;
        display: flex;
        justify-content: center;
    }
    .text2{
        background-color: green;
        color: white;
        height:30px;
        width:500px;
    }
    .text3{
        text-align: center;
    }
    .btn{
        background-color: green;
        color:white;
        border-radius: 5px;
        border-width: 5px;
        border-color: black;
    }
    .btn-align{
        text-align: center;
    }
     body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-image: url("login.jpg");
  height:100vh;
  background-size: cover;
}
        </style>
    </head>
    <body>
        <nav class="navbar navbar-expand-lg navbar-light bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#" style="font-family: fantasy; color: aliceblue;">Dribbble</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="home.html" style="color: aliceblue;">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="search.html" style="color: aliceblue;">Search</a></li>
          <li class="nav-item"><a class="nav-link" href="login.html" style="color: aliceblue;">Login Up</a></li>
          <li class="nav-item"><a class="nav-link" href="sub.html" style="color: aliceblue;">Subscribe</a></li>
        </ul>
      </div>
    </div>
  </nav>
  <div class="align">
    <div class="text1">
    <div class="text2">
       <h3 class="text3"> Login/signup </h3></div>
    <form>
        <br>
       UserName:
        <input type="text" ><br><br><br>
        Email Id:
        <input type="text" ><br><br><br>
       Password:
        <input type="text"><br><br><br>
       
       <button class="btn">
        Submit</button><br><br>
        <button class="btn">
        forget password</button>

    </form>

    </div>
  </div>
 
    </body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2025-05-14 114621.png>)

![alt text](<Screenshot 2025-05-14 114649.png>)

![alt text](<Screenshot 2025-05-14 114722.png>)

![alt text](<Screenshot 2025-05-14 114704.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
