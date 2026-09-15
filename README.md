```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Dive In with Lala 🐠🤿</title>

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', 'Segoe UI', Arial, sans-serif;
      background: #ffffff;
      color: #111111;
      margin: 0;
      min-height: 100vh;

      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;

      padding: 40px 20px 100px;
    }

    h1 {
      font-size: 1.9rem;
      font-weight: 600;
      letter-spacing: -0.5px;
      text-align: center;
      margin: 0 0 32px;
    }

    .buttons {
      width: 100%;
      max-width: 250px;
    }

    .button {
      display: flex;
      align-items: center;
      justify-content: center;

      width: 100%;
      min-height: 50px;

      margin: 8px 0;
      padding: 14px 16px;

      border-radius: 12px;

      font-size: 16px;
      font-weight: 600;
      text-decoration: none;

      color: #ffffff;

      transition:
        transform 0.15s ease,
        opacity 0.2s ease;
    }

    .button:hover {
      transform: translateY(-2px);
      opacity: 0.9;
    }

    .button:active {
      transform: translateY(0);
    }

    /* KakaoTalk */
    .kakao {
      background-color: #FEE500;
      color: #3C1E1E;
    }

    /* LINE */
    .line {
      background-color: #00B900;
    }

    /* WhatsApp */
    .whatsapp {
      background-color: #25D366;
    }

    /* Instagram */
    .instagram {
      background: linear-gradient(
        45deg,
        #feda75,
        #fa7e1e,
        #d62976,
        #962fbf,
        #4f5bd5
      );
    }

    /* LALA DIVE Website */
    .website {
      background-color: #0077B6;
    }

    /* Email */
    .email {
      background-color: #333333;
    }

    footer {
      position: fixed;
      bottom: 25px;
      left: 0;
      width: 100%;

      text-align: center;

      font-size: 13px;
      color: #999999;
    }
  </style>
</head>

<body>

  <h1>Dive In with Lala 🐠🤿</h1>

  <div class="buttons">

    <!-- KakaoTalk -->
    <a
      class="button kakao"
      href="https://open.kakao.com/me/diverlala"
      target="_blank"
      rel="noopener noreferrer"
    >
      💬 KakaoTalk
    </a>

    <!-- LINE -->
    <a
      class="button line"
      href="https://line.me/ti/p/T9-h9V2uUB"
      target="_blank"
      rel="noopener noreferrer"
    >
      💚 LINE
    </a>

    <!-- WhatsApp -->
    <a
      class="button whatsapp"
      href="https://wa.link/t2xwgj"
      target="_blank"
      rel="noopener noreferrer"
    >
      📱 WhatsApp
    </a>

    <!-- Instagram -->
    <a
      class="button instagram"
      href="https://www.instagram.com/laladive_phuket"
      target="_blank"
      rel="noopener noreferrer"
    >
      📸 Instagram
    </a>

    <!-- LALA DIVE Website -->
    <a
      class="button website"
      href="https://laladivephuket.com"
      target="_blank"
      rel="noopener noreferrer"
    >
      🌐 LALA DIVE Website
    </a>

    <!-- Email -->
    <a
      class="button email"
      href="mailto:yeonyang08@gmail.com"
    >
      ✉️ Send an Email
    </a>

  </div>

  <footer>
    © 2025 LALA KIM 🐬
  </footer>

</body>
</html>
```
