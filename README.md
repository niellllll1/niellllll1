<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculator</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1> Calculator</h1>
    <form action="" name="clc">
        <input type="text" name="display" style="width: 370px; height: 70px; background-color: wh;color: black;"><br>
        <input class="btn" type="button" value="0" onclick="clc.display.value += '0'" style="background-color: white;">
        <input class="btn" type="button" value="1" onclick="clc.display.value += '1'" style="background-color: white;">
        <input class="btn" type="button" value="2" onclick="clc.display.value += '2'" style="background-color: white;">
        <input class="btn" type="button" value="+" onclick="clc.display.value += '+'" style=" background-color: white;"><br>
        <input class="btn" type="button" value="3" onclick="clc.display.value += '3'" style="background-color: white;">
        <input class="btn" type="button" value="4" onclick="clc.display.value += '4'" style="background-color: white;">
        <input class="btn" type="button" value="5" onclick="clc.display.value += '5'" style="background-color: white;">
        <input class="btn" type="button" value="-" onclick="clc.display.value += '-'" style="background-color: white;"><br>
        <input class="btn" type="button" value="6" onclick="clc.display.value += '6'" style="background-color: white;">
        <input class="btn" type="button" value="7" onclick="clc.display.value += '7'" style="background-color: white;">
        <input class="btn" type="button" value="8" onclick="clc.display.value += '8'" style="background-color: white;">
        <input class="btn" type="button" value="×" onclick="clc.display.value += '×'" style="background-color: white;"><br>
        <input class="btn" type="button" value="9" onclick="clc.display.value += '9'" style="background-color: white;">
        <input class="btn" type="button" value="C" onclick="clc.display.value =''" style="background-color: white;">
        <input class="btn" type="button" value="=" onclick="clc.display.value ='I MISS YOU'" style="background-color: white;">
        <input class="btn" type="button" value="&#247;" onclick="clc.display.value += '/'" style="background-color: white;">

    </form>
</body>
</html>
