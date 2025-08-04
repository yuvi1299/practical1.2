<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Responsive Banking UI</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .card {
      background: white;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0px 4px 12px rgba(0, 0, 0, 0.15);
      text-align: center;
      width: 300px;
      max-width: 90%;
    }

    .balance {
      font-size: 28px;
      font-weight: bold;
      color: #2e7d32;
      margin-bottom: 25px;
    }

    button {
      display: block;
      width: 100%;
      padding: 15px;
      margin: 10px 0;
      border: none;
      border-radius: 8px;
      font-size: 18px;
      font-weight: bold;
      cursor: pointer;
      transition: transform 0.2s ease;
    }

    button:hover {
      transform: scale(1.05);
    }

    .deposit {
      background-color: #4caf50;
      color: white;
    }

    .withdraw {
      background-color: #f44336;
      color: white;
    }

    @media (max-width: 600px) {
      .card {
        width: 90%;
        padding: 20px;
      }
      .balance {
        font-size: 24px;
      }
      button {
        font-size: 16px;
        padding: 12px;
      }
    }
  </style>
</head>
<body>
  <div class="card">
    <div class="balance">$0</div>
    <button class="deposit">Deposit</button>
    <button class="withdraw">Withdraw</button>
  </div>
</body>
</html>
<img width="1416" height="1077" alt="Screenshot 2025-08-04 120042" src="https://github.com/user-attachments/assets/539cafb2-a7d9-4345-8266-bdf9642519f5" />
