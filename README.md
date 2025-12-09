<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Enteng Cheesedesal Promotion</title>
  <style>
    body {
      font-family: 'Segoe UI', Arial, sans-serif;
      margin: 0;
      background: linear-gradient(135deg, #f0f4ff, #ffffff);
      color: #333;
    }

    header {
      text-align: center;
      padding: 30px 20px;
      background: #b30f0f;
      color: #fff;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    header h1 {
      margin: 0;
      font-size: 40px;
      text-transform: uppercase;
      letter-spacing: 2px;
    }
    .stripe {
      margin: 15px auto 0;
      width: 80%;
      height: 12px;
      background-image: repeating-linear-gradient(
        -45deg,
        #fff,
        #fff 8px,
        #ffdd00 8px,
        #ffdd00 16px
      );
      border-radius: 6px;
    }

    .image-text {
      display: flex;
      gap: 20px;
      padding: 30px;
      max-width: 1000px;
      margin: auto;
    }
    .image-box {
      flex: 1;
      border: 2px dashed #aaa;
      text-align: center;
      padding: 60px 20px;
      background: #fafafa;
      border-radius: 12px;
      font-weight: bold;
      color: #777;
      transition: background 0.3s;
    }
    .image-box:hover {
      background: #eaf0ff;
    }
    .text-boxes {
      flex: 2;
      display: flex;
      flex-direction: column;
      gap: 12px;
      justify-content: center;
    }
    .text-boxes p {
      background: #fff;
      padding: 12px;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.05);
    }

    .block {
      background: #fff;
      margin: 30px auto;
      padding: 25px;
      border-radius: 12px;
      max-width: 1000px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.08);
    }
    .block h2 {
      margin-top: 0;
      text-transform: uppercase;
      color: #b30f0f;
      border-bottom: 2px solid #e5e7eb;
      padding-bottom: 8px;
    }
    .block p {
      margin: 10px 0;
      font-size: 16px;
    }

    .cta {
      display: inline-block;
      margin: 15px 0;
      padding: 12px 28px;
      background: #ffff03;
      color: #b30f0f;
      border: none;
      border-radius: 30px;
      font-weight: bold;
      font-size: 16px;
      text-decoration: none;
      transition: background 0.3s, transform 0.2s;
    }
    .cta:hover {
      background: #ffff03;
      transform: scale(1.20);
    }
    .strategies p {
      margin: 8px 0;
      padding: 10px;
      border-left: 4px solid  #b30f0f;
      background: #f9faff;
      border-radius: 6px;
      transition: background 0.3s;
    }
    .strategies p:hover {
      background: #eaf0ff;
    }

    footer {
      text-align: center;
      padding: 15px;
      background: #b30f0f;
      color: #ffff03;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Enteng Cheese'desal</h1>
    <p>Deliciously cheesy pandesal, baked fresh daily</p>
    <div class="stripe"></div>
  </header>

  <section class="image-text">
    <div class="image-box"> <img src="enteng.png"> </div>
    <div class="text-boxes">
      <p><strong>Branch Location:</strong> Purok Uno, M. H. Del Pilar, Alicia</p>
      <p><strong>Specialty:</strong> Cheese'desal - soft pandesal filled with creamy cheese</p>
      <p><strong>Hours:</strong> Open daily, 5:30 AM - 6:30 PM</p>
    </div>
  </section>

  <section class="block">
    <h2>COMMUNITY ENGAGEMENT FEATURES</h2>
    <p>• Supporting local farmers by sourcing fresh ingredients</p>
    <p>• Weekend promos for workers and students this December</p>
    <p>• Active participation in barangay events and celebrations</p>
  </section>

  <section class="block">
    <h2>PROMOTIONAL STRATEGIES</h2>
    <a href="#" class="cta">ORDER NOW</a>
    <div class="strategies">
      <p>○ Buy 5 Cheese'desal, Get 1 Free</p>
      <p>○ Loyalty card: Free 3 pandesal after 10 purchases</p>
      <p>○ Social media shoutouts for regular customers</p>
    </div>
  </section>

  <footer>
    &copy; 2025 Enteng Cheese'desal | Purok Uno, M. H. Del Pilar, Alicia
  </footer>
</body>
</html>
