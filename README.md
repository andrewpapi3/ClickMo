<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Prank Your Friends</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
        }
        #message {
            font-size: 24px;
            margin: 50px;
        }
        #yes-button {
            background-color: green;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 18px;
            cursor: pointer;
        }
        #no-button {
            background-color: red;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 18px;
            cursor: not-allowed;
        }
    </style>
</head>
<body>
    <div id="message">
        Do you like me?
    </div>
    <button id="yes-button" onclick="prank()">Yes</button>
    <button id="no-button" disabled>No</button>

    <script>
        function prank() {
            document.getElementById("message").innerHTML = "Ikaw ha, charot! Good luck sa exam, baby! Mwamwaaa! 😘";
            document.getElementById("yes-button").style.display = "none";
            document.getElementById("no-button").style.display = "none";
        }
    </script>
</body>
</html>

