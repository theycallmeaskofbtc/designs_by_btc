<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Designs by BTC</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0f0f0f;
      color: white;
    }

    header {
      padding: 20px;
      text-align: center;
      background: #111;
      font-size: 24px;
      font-weight: bold;
      letter-spacing: 2px;
    }

    .hero {
      padding: 60px 20px;
      text-align: center;
    }

    .hero h1 {
      font-size: 40px;
      margin-bottom: 10px;
    }

    .hero p {
      color: #aaa;
    }

    .btn {
      margin-top: 20px;
      padding: 10px 20px;
      background: white;
      color: black;
      border: none;
      cursor: pointer;
      border-radius: 5px;
    }

    .btn:hover {
      background: #ddd;
    }
  </style>
</head>

<body>

  <header>DESIGNS BY BTC</header>

  <div class="hero">
    <h1>Welcome 👋</h1>
    <p>I design clean modern visuals and websites</p>
    <button class="btn">View Portfolio</button>
  </div>

</body><header>DESIGNS BY BTC</header>

<div class="hero">
  <h1>Welcome 👋</h1>
  <p>I design clean modern visuals and websites</p>
  <button class="btn">View Portfolio</button>
</div>

<section class="gallery">
  <h2>My Designs</h2>

  <div class="grid">
    <div class="card">Design 1</div>
    <div class="card">Design 2</div>
    <div class="card">Design 3</div>
    <div class="card">Design 4</div>
  </div>
</section>
</html>.gallery {
  padding: 40px 20px;
  text-align: center;
}

.gallery h2 {
  margin-bottom: 20px;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
  gap: 15px;
  padding: 10px;
}

.card {
  background: #1c1c1c;
  padding: 40px;
  border-radius: 10px;
  border: 1px solid #333;
  transition: 0.3s;
}

.card:hover {
  transform: scale(1.05);
  background: #2a2a2a;
}
