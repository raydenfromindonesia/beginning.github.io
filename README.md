<!DOCTYPE html>
<html>
<head>
    <title>My Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background: #f5f5f5;
            padding: 50px;
        }

        .card {
            background: white;
            max-width: 500px;
            margin: auto;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }

        img {
            width: 150px;
            border-radius: 50%;
        }

        button {
            padding: 10px 20px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            background: #0078ff;
            color: white;
        }

        button:hover {
            background: #005fcc;
        }
    </style>
</head>
<body>
    <div class="card">
        <h1>Welcome to My Website</h1>
        <p>Made completely free!</p>

        <button onclick="sayHello()">Click Me</button>
    </div>

    <script>
        function sayHello() {
            alert("Hello! Thanks for visiting my website.");
        }
    </script>
</body>
</html>
