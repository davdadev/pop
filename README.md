<html>
<head>
    <style>
        @keyframes marquee {
            0%   { text-indent: 100%; }
            100% { text-indent: -100%; }
        }
        .animated-url {
            overflow: hidden;
            white-space: nowrap;
            animation: marquee 5s linear infinite;
        }
    </style>
    <script>
        function loop() {
            var i, n, s = '';

            for (i = 0; i < 10; i++) {
                n = Math.floor(Math.sin((Date.now()/200) + (i/2)) * 4) + 4;

                s += String.fromCharCode(0x2581 + n);
            }

            window.location.hash = s;

            setTimeout(loop, 50);
        }

        loop();
    </script>
</head>
<body>
    <h1>Welcome!</h1>
    <p>Check out this cool animated URL:</p>
    <p class="animated-url">🌍🚀🌟hiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiii🌟🚀🌍</p>
</body><head>
    <style>
        .animated-url {
            animation: marquee 5s linear infinite;
        }
    </style>
    <script>
        function loop() {
            var i, n, s = '';

            for (i = 0; i < 10; i++) {
                n = Math.floor(Math.sin((Date.now()/200) + (i/2)) * 4) + 4;

                s += String.fromCharCode(0x2581 + n);
            }

            window.location.hash = s;

            setTimeout(loop, 50);
        }
input("hi")
        loop();
    </script>
</head>
<body>
    <form action="http://localhost:3000/inputs" method="POST">
        <input type="text" id="myInput" name="myInput">
        <button type="submit">Submit</button>
    </form>
</body>
