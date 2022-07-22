<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gay Button</title>
    <style>
        body {
            display: flex;
            align-items: center;
            vertical-align: middle;
            justify-content: center;
        }

        div#foda {
            background-color: darkorange;
            padding: 25px;
            border: 1px solid black;
            width: 300px;
            text-align: center;
            border-radius: 25px;
        }

        div:hover#foda {
            background-color: rgb(244, 134, 0);
        }

        p {
            font: bold 30px Arial;
            color: white;
        }

        video {
            display: none;
        }
    </style>
</head>
<body>
    <div onclick="gg()">
        <div id="foda">
            <p>Clique para se tornar gay</p>
        </div>
    </div>

    <video id="cu" src="rickrolludo.mp4" width="1080" style="display: none;"></video>
    <br>
    <script src="script.js"></script>
</body>
</html>
