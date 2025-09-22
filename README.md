
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfólio - Nilton Neto</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap');

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }

    body {
      min-height: 100vh;
      color: #fff;
      background: linear-gradient(-45deg, #1e1e2f, #3a0ca3, #4361ee, #4cc9f0);
      background-size: 400% 400%;
      animation: gradientBG 12s ease infinite;
    }

    @keyframes gradientBG {
      0% {background-position: 0% 50%;}
      50% {background-position: 100% 50%;}
      100% {background-position: 0% 50%;}
    }

    header {
      width: 100%;
      text-align: center;
      padding: 2rem 0;
    }

    header h1 {
      font-size: 2.8rem;
      margin-bottom: 0.5rem;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      transition: 0.3s;
    }

    nav a:hover {
      color: #4cc9f0;
    }

    .container {
      width: 90%;
      max-width: 1000px;
      margin: 2rem auto;
      background: rgba(255,255,255,0.08);
      border-radius: 20px;
      padding: 2rem;
      backdrop-filter: blur(15px);
      box-shadow: 0 8px 20px rgba(0,0,0,0.3);
    }

    h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
      border-left: 5px solid #4cc9f0;
      padding-left: 10px;
    }

    .sobre {
      display: flex;
      align-items: center;
      gap: 2rem;
      flex-wrap: wrap;
    }

    .sobre img {
      width: 220px;
      height: 220px;
      border-radius: 50%;
      border: 4px solid #4cc9f0;
      box-shadow: 0 0 20px rgba(76,201,240,0.6);
    }

    .projetos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2rem;
    }

    .card {
      background: rgba(255,255,255,0.12);
      padding: 1.5rem;
      border-radius: 15px;
      cursor: pointer;
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .card:hover {
      transform: translateY(-8px);
      box-shadow: 0 8px 25px rgba(0,0,0,0.4);
    }

    .card h3 {
      margin-bottom: 1rem;
      color: #4cc9f0;
    }

    footer {
      text-align: center;
      padding: 1.5rem 0;
      margin-top: 2rem;
      background: rgba(0,0,0,0.4);
    }

    footer a {
      color: #4cc9f0;
      margin: 0 10px;
      text-decoration: none;
    }

    /* Modal */
    .modal {
      display: none;
      position: fixed;
      z-index: 1000;
      top: 0; left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0,0,0,0.7);
      justify-content: center;
      align-items: center;
    }

    .modal-content {
      background: rgba(255,255,255,0.1);
      padding: 20px;
      border-radius: 15px;
      text-align: center;
      backdrop-filter: blur(10px);
      color: #fff;
      max-width: 600px;
      width: 90%;
    }

    .modal img {
      max-width: 100%;
      border-radius: 10px;
    }

    .close {
      position: absolute;
      top: 20px;
      right: 30px;
      font-size: 2rem;
      cursor: pointer;
    }

    /* Projeto 3: animação */
    .loader {
      display: flex;
      justify-content: center;
      gap: 10px;
      margin-top: 20px;
    }

    .dot {
      width: 15px;
      height: 15px;
      background: #4cc9f0;
      border-radius: 50%;
      animation: bounce 0.6s infinite alternate;
    }

    .dot:nth-child(2) { animation-delay: 0.2s; }
    .dot:nth-child(3) { animation-delay: 0.4s; }

    @keyframes bounce {
      from { transform: translateY(0); }
      to { transform: translateY(-15px); }
    }
  </style>
</head>
<body>
  <header>
    <h1>Nilton Neto</h1>
    <p>Desenvolvedor Web | Editor de Vídeo | Designer</p>
    <nav>
      <a href="#sobre">Sobre</a>
      <a href="#projetos">Projetos</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <div class="container">
    <section id="sobre">
      <h2>Sobre Mim</h2>
      <div class="sobre">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQSfQXbMCSnzY9WpL0W6yEsvR0K2jicxM2YJw&s" alt="Minha foto">
        <p>Meu nome é <strong>Nilton de Souza Bittencourt Neto</strong>, tenho 13 anos e sou apaixonado por tecnologia. 
        Busco iniciar minha jornada profissional como desenvolvedor de sites. 
        Também tenho experiência com design gráfico e edição de vídeos, 
        habilidades que considero essenciais para criar soluções digitais criativas e funcionais.</p>
      </div>
    </section>

    <section id="projetos">
      <h2>Projetos</h2>
      <div class="projetos">
        <div class="card" onclick="window.open('http://127.0.0.1:5500/omg111/index.html','_blank')">
          <h3>Projeto 1</h3>
          <p>Um site responsivo com design moderno.</p>
        </div>
       ndnd
       <a href="teste"
  <h3>Projeto 2</h3>
  <p>Protótipo do login que desenvolvi em HTML e CSS.</p>
</div>
</a>
<!-- Modal Projeto 2 -->
<div id="modal2" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('modal2')">&times;</span>
    <h2>Projeto 2</h2>
    <p>Protótipo do login em HTML e CSS:</p>
    <img src="" alt="Projeto 2" style="max-width:100%; border-radius:10px;">
  </div>
</div>
        <div class="card" onclick="openModal('modal3')">
          <h3>Projeto 3</h3>
          <p>Animação divertida feita em CSS.</p>
        </div>
      </div>
    </section>

    <section id="contato">
      <h2>Contato</h2>
      <a href="https://www.instagram.com/niltondesouzabittencourtneto?igsh=MWZ4cGM0dW1wYWQ2aA==" target="_blank">
         <strong>📸 @niltondesouzabittencourtneto </strong> 
        </a>
    </section>
  </div>

  <footer>
    <p>&copy; 2025 - Nilton Neto </p>
  </footer>

  <!-- Modal Projeto 2 -->
  <div id="modal2" class="modal">
    <span class="close" onclick="closeModal('modal2')">&times;</span>
    <div class="modal-content">
      <h2>Projeto 2 - Tela de Login</h2>
      <img src="projeto2.png" alt="Projeto 2">
    </div>
  </div>

  <!-- Modal Projeto 3 -->
  <div id="modal3" class="modal">
    <span class="close" onclick="closeModal('modal3')">&times;</span>
    <div class="modal-content">
      <h2>Projeto 3 - Animação em CSS</h2>
      <div class="loader">
        <div class="dot"></div>
        <div class="dot"></div>
        <div class="dot"></div>
      </div>
    </div>
  </div>

  <script>
    function openModal(id) {
      document.getElementById(id).style.display = 'flex';
    }
    function closeModal(id) {
      document.getElementById(id).style.display = 'none';
    }
  </script>
</body>
</html>
