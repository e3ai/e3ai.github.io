<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>E3-AI</title>
  <link rel="icon" type="image/png" href="/assets/e3ai_logo.png" />
  <link rel="apple-touch-icon" href="/assets/e3ai_logo.png" />
  <style>
    body {
      margin: 0;
      background: #000;
      color: #00ff9c;
      font-family: Menlo, Monaco, Consolas, "Courier New", monospace;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
    }

    .terminal {
      width: 90%;
      max-width: 800px;
    }

    .line {
      white-space: nowrap;
      overflow: hidden;
      border-right: 2px solid #00ff9c;
      animation: blink 1s step-end infinite;
    }

    .typing {
      display: inline-block;
      overflow: hidden;
      border-right: 2px solid #00ff9c;
      white-space: nowrap;
      animation: typing 3s steps(40, end), blink 1s step-end infinite;
    }

    @keyframes typing {
      from { width: 0 }
      to { width: 100% }
    }

    @keyframes blink {
      50% { border-color: transparent }
    }

    .dim {
      color: #008f5a;
    }
  </style>
</head>
<body>
  <div class="terminal">
    <div class="dim">>e3.ai</div>
    <br />
    <div class="typing">>We build Energy-efficient Event-driven Edge AI systems.</div>
  </div>
</body>
</html>

