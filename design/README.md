A few of the code snippets


    <html>
    <body>

    <p>Tell me your name</p>

    <form onreset="popFunction()">
    <input type="text" id="userInput" oninput="newFunction()">
    <input type="reset">

    <p id="userName"></p>

    <script>
    function newFunction() {
    var x = document.getElementById("userInput").value;
    document.getElementById("userName").innerHTML = "How cool is that " + x + "? Now press the rest button";
    }
    function popFunction() {
    alert("Thanks for playing! Now try a code of your own.");
    }
    </script>

    </body>
    </html>


