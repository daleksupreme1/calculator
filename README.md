<html>
    <label for="numberA">enter first number: </label> <input type="text" id="numberA" name="numberA">
    <br>
    <br>
    <label for="numberB">enter second number: </label> <input type="text" id="numberB" name="numberB">
     <br>
    <br>
<button type="button" onclick="multiplyXY()">multiply</button>
    <br>
    <button type="button" onclick="subtractXY()">subtract</button>
    <br>
     <button type="button" onclick="divideXY()">divide</button>
    <br>
    <button type="button" onclick="addXY()">add</button>
    <br>
    <br>
    <p id="demo">the result will appear here</p>
    <script>
        function multiplyXY() {
         var a = document.getElementById("numberA").value;
        var b = document.getElementById("numberB").value;
        var answer = a*b;
            document.getElementById("demo").innerHTML = "the answer is " + answer;
        }
        </script>
     <script>
        function subtractXY() {
         var a = document.getElementById("numberA").value;
        var b = document.getElementById("numberB").value;
        var answer = a-b;
            document.getElementById("demo").innerHTML = "the answer is " + answer;
        }
        </script>
      <script>
        function divideXY() {
         var a = document.getElementById("numberA").value;
        var b = document.getElementById("numberB").value;
        var answer = a/b;
            document.getElementById("demo").innerHTML = "the answer is " + answer;
        }
        </script>
     <script>
        function addXY() {
         var a = parseInt( document.getElementById("numberA").value);
        var b = parseInt( document.getElementById("numberB").value);
        var answer = a + b;
            document.getElementById("demo").innerHTML = "the answer is " + answer;
        }
        </script>
</html>
