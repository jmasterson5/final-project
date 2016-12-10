# CodeMirror

[CodeMirror](https://github.com/codemirror/codemirror) found on github, is a very cool way to display useful coding into an HTML page. It is widely used for demonstrating, teaching, and learning to code. I Plan to make use of this with a live coding portion of my website.

## A few of the code snippets


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


