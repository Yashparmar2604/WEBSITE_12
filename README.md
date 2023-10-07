# WEBSITE_12

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="css.css">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <style>
        /* Custom styles for navigation bar */
             /* Custom styles for navigation bar */
             .navbar {
            background-color: #000;
            color: #fff;
        }

        /* Custom styles for the top section */
        #top {
            background-color: #0e6fc2;
            color: #fff;
            text-align: center;
            padding: 20px;
        }

        #top img {
            display: inline-block;
            vertical-align: middle;
        }

        #top h1 {
            display: inline-block;
            vertical-align: middle;
            margin-left: 10px;
        }

        /* Custom styles for the card */
        .custom-card {
            background-color: #0e6fc2;
            color: #fff;
            border: none;
            border-radius: 0;
            margin: 0;
            padding: 0;
        }

        .custom-card .card-header {
            background-color: #0a549d;
        }

        /* Custom styles for dropdown */
        .custom-dropdown {
            position: relative;
        }

        .custom-dropdown .dropdown-menu {
            display: none;
            position: absolute;
            top: 100%;
            left: 0;
            background-color: #2a7dd1;
            border: 1px solid #378cd7;
            border-radius: 0;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.15);
            margin: 0;
            padding: 0;
        }

        .custom-dropdown:hover .dropdown-menu {
            display: block;
        }

        /* Updated style for the last div */
        .solution-container {
            background-color: #0074e4; /* Blue background */
            color: #fff; /* White text color */
            padding: 20px;
            border-radius: 10px;
            text-align: center;
        }

        /* CSS for the heading */
        .solution-heading {
            font-size: 28px;
            font-weight: bold;
            margin-bottom: 20px;
        }

        /* CSS for the description */
        .solution-description {
            font-size: 18px;
            margin-bottom: 20px;
        }

        /* CSS for the list items */
        .additional-details li {
            list-style: none;
            margin: 5px 0;
        }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg bg-dark border-bottom border-body" data-bs-theme="dark">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Navbar</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNavDropdown">
            <ul class="navbar-nav">
              
                <li class="nav-item">
                    <a href="#contact-us">Contact Us</a>
                </li>
                
              <li class="nav-item">
                <a class="nav-link" href="#">ABOUT</a>
              </li>
            </ul>
          </div>
        </div>
    </nav>

    <div id="top">
        <img src="https://lh5.googleusercontent.com/p/AF1QipOJdgIcu5wIR6q9R_puXWUVgkSomN2TBUaxv4vi=w160-h160-k-no" alt="logo">
        <h1>WELCOME TO YASH ELECTRONICS</h1>
    </div>

    <div class="container-fluid p-0">
        <div class="card custom-card"> <!-- Apply custom card styles -->
            <div class="card-header">
                <h3>Services Provided</h3>
            </div>
            <div class="card-body">
                <div class="row">
                

                    <div class ="col-md-6">
                        <div class="custom-dropdown">
                            <button class="btn btn-link text-white">Mobile Repairing</button>
                            <div class="dropdown-menu">
                                <a class="dropdown-item" href="#">Charging Socket</a>
                                <a class="dropdown-item" href="#">Display Repairing</a>
                                <a class="dropdown-item" href="#">Battery Issues</a>
                                <a class="dropdown-item" href="#">Water Damage</a>
                                <a class="dropdown-item" href="#">Motherboard Issues</a>
                            </div>
                        </div>
                        
                        <div class="custom-dropdown">
                            <button class="btn btn-link text-white">TV Repairing</button>
                            <div class="dropdown-menu">
                                <a class="dropdown-item" href="#">Panel Repairing</a>
                                <a class="dropdown-item" href="#">Black Screen Issue</a>
                                <a class="dropdown-item" href="#">Red Light Issue</a>
                                <a class="dropdown-item" href="#">No Sound Issue</a>
                            </div>
                        </div>
                        
                    </div>
                    <div class="col-md-6">
                        <img src="your-image-url.jpg" alt="Service Image" class="img-fluid">
                    </div>
                </div>
            </div>
        </div>
    </div>


    <div class="solution-container">
        <h1 class="solution-heading">Electronics Solutions Hub</h1>
        <p class="solution-description">Your one-stop destination for all your electronics-related problems!</p>
        <p class="solution-description">Specialized in mobile and TV repairing services.</p>
        <p class="additional-details">We offer:</p>
        <ul class="additional-details">
            <li>Fast and reliable repairs for mobile devices and TVs</li>
            <li>Skilled technicians with years of experience</li>
            <li>Quality replacement parts</li>
            <li>Competitive pricing</li>
            <li>Convenient location and hours</li>
        </ul>
    </div>


  
    

    <footer style="background-color: #000; color: #fff;">
        <div id="contact-us">
        <div class="container">
            <div class="row">
                <div class="col-md-6">
                    <h4>Address:</h4>
                    <p>Ward 12/B, Plot 222,</p>
                    <p>Police Station Char Rasta,</p>
                    <p>Gandhidham, Kutch</p>
                </div>
                <div class="col-md-6">
                    <h4>Contact Information:</h4>
                    <p>Phone: <a href="tel:+919879551065">9879551065</a></p>
                    <p>Email: <a href="mailto:2009jayeahparmar@gmail.com">2009jayeahparmar@gmail.com</a></p>
                </div>
            </div>
        </div>
    </div>
    </footer>
    


    <!-- Bootstrap JavaScript (not used in this example) -->
</body>
</html>
