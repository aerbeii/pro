<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Semua Momen - Galeri Cinta Kami</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #fff0f5;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #e75480;
      color: white;
      padding: 1em 0;
      text-align: center;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 30px;
    }

    .gallery img {
      width: 100%;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: transform 0.2s;
    }

    .gallery img:hover {
      transform: scale(1.03);
    }

    .back-btn {
      text-align: center;
      margin: 20px;
    }

    .back-btn a {
      background-color: #e75480;
      color: white;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
    }

    .back-btn a:hover {
      background-color: #c70039;
    }

    footer {
      background-color: #e75480;
      color: white;
      text-align: center;
      padding: 10px;
      margin-top: 30px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Semua Momen</h1>
    <p>Galeri lengkap cinta kita dari waktu ke waktu</p>
  </header>

  <div class="gallery">
    <!-- Momen 1 -->
    <img src="foto/IMG-20250601-WA0054.jpg" alt="Momen 1 - 1">
    <img src="foto/IMG-20250601-WA0053.jpg" alt="Momen 1 - 2">
    <img src="foto/IMG-20250601-WA0058.jpg" alt="Momen 1 - 3">

    <!-- Momen 2 -->
    <img src="foto/IMG-20250430-WA0101.jpg" alt="Momen 2 - 1">
    <img src="foto/IMG-20250430-WA0112.jpg" alt="Momen 2 - 2">
    <img src="foto/IMG-20250430-WA0092.jpg" alt="Momen 2 - 3">

    <!-- Momen 3 -->
    <img src="foto/IMG-20250430-WA0096.jpg" alt="Momen 3 - 1">
    <img src="foto/IMG-20250430-WA0083.jpg" alt="Momen 3 - 2">
    <img src="foto/IMG-20250430-WA0111.jpg" alt="Momen 3 - 3">
  </div>

  <div class="back-btn">
    <a href="index.html">← Kembali ke Beranda</a>
  </div>

  <footer>
    &copy; 2025 Galeri Cinta Kami. Dibuat dengan ❤️ untuk mengenang setiap detik bersama.
  </footer>

</body>
</html>
