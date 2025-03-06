<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Superpower of Coding with Snacks!</title>
    <style>
        body {
            font-family: 'Courier New', monospace;
            text-align: center;
            background-color: #121212;
            color: white;
            margin: 0;
            padding: 0;
        }

        h1 {
            font-size: 24px;
            color: #ffcc00;
            text-shadow: 0px 0px 10px #ffcc00;
            animation: glow 1.5s infinite alternate;
        }

        @keyframes glow {
            from { text-shadow: 0px 0px 5px #ffcc00; }
            to { text-shadow: 0px 0px 20px #ff6600; }
        }

        .coder {
            font-size: 18px;
            white-space: pre;
            line-height: 1.5;
            display: inline-block;
            text-align: left;
        }

        .snacks {
            font-size: 24px;
            margin-top: 10px;
        }

        .typing span {
            display: inline-block;
            width: 0;
            overflow: hidden;
            border-right: 2px solid white;
            white-space: nowrap;
            animation: typing 3s steps(20) infinite alternate, blink 0.7s infinite;
        }

        @keyframes typing {
            from { width: 0; }
            to { width: 100%; }
        }

        @keyframes blink {
            50% { border-color: transparent; }
        }
    </style>
</head>
<body>
    <h1>I HAVE THE SUPERPOWER OF CODING WITH SNACKS! 🍕☕🍿</h1>

    <div class="coder">
        <pre>
  (\_/)
  (O.o)  <span class="typing"><span> Coding... </span></span>
  (>💻)_/   
        </pre>
    </div>

    <div class="snacks">☕ 🍩 🍿</div>
</body>
</html>
