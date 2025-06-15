<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Simple Webpage</title>
    <!-- Styling with CSS -->
    <style>
        body {
            background-image: "";
            background-color: #f0f8ff;
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 20px;
        }
        h1 {
            color: #2c3e50;
            text-align: center;
        }
        p {
            font-size: 18px;
            color: #34495e;
            line-height: 1.6;
        }
        img {
            display: block;
            margin: 20px auto;
            width: 300px;
            border-radius: 15px;
            box-shadow: 0 0 10px rgba(0,0,0,0.3);
        }
        a {
            color: #3498db;
            text-decoration: none;
            font-weight: bold;
        }
        a:hover {
            text-decoration: underline;
        }
        button {
            display: block;
            margin: 30px auto;
            padding: 10px 20px;
            font-size: 16px;
            background-color: #e67e22;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #d35400;
        }
    </style>
</head>
<body>

    <h1>Welcome to My Simple Webpage</h1>
    <p>This is a simple webpage created using <strong>HTML</strong>, <strong>CSS</strong>, and <strong>JavaScript</strong>. You can learn basic web development by experimenting with these technologies.</p>

    <p>Here is a beautiful picture:</p>
    <img src="./planet9_Wallpaper_5000x2813.jpg" alt="Sample Image">

    <p>Visit <a href="https://www.example.com" target="_blank">this link</a> to explore more.</p>

    <button onclick="showMessage()">Click Me!</button>

    <script>
        function showMessage() {
            alert("Hello! You clicked the button.");
        }
    </script>

</body>
</html>
