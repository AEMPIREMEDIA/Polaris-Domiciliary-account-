<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Polaris Bank Receipt</title>
  <style>
    body {
      font-family: 'Courier New', Courier, monospace;
      background-color: #f0f4f8;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .receipt-container {
      background-color: #13222d;
      color: #cce4ff;
      padding: 30px;
      border-radius: 20px;
      width: 350px;
      text-align: center;
    }
    .receipt-container h1 {
      font-size: 1.2rem;
      color: #4da6ff;
      margin-bottom: 20px;
    }
    .receipt-container p {
      font-size: 0.9rem;
      line-height: 1.5;
    }
    .italic {
      font-style: italic;
      margin-top: 10px;
    }
    .qr-code {
      margin: 20px 0;
    }
    .download-btn {
      background-color: #ffffff;
      border: none;
      padding: 15px;
      border-radius: 10px;
      width: 100%;
      font-size: 1rem;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <div class="receipt-container">
    <img src="logo_placeholder.png" alt="Polaris Bank Logo" height="40" />
    <h1>POLARIS BANK LIMITED</h1>
    <p>Amount: ₦10,726.22</p>
    <p>To: David Isaac (7010279796)</p>
    <p>Bank: Moniepoint MFB</p>
    <p>From: Etim, Aniefiok Bassey</p>
    <p>Date: 4/8/2025, 1:01:15 PM</p>
    <p>Description: Refund for Etim borrowed cash from you, thanks and sorry for the bank issues.</p>
    <p class="italic">Beneficiary will receive funds<br>within 24 banking hours.</p>
    <div class="qr-code">
      <img src="qr_placeholder.png" alt="QR Code" width="100" height="100" />
    </div>
    <button class="download-btn">Download Receipt</button>
  </div>
</body>
</html>
