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
      background: #ffffff;
      color: #111111;
      font-family: Menlo, Monaco, Consolas, "Courier New", monospace;
      display: flex;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      padding: 16px;
      box-sizing: border-box;
    }

    .terminal {
      width: 100%;
      max-width: 800px;
      font-size: 16px;
      line-height: 1.6;
    }

    @media (max-width: 480px) {
      .terminal {
        font-size: 14px;
      }
    }

    .line {
      white-space: nowrap;
      overflow: hidden;
      border-right: 2px solid #111111;
      animation: blink 1s step-end infinite;
    }

    .typing {
      display: inline-block;
      overflow: hidden;
      border-right: 2px solid #111111;
      white-space: nowrap;
      max-width: 100%;
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
      color: #666666;
    }
  </style>
</head>
<body>
  <div class="terminal">
    <div class="typing">>We build Energy-efficient Event-driven Edge AI systems.</div>
  </div>
</body>
</html>

