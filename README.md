
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>瀛翰3C</title>
  <style>
    :root {
      --primary-color: #174873;
      --accent-color: #3BAFDA;
      --background-color: #F4F8FB;
      --text-color: #2C3E50;
      --section-padding: 60px 20px;
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: var(--background-color);
      color: var(--text-color);
      scroll-behavior: smooth;
    }

    header {
      background-color: var(--primary-color);
      color: white;
      padding: 20px;
      text-align: center;
      opacity: 0;
      transform: translateY(-20px);
      animation: fadeInUp 1s forwards;
    }

    header h1 {
      margin: 0;
      font-size: 2em;
    }

    section {
      padding: var(--section-padding);
      opacity: 0;
      transform: translateY(20px);
      animation: fadeInUp 1s forwards;
    }

    section:nth-of-type(2) { animation-delay: 0.2s; }
    section:nth-of-type(3) { animation-delay: 0.4s; }
    section:nth-of-type(4) { animation-delay: 0.6s; }

    h2 {
      color: var(--primary-color);
      margin-bottom: 20px;
    }

    ul {
      list-style: none;
      padding-left: 0;
    }

    ul li::before {
      content: "\2713\0020";
      color: var(--accent-color);
    }

    .section-alt {
      background-color: white;
    }

    .image-banner {
      width: 100%;
      max-height: 300px;
      object-fit: cover;
      display: block;
    }

    footer {
      background-color: var(--primary-color);
      color: white;
      text-align: center;
      padding: 20px;
      opacity: 0;
      transform: translateY(20px);
      animation: fadeInUp 1s forwards;
      animation-delay: 0.8s;
    }

    .contact-info p {
      margin: 5px 0;
    }

    @media (min-width: 768px) {
      .columns {
        display: flex;
        gap: 40px;
      }
      .columns > div {
        flex: 1;
      }
    }

    @keyframes fadeInUp {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>瀛翰3C</h1>
    <p>資訊設備通路與數位應用顧問</p>
  </header>


  <section>
    <h2>產品項目</h2>
    <ul>
      <li>電腦 / 筆記型電腦 / 螢幕</li>
      <li>事務機 / 儲存裝置 / 周邊配件</li>
      <li>網路通訊設備 / UPS電池</li>
      <li>智慧家庭 / 商用電子設備</li>
    </ul>
  </section>

  <section class="section-alt">
    <h2>服務對象與解決方案</h2>
    <div class="columns">
      <div>
        <h3>內部資訊系統導入</h3>
        <ul>
          <li>POS銷售系統</li>
          <li>CRM顧客關係管理</li>
          <li>簡易ERP系統</li>
          <li>雲端辦公工具整合</li>
        </ul>
      </div>
      <div>
        <h3>電商與社群整合</h3>
        <ul>
          <li>LINE官方帳號建置與Chatbot應用</li>
          <li>自建購物網站規劃與導入</li>
          <li>社群平台整合行銷策略</li>
        </ul>
      </div>
      <div>
        <h3>網路架構與資安顧問</h3>
        <ul>
          <li>企業內部網路建置</li>
          <li>資安防護建議</li>
          <li>防毒部署與維運支援</li>
        </ul>
      </div>
    </div>
  </section>

  <section>
    <h2>聯絡我們</h2>
    <div class="contact-info">
      <p>📧 service@yinghan3c.com</p>
      <p>📱 0988-XXX-XXX</p>
      <p>📍 台中市XX區XX路XX號</p>
    </div>
  </section>

  <footer>
    <p>© 2025 瀛翰3C. 瀛翰企業有限公司。統編：60692848</p>
  </footer>


</body>
</html>
