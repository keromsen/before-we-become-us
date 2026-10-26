
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>BEFORE WE BECAME US</title>

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 24px;
      background: #eeeae2;
      color: #37372f;
      font-family: Georgia, serif;
    }

    .intro {
      width: 100%;
      max-width: 380px;
      min-height: 540px;
      padding: 48px 28px;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      border: 1px solid #d5d0c5;
      background: #f8f6f0;
      box-shadow: 0 18px 50px #5c56451a;
    }

    .eyebrow {
      font-family: Arial, sans-serif;
      font-size: 10px;
      letter-spacing: 4px;
      text-transform: uppercase;
      color: #858575;
    }

    h1 {
      margin: 35px 0 18px;
      font-size: clamp(29px, 8vw, 39px);
      line-height: 1.2;
      font-weight: normal;
      letter-spacing: -1px;
    }

    .subtitle {
      font-size: 14px;
      line-height: 1.9;
      color: #77766c;
    }

    .divider {
      width: 38px;
      height: 1px;
      margin: 30px 0;
      background: #b8b5a5;
    }

    .open-button {
      margin-top: 14px;
      padding: 14px 28px;
      border: 1px solid #777b68;
      background: #777b68;
      color: white;
      font-family: Arial, sans-serif;
      font-size: 11px;
      letter-spacing: 2px;
      cursor: pointer;
      transition: background 0.2s;
    }

    .open-button:hover {
      background: #5f6453;
    }

    .footer {
      margin-top: 42px;
      font-family: Arial, sans-serif;
      font-size: 9px;
      letter-spacing: 2px;
      color: #a19d90;
    }
  </style>
</head>

<body>
  <main class="intro">
    <p class="eyebrow">a story about two people</p>

    <h1>BEFORE<br>WE BECAME US</h1>

    <p class="subtitle">
      somewhere between a message<br>
      and a memory, we became something.
    </p>

    <div class="divider"></div>

    <button class="open-button" onclick="openPhone()">
      OPEN PHONE
    </button>

    <p class="footer">A STORY TOLD THROUGH HIS PHONE</p>
  </main>

  <script>
    function openPhone() {
      alert("Gaska's phone is coming soon.");
    }
  </script>
</body>
</html>
