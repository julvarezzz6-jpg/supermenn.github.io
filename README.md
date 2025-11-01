<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>INDAHNYA KEHIDUPAN</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
        }
        #interactiveButton {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
            text-decoration: none; /* Menghilangkan garis bawah jika digunakan sebagai link */
        }
        #interactiveButton:hover {
            background-color: #45a049;
        }
        #interactiveButton:active {
            background-color: #3e8e41;
        }
    </style>
</head>
<body>
    <h1>INDAHNYA KEHIDUPAN</h1>
    <button id="interactiveButton">Klik Saya!</button>

    <script>
        const button = document.getElementById('interactiveButton');

        button.addEventListener('click', function() {
            // Ganti URL di bawah ini dengan link yang diinginkan
            window.location.href = 'https://www.google.com'; // Contoh: membuka Google
        });
    </script>
</body>
</html>
