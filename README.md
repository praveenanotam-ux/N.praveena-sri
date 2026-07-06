<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p>counter:</p>
    <div id="counter">0</div>
     <button onclick="increment()">Increment</button>
     <button onclick="decrement()">Decrement</button>
     <button onclick="reset()">Reset</button>
    <script>
        let count = 0;
        function increment(){
            count++;
            document.getElementById("counter").innerText = count;
        }
        function decrement(){
            count--;
            document.getElementById("counter").innerText = count;
        }
        function reset(){
            count = 0;
            document.getElementById("counter").innerText = count;
        }
    </script>
</body>
</html>
