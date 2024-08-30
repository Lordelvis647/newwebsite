<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Apostolic Church Of Ghana</title>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <!-- Font Awesome for Social Media Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">

    <style>
        /* General Reset and Font */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Roboto', sans-serif;
        }

        /* Set the background image */
        body {
            background-image: url("download (1).jpeg");  /* Ensure the image path is correct */
            background-size: cover;  /* Ensure the image covers the entire background */
            background-repeat: no-repeat;  /* Prevent repeating the image */
            background-position: center center;  /* Center the image */
            background-attachment: fixed;  /* Make the background fixed while scrolling */
            color: white;  /* Default text color */
            padding: 20px;
            position: relative;
            min-height: 100vh;
        }

        /* Style the navigation bar */
        nav {
            background-color: rgba(0, 0, 0, 0.8); /* Semi-transparent background */
            padding: 10px;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.3);
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        /* Logo Styling */
        .logo img {
            width: 150px; /* Adjust width as needed */
            height: auto; /* Maintain aspect ratio */
        }

        /* Style the navigation links */
        nav a {
            color: rgb(255, 255, 255);
            padding: 14px 20px;
            margin: 0 10px;
            text-decoration: none;
            font-size: 18px;
            display: inline-block;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        nav a:hover {
            background-color: #45a049;  /* Change background color on hover */
        }

        /* Main Heading */
        h1 {
            color: lightblue;
            text-align: center;
            padding-top: 100px;
            font-size: 3em;
            text-shadow: 2px 2px 5px black;
        }

        /* Paragraph styling */
        p {
            text-align: center;
            font-size: 18px;
            line-height: 1.6;
            margin: 20px 0;
            background-color: rgba(0, 0, 0, 0.5);  /* Semi-transparent background */
            padding: 15px;
            border-radius: 10px;
        }

        /* Content Section */
        .content {
            margin-top: 50px;
            text-align: center;
        }

        .content h2 {
            color: yellow;
            margin-bottom: 20px;
        }

        /* Footer Styling */
        footer {
            background-color: rgba(0, 0, 0, 0.8);
            padding: 20px;
            text-align: center;
            position: absolute;
            bottom: 0;
            width: 100%;
        }

        footer p {
            color: white;
            margin-bottom: 10px;
        }

        /* Social Media Icons */
        .social-icons a {
            color: white;
            margin: 0 10px;
            font-size: 24px;
            transition: color 0.3s;
        }

        .social-icons a:hover {
            color: #45a049;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            h1 {
                font-size: 2.5em;
            }

            p {
                font-size: 16px;
            }

            nav a {
                font-size: 16px;
                padding: 10px 15px;
            }

            .social-icons a {
                font-size: 20px;
            }

            .logo img {
                width: 100px; /* Smaller logo for mobile */
            }
        }
    </style>
</head>
<body>

    <!-- Navigation Bar -->
    <nav>
         
        <div class="nav-links">
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Contact</a>
        </div>
    </nav>

    <!-- Main Section -->
    <h1>The Apostolic Church Of Ghana</h1>
    <p>
        Christ Apostolic Church is an indigenous African church founded by members of Precious Stone Society (Faith Tabernacle) after separating from The Apostolic Church in 1940.
        The church's history is linked to its founders, namely Isaac Babalola Akinyele, Joseph Ayo Babalola, David Odubanjo, Joseph Esinsinade, and Miss Sophia Odunlami.
    </p>
    <p>
        Before then, Christ Apostolic Church and The Apostolic Church (called Diamond or Precious Stone at that time) were found in some places in Nigeria but met mainly at St Savior's Anglican Church.
        The Anglican Church was opposed to the practices of the group, and members of the group who were workers in the Anglican Church were forced to resign.
        When the Great Revival emerged in July 1930, people rejected their traditional medicines, and thousands of people gave their lives to Jesus.
        On 23 September 1931, Pastors D.P Williams, A. Turnbull, and W.J Williams came to Nigeria and ordained the first seven Pastors of the church.
    </p>
    <p>
        Christ Apostolic Church (CAC) is the first Pentecostal church present in Nigeria. It arose in the first half of the 20th century, in the then-British empire.
        It was founded in Ijebu-ode, named Precious Stone Society in 1918, but was formally established in 1941 after a split from the Apostolic Church,
        which the original Aladura organization (Faith Tabernacle) had invited to Nigeria.
    </p>
    <p>
        Christ Apostolic Church operates secondary schools and an Entrepreneurial University named after the first General Evangelist, Joseph Ayo Babalola University (JABU), located in Ikeji Arakeji, Osun State, Nigeria.
        Pastor Samuel Olusegun Oladele was inaugurated as the 8th president of Christ Apostolic Church Worldwide on 20 March 2021.
    </p>

    <!-- About Us Section -->
    <div class="content">
        <h2>About Us</h2>
        <p>
            The Christ Apostolic Church as known today started in 1917 as the Unity Prayer Group and was later called the Faith Tabernacle Church because of the initial affiliation of Anim's prayer group to the Faith Tabernacle ministry, Philadelphia.
        </p>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 The Apostolic Church Of Ghana. All Rights Reserved.</p>
        <div class="social-icons">
            <a href="#" target="_blank"><i class="fab fa-facebook"></i></a>
            <a href="#" target="_blank"><i class="fab fa-twitter"></i></a>
            <a href="#" target="_blank"><i class="fab fa-instagram"></i></a>
            <a href="#" target="_blank"><i class="fab fa-youtube"></i></a>
        </div>
    </footer>

</body>
</html>
