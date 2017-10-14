<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>test1</title>
    <script>
        function run1() {
            var myWidth = document.getElementById("container");
            myWidth.style.width = "200px";
            }

        function run2() {
            var myHeight =  document.getElementById("container");
            myHeight.style.height = "200px";
        }

        function run3() {
            var myColor = document.getElementById("container");
            myColor.style.background = "red";
        }

        function run4() {
            var myDisplay = document.getElementById("container");
            myDisplay.style.display = "none";
        }

        function run5() {
            var rePlace = document.getElementById("container");
            rePlace.style.display = "block";
            rePlace.style.background = "black";
            rePlace.style.height = "100px";
            rePlace.style.width = "100px";
        }
    </script>
</head>
<body>
<div id="outer" style="width: 500px; margin: 0 auto; padding: 0; text-align: center;">
    <input type="button" value="变高" onclick="run1()"/>
    <input type="button" value="变宽" onclick="run2()"/>
    <input type="button" value="变色" onclick="run3()"/>
    <input type="button" value="隐藏" onclick="run4()"/>
    <input type="button" value="重置" onclick="run5()"/>

    <div id="container" style="width: 100px; height: 100px; background: black; margin: 10px auto; display: block;">
    </div>
</div>
</body>
</html>
