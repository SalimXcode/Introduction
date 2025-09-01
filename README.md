#introduction
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SalimXCode | Jarvis AI Profile</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Share+Tech+Mono&display=swap');

    body {
      margin: 0;
      padding: 0;
      font-family: 'Share Tech Mono', monospace;
      background: radial-gradient(circle at top, #0f2027, #203a43, #2c5364);
      color: #00ffe7;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
    }

    .jarvis-container {
      text-align: center;
      border: 2px solid #00ffe7;
      border-radius: 15px;
      padding: 30px 50px;
      background: rgba(0, 0, 0, 0.6);
      box-shadow: 0 0 20px #00ffe7, inset 0 0 20px #00ffe7;
      animation: pulse 2s infinite;
    }

    .jarvis-title {
      font-size: 2rem;
      text-transform: uppercase;
      letter-spacing: 3px;
      text-shadow: 0 0 15px #00ffe7;
      margin-bottom: 20px;
    }

    .scan-line {
      width: 100%;
      height: 2px;
      background: linear-gradient(90deg, transparent, #00ffe7, transparent);
      animation: scan 3s linear infinite;
      margin: 20px 0;
    }

    .skills {
      font-size: 1.2rem;
      margin-top: 15px;
      color: #fff;
    }

    .skills span {
      display: inline-block;
      margin: 8px;
      padding: 5px 15px;
      border: 1px solid #00ffe7;
      border-radius: 8px;
      box-shadow: 0 0 10px #00ffe7;
      animation: glow 2s infinite alternate;
    }

    @keyframes glow {
      from { box-shadow: 0 0 5px #00ffe7; }
      to { box-shadow: 0 0 20px #00ffe7; }
    }

    @keyframes pulse {
      0%, 100% { box-shadow: 0 0 20px #00ffe7, inset 0 0 20px #00ffe7; }
      50% { box-shadow: 0 0 40px #00ffe7, inset 0 0 40px #00ffe7; }
    }

    @keyframes scan {
      0% { transform: translateX(-100%); }
      100% { transform: translateX(100%); }
    }
  </style>
</head>
<body>
  <div class="jarvis-container">
    <div class="jarvis-title">[ Identity Confirmed ]<br>SalimXCode</div>
    <div class="scan-line"></div>
    <div class="skills">
      <span>⚡ Python</span>
      <span>🔥 HTML</span>
      <span>🎨 CSS</span>
    </div>
    <p style="margin-top:20px;">Mission: <strong>Building Future with Code</strong></p>
  </div>
</body>
</html>
