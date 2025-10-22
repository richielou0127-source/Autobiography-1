<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Autobiography</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(to right, #e0f7fa, #fff);
            color: #333;
        }

        header {
            background-color: #2c3e50;
            color: white;
            padding: 40px 20px 20px;
            text-align: center;
        }

        header h1 {
            margin-bottom: 10px;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin-top: 10px;
        }

        nav ul li {
            display: inline-block;
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #1abc9c;
        }

        .section {
            margin: 30px auto;
            max-width: 800px;
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }

        .section h2 {
            border-bottom: 2px solid #ccc;
            padding-bottom: 10px;
        }

        .profile-pic {
            width: 150px;
            border-radius: 70%;
            display: block;
            margin: 10px auto;
            border: 4px solid #2c3e50;
        }

        footer {
            text-align: center;
            background-color: #2c3e50;
            color: white;
            padding: 15px 0;
            position: relative;
            bottom: 0;
            width: 100%;    
            margin-top: 40px;
        }

        .achievements li {
            margin-bottom: 8px;
        }

        .social-icons a {
            margin: 0 10px;
            color: #0c0c0c;
            text-decoration: none;
        }

        .social-icons a:hover {
            color: #f8e800f8;
        }
        body {
            background-image: url('https://www.google.com/url?sa=i&url=https%3A%2F%2Fllcc.edu.ph%2Fthe-seal-of-lapu-lapu-city-college%2F&psig=AOvVaw0jn02iaSgtnFGPTjqdaCl7&ust=1761122249723000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCKCUjtTxtJADFQAAAAAdAAAAABAE.jpg');
            background-repeat: no-repeat;
            background-size: cover;
        }
    </style>
</head>
<body>

    <header>
        <h1>Autobiography</h1>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#journey">My Journey</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <div class="section" id="about">
        <h2><i class="fas fa-user"></i> About Me</h2>
        <p>Richelou Padillo from section BIT 1-D, 18 years old.</p>
        <p>My hobbies include playing volleyball, listening to music, and playing online games.</p>
        <p>Currently studying in Lapu-Lapu City College.</p>
    </div>

    <div class="section" id="journey">
        <h2><i class="fas fa-trophy"></i> My Achievements</h2>
        <ul class="achievements">
            <li>🏅 With Honor 2024–2025</li>
            <li>🏐 CVIRAA Lapu-Lapu City Representative</li>
            <li>🥇 Champion Men's Volleyball Interbarangay, Mactan 2024</li>
            <li>🏆 Private School Developmental Volleyball Men's Champion - 3 Peat</li>
        </ul>
    </div>

    <div class="section" id="contact">
        <h2><i class="fas fa-envelope"></i> Contact</h2>
        <p>Feel free to connect with me!</p>
        <div class="social-icons">
            <a href="https://www.facebook.com/richielouuu" target="_blank"><i class="fab fa-facebook fa-2x"></i></a>
            <a href="#"><i class="fab fa-instagram fa-2x"></i></a>
            <a href="#"><i class="fab fa-twitter fa-2x"></i></a>
        </div>
    </div>

    <footer>
        <p>© 2025 Richelou Padillo. All rights reserved.</p>
    </footer>

</body>
</html>
