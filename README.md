<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>APB RAM Design and Verification</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 40px;
      background-color: #f9f9f9;
      color: #333;
    }
    h1 {
      color: #2c3e50;
    }
    h2 {
      color: #2980b9;
      border-bottom: 2px solid #2980b9;
      padding-bottom: 5px;
    }
    ul {
      line-height: 1.6;
    }
    a {
      color: #e74c3c;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    .highlight {
      background-color: #ecf0f1;
      padding: 10px;
      border-left: 4px solid #3498db;
      font-family: monospace;
    }
  </style>
</head>
<body>

  <h1>📦 APB RAM Design and Verification</h1>

  <h2>Overview</h2>
  <p>
    This project focuses on the design and functional verification of an <strong>APB-interfaced RAM module</strong>, developed using <strong>SystemVerilog</strong> and simulated on <strong>EDA Playground</strong> with <strong>Aldec Riviera 2023.04</strong>. The design adheres to the <em>AMBA APB protocol</em> and implements both <strong>read</strong> and <strong>write</strong> operations through standard APB signals.
  </p>

  <h2>🔑 Key Features</h2>
  <ul>
    <li>📦 APB-compliant RAM with parameterizable address and data width</li>
    <li>🔁 Supports standard read/write operations</li>
    <li>🧪 Self-checking <strong>SystemVerilog Testbench</strong></li>
    <li>🛠️ Developed and simulated on <strong>EDA Playground</strong></li>
    <li>🔍 <strong>Protocol assertions</strong> to ensure APB compliance</li>
    <li>📈 Waveform viewing with <strong>GTKWave</strong> (via EDA Playground)</li>
  </ul>

  <h2>🛠️ Simulator Used</h2>
  <p class="highlight">Aldec Riviera-PRO 2023.04</p>

  <h2>🔗 Project Link</h2>
  <p>
    View and run the simulation on EDA Playground:
    <a href="https://www.edaplayground.com/x/VFWv" target="_blank">
      https://www.edaplayground.com/x/VFWv
    </a>
  </p>

</body>
</html>
