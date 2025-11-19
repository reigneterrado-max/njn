<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f0f0f0;
            padding: 50px;
        }
        h1 {
            color: #2c3e50;
        }
        p {
            color: #34495e;
        }
        button {
            padding: 10px 20px;
            background-color: #3498db;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #2980b9;
        }
    </style>
</head>
<body>
    <h1>Welcome to My Website!</h1>
    <p>This is a simple webpage created with HTML, CSS, and a little bit of JS.</p>
    <button onclick="showMessage()">Click Me!</button>

    <script>
        function showMessage() {
            alert("Hello! This is your first website in action!");
        }
    </script>
</body>
</html>
