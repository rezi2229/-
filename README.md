
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>10 გვერდი</title>
    <style>
        /* სტილები აქ */
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }
        .container {
            width: 100%;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
        }
        img {
            max-width: 100%;
            max-height: 100%;
        }
        .button {
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #007bff;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>

<div class="container">
    <img src="Slide1.PNG" alt="Image">
    <button class="button" onclick="window.location.href='page2.html'">გადასვლა შემდეგზე</button>
</div>

</body>
</html>
