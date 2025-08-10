# Mk2-store
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mike Store</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@500;700&display=swap');

    body {
      margin: 0;
      font-family: 'Orbitron', sans-serif;
      background: linear-gradient(180deg, #001a33, #000000);
      color: white;
      text-align: center;
    }

    header {
      padding: 40px 20px;
      background: radial-gradient(circle at center, #0066ff, #000);
      box-shadow: 0 0 25px #00aaff;
      border-bottom: 2px solid rgba(255,255,255,0.1);
      animation: glowHeader 3s infinite alternate;
    }

    @keyframes glowHeader {
      0% { box-shadow: 0 0 15px #00f0ff; }
      100% { box-shadow: 0 0 35px #00f0ff; }
    }

    header img {
      max-width: 180px;
      display: block;
      margin: 0 auto 15px;
      border-radius: 12px;
      box-shadow: 0 0 30px #00f0ff;
      animation: glowLogo 2s infinite alternate;
    }

    @keyframes glowLogo {
      0% { box-shadow: 0 0 20px #00f0ff; }
      100% { box-shadow: 0 0 50px #00f0ff; }
    }

    h1 {
      font-size: 3rem;
      text-shadow: 0 0 20px #00f0ff, 0 0 40px #00aaff;
      margin: 0;
      animation: textGlow 1.5s infinite alternate;
    }

    @keyframes textGlow {
      0% { text-shadow: 0 0 15px #00f0ff, 0 0 30px #00aaff; }
      100% { text-shadow: 0 0 25px #00ffff, 0 0 50px #00ccff; }
    }

    p.sub {
      font-size: 1.2rem;
      color: #cceeff;
      text-shadow: 0 0 10px #0099ff;
      animation: flicker 2s infinite;
    }

    @keyframes flicker {
      0%, 18%, 22%, 25%, 53%, 57%, 100% { opacity: 1; }
      20%, 24%, 55% { opacity: 0.4; }
    }

    /* Banner animado */
    .banner {
      background: url('https://i.imgur.com/gRnbXfX.jpeg') center/cover no-repeat;
      height: 250px;
      display: flex;
      justify-content: center;
      align-items: center;
      margin: 40px 0;
      box-shadow: 0 0 30px #00f0ff;
      animation: pulse 3s infinite alternate;
    }

    @keyframes pulse {
      0% { box-shadow: 0 0 15px #00f0ff; }
      100% { box-shadow: 0 0 40px #00f0ff; }
    }

    .banner h2 {
      font-size: 2rem;
      background: rgba(0,0,0,0.6);
      padding: 15px 25px;
      border-radius: 10px;
      text-shadow: 0 0 15px #00f0ff;
    }

    /* Ícones de categorias */
    .categorias {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      margin: 40px auto;
      max-width: 1000px;
    }

    .cat-item {
      background: rgba(0,0,0,0.5);
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 0 15px #00f0ff;
      width: 180px;
      transition: 0.3s;
    }

    .cat-item:hover {
      transform: scale(1.05);
      box-shadow: 0 0 30px #00f0ff;
    }

    .cat-item i {
      font-size: 2.5rem;
      margin-bottom: 10px;
      color: #00e6ff;
      text-shadow: 0 0 10px #00f0ff;
    }

    footer {
      padding: 40px 20px;
      background: #000;
      border-top: 2px solid rgba(255,255,255,0.1);
    }

    .discord-link {
      background: #5865F2;
      color: white;
      padding: 15px 35px;
      border-radius: 10px;
      text-decoration: none;
      font-size: 1.2rem;
      display: inline-block;
      box-shadow: 0 0 20px #5865F2;
      transition: 0.3s;
      animation: glowDiscord 2s infinite alternate;
    }

    @keyframes glowDiscord {
      0% { box-shadow: 0 0 15px #5865F2; }
      100% { box-shadow: 0 0 35px #5865F2; }
    }

    .discord-link:hover {
      background: #4752C4;
    }
  </style>
</head>
<body>

  <header>
    <img src="logo.png" alt="Mike Store Logo">
    <h1>Mike Store</h1>
    <p class="sub">Steal a Brainrot - O melhor do mundo gamer</p>
  </header>

  <!-- Banner principal -->
  <div class="banner">
    <h2>🔥 Promoções Imperdíveis! 🔥</h2>
  </div>

  <!-- Categorias -->
  <section class="categorias">
    <div class="cat-item">
      <i class="fas fa-gamepad"></i>
      <p>Jogos</p>
    </div>
    <div class="cat-item">
      <i class="fas fa-headset"></i>
      <p>Acessórios</p>
    </div>
    <div class="cat-item">
      <i class="fas fa-tshirt"></i>
      <p>Roupas Gamer</p>
    </div>
    <div class="cat-item">
      <i class="fas fa-gift"></i>
      <p>Gift Cards</p>
    </div>
  </section>

  <footer>
    <p>Entre na nossa comunidade no Discord:</p>
    <a class="discord-link" href="https://discord.gg/rGwtNSnE" target="_blank">Acessar Discord</a>
  </footer>


    <div style="text-align:center; margin: 50px 0;">
        <a href="https://discord.gg/rGwtNSnE" target="_blank" 
           style="display:inline-block; background: linear-gradient(90deg, #8e2de2, #4a00e0); 
                  color: white; padding: 15px 30px; font-size: 20px; font-weight: bold; 
                  border-radius: 30px; text-decoration: none; box-shadow: 0px 4px 15px rgba(0,0,0,0.3); 
                  transition: transform 0.2s;">
            🛒 Entrar na Loja no Discord
        </a>
    </div>
    <script>
        document.querySelector('a[href="https://discord.gg/rGwtNSnE"]').addEventListener('mouseover', function() {
            this.style.transform = 'scale(1.1)';
        });
        document.querySelector('a[href="https://discord.gg/rGwtNSnE"]').addEventListener('mouseout', function() {
            this.style.transform = 'scale(1)';
        });
    </script>
    </body>
</html>
