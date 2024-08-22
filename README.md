<!DOCTYPE html>
<html>
<head>
    <title>Minimalist Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f0f0f0;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
        }

        main {
            padding: 20px;
        }

        button {
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }

        footer {
            background-color: #333;
            color: #fff;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Biplab Goswami</h1>
    </header>
    <main>
        <p>This is a simple, minimalist website created using HTML, CSS, and JavaScript.</p>
        <button id="changeColor">Change Color</button>
    </main>
    <footer>
        &copy; 2024 Minimalist Website
    </footer>
    <script>
        const changeColorButton = document.getElementById('changeColor');

        changeColorButton.addEventListener('click', () => {
            const randomColor = '#' + Math.floor(Math.random() * 16777215).toString(16);
            document.body.style.backgroundColor = randomColor;
        });
    </script>
</body>
</html>

