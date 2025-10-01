<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Thu Mua Sắt Vụn Tuệ Tĩnh</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #fff9d9;
      text-align: center;
      overflow-x: hidden;
    }
    header {
      padding: 20px;
      background: #ffcc00;
      color: #333;
      font-size: 26px;
      font-weight: bold;
    }
    section {
      padding: 20px;
    }
    /* Nút nổi liên hệ */
    .floating-buttons {
      position: fixed;
      bottom: 20px;
      right: 20px;
      display: flex;
      flex-direction: column;
      gap: 12px;
      z-index: 999;
    }
    .btn-circle {
      width: 55px;
      height: 55px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 24px;
      cursor: pointer;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
      position: relative;
      overflow: hidden;
    }
    .btn-circle::after {
      content: "";
      position: absolute;
      width: 120%;
      height: 120%;
      background: rgba(255,255,255,0.4);
      border-radius: 50%;
      transform: scale(0);
      transition: transform 0.4s ease-out;
      z-index: 1;
    }
    .btn-circle:active::after {
      transform: scale(1.5);
    }
    .call { background: #28a745; }
    .zalo { background: #0068ff; }
    .messenger { background: #0084ff; }

    /* Bong bóng chat nổi */
    .chat-bubbles {
      position: fixed;
      bottom: 100px;
      left: 20px;
      display: flex;
      flex-direction: column;
      gap: 12px;
      z-index: 999;
    }
    .chat-bubble {
      width: 55px;
      height: 55px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 26px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
      cursor: pointer;
      animation: bounce 1.5s infinite alternate, blink 2s infinite;
    }
    .chat-zalo { background: #0068ff; }
    .chat-mess { background: #0084ff; }

    @keyframes bounce {
      0% { transform: translateY(0); }
      100% { transform: translateY(-6px); }
    }
    @keyframes blink {
      0%,100% { opacity: 1; }
      50% { opacity: 0.7; }
    }

    /* Google Maps */
    .map {
      margin: 20px auto;
      max-width: 900px;
    }
    iframe {
      width: 100%;
      height: 350px;
      border: 0;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    }
  </style>
  <!-- Icon FontAwesome -->
  <script src="https://kit.fontawesome.com/yourkitid.js" crossorigin="anonymous"></script>
</head>
<body>
  <header>Thu Mua Sắt Vụn Tuệ Tĩnh</header>
  <section>
    <h2>Uy tín - Nhanh chóng - Giá cao</h2>
    <p>Chuyên thu mua sắt vụn, đồng, nhôm, inox, chì, hợp kim... tại TP.HCM và các khu vực lân cận.</p>
  </section>

  <!-- Google Maps -->
  <div class="map">
    <iframe 
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3919.027636259324!2d106.60733737480453!3d10.809045989345744!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x31752b31b39d72a9%3A0x3f0cdb1d38d63e87!2zMTQgxJDGsOG7nW5nIHPhu5EgNCwgS2h1IFBoxrDhu51uZyAzLCBCw6xuaCBIxrBuZyBIw7JhIEEsIELDrG5oIFThu6sgxJDhu5NuZywgSOG7kyBDaMOtbmg!5e0!3m2!1svi!2s!4v1696500000000" 
      allowfullscreen 
      loading="lazy">
    </iframe>
  </div>

  <!-- Nút nổi liên hệ -->
  <div class="floating-buttons">
    <a href="tel:0377280664" class="btn-circle call"><i class="fas fa-phone"></i></a>
    <a href="https://zalo.me/0377280664" class="btn-circle zalo"><i class="fas fa-comment"></i></a>
    <a href="https://m.me/yourfacebookid" class="btn-circle messenger"><i class="fab fa-facebook-messenger"></i></a>
  </div>

  <!-- Bong bóng chat nổi -->
  <div class="chat-bubbles">
    <a href="https://zalo.me/0377280664" class="chat-bubble chat-zalo"><i class="fas fa-comment"></i></a>
    <a href="https://m.me/yourfacebookid" class="chat-bubble chat-mess"><i class="fab fa-facebook-messenger"></i></a>
  </div>
</body>
</html>
[SSDS.txt](https://github.com/user-attachments/files/22628276/SSDS.txt)
