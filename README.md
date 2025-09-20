<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h2> String Match </h2>
    <p id="out"></p>
    <script>
        let text="cat,bat,rat,mat";
        let result=text.match(/at/g);
        document.getElementById("out").innerText=result;
    </script>
</body>
</html>
