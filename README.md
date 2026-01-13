html````




!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ritesh Kumar Yadav | First Webpage</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background: #1d1f21;
            margin: 0;
            padding: 0;
            color: white;
        }

        header {
            text-align: center;
            background: #4fa3d1;
            color: white;
            padding: 25px;
            font-size: 28px;
            font-weight: bold;
        }

        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }

        h2 {
            color: #7ec8ff;
            font-size: 26px;
        }

        p {
            font-size: 17px;
            line-height: 1.6;
        }

        .logo {
            width: 150px;
            height: 150px;
            margin: 20px auto;
            display: block;
            border-radius: 50%;
            border: 4px solid #7ec8ff;
            padding: 8px;
            background: #ffffff10;
            box-shadow: 0 0 18px rgba(126, 200, 255, 0.5);
            transition: 0.3s ease;
        }

        .logo:hover {
            transform: scale(1.08);
            box-shadow: 0 0 28px rgba(126, 200, 255, 0.9);
        }

        a {
            color: #7ec8ff;
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            text-decoration: underline;
        }

        .btn {
            padding: 12px 25px;
            background: #4fa3d1;
            color: white;
            border: none;
            border-radius: 8px;
            font-size: 17px;
            cursor: pointer;
            margin-top: 15px;
        }

        .btn:hover {
            background: #3a8bb7;
        }

        .card {
            background: #2a2d2f;
            padding: 25px;
            margin: 25px 0;
            border-radius: 12px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.3);
        }
    </style>
</head>

<body>

    <header>
        Welcome to My First Webpage
    </header>

    <div class="container">

        <div class="card">
            <h2>About Me</h2>
            <p>
                Hi! I'm <strong>Ritesh Kumar Yadav </strong>, an aspiring web developer currently learning 
                HTML, CSS, and JavaScript.  
                I am also working as an <strong>Intern at Apex Planet</strong>, where I am gaining real-world experience and improving my development skills.<br><br>

                <strong>This is my first task in my internship at Apex Planet.</strong>
            </p>

            <img class="logo" src="https://cdn-icons-png.flaticon.com/512/5968/5968267.png" alt="Logo">
        </div>

        <div class="card">
            <h2>Connect with Me</h2>
            <p>
                You can view my work and projects on 
                <a href="https://www.linkedin.com" target="_blank">LinkedIn</a>  
                or explore my code on  
                <a href="https://github.com" target="_blank">GitHub</a>.
            </p>

            <button class="btn" onclick="showMessage()">Press here!</button>
        </div>

    </div>

    <script>
        function showMessage() {
            alert("Hello! Welcome to Ritesh's webpage 🎉");
        }
    </script>

</body>
</html>
