
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
        
        <div class="card" onclick="!DOCTYPE hUT-8"

    










<style>  :root{
    --size: 220px;        /* tamanho do anel externo */
    --photo-size: 192px;  /* tamanho da foto */
    --ring-thickness: 14px; /* espessura da borda colorida */
  }

  body{
    margin:0;
    height:100vh;
    display:flex;
    align-items:center;
    justify-content:center;
    background:transparent; /* fundo transparente */
  }

  .orb-wrap{
    position:relative;
    width:var(--size);
    height:var(--size);
    display:flex;
    align-items:center;
    justify-content:center;
    animation: bob 4s ease-in-out infinite; /* flutuar */
  }

  .ring{
    position:absolute;
    width:100%;
    height:100%;
    border-radius:50%;
    background: conic-gradient(
      from 0deg,
      #ff6b6b,
      #fbc02d,
      #6ee7b7,
      #60a5fa,
      #c084fc,
      #ff6b6b
    );
    filter: blur(4px) saturate(120%);
    z-index:1;
    animation: spinColors 6s linear infinite;
  }

  .ring::after{
    content:"";
    position:absolute;
    inset:var(--ring-thickness);
    border-radius:50%;
    background:transparent;
    box-shadow: 0 0 0 9999px transparent; /* transparente para deixar só a borda */
  }

  .photo{
    position:relative;
    width:var(--photo-size);
    height:var(--photo-size);
    z-index:2;
    border-radius:50%;
    overflow:hidden;
    display:block;
    box-shadow: inset 0 -6px 18px rgba(0,0,0,0.25);
    background:#fff; /* fundo branco atrás da foto */
  }

  .photo img{
    width:100%;
    height:100%;
    object-fit:cover;
  }

  @keyframes spinColors{
    from{ transform: rotate(0deg); }
    to{ transform: rotate(360deg); }
  }

  @keyframes bob{
    0%{ transform: translateY(0px); }
    50%{ transform: translateY(-14px); }
    100%{ transform: translateY(0px); }
  }
</style>
</head>
<body>

  <div class="orb-wrap">    
    <div class="ring"></div>
    <!-- Troque o src abaixo pela sua foto -->
    <div class="photo">
      <img src="2a25de24b45816bd07db73899e3f6d67.jpg" alt="Sua foto aqui">
    </div>
  </div>
<!-- From Uiverse.io by Praashoo7 --> 









<!-- From Uiverse.io by Praashoo7 --> 








<!-- From Uiverse.io by AlimurtuzaCodes --> 

  <!-- From Uiverse.io by kamehame-ha --> 


  
</head>
<body>

  <style>
  :root{
    --btn-size: 100px; /* tamanho do círculo */
    --gap: 22px;
    --bg: #0b0b0c;
  }

  *{box-sizing:border-box}
  body{
    margin:0;
    min-height:100vh;
    display:grid;
    place-items:center;
    background: linear-gradient(180deg, var(--bg), #080808 80%);
    font-family: Arial, sans-serif;
    color:#fff;
  }

  .btn-grid{
    display:grid;
    grid-template-columns: repeat(2, var(--btn-size));
    gap: var(--gap);
    justify-items:center;
    align-items:center;
    padding: 24px;
  }

  .circle-btn{
    width: var(--btn-size);
    height: var(--btn-size);
    border-radius: 50%;
    overflow: hidden;
    cursor:pointer;
    position: relative;
    transition: transform .25s ease, box-shadow .25s ease;
    box-shadow: 0 12px 30px rgba(0,0,0,0.6);
  }

  .circle-btn:hover{
    transform: scale(1.1);
    box-shadow: 0 20px 40px rgba(0,0,0,0.7);
  }

  /* a imagem fica certinha no círculo */
  .circle-btn img{
    width: 100%;
    height: 100%;
    object-fit: cover; /* preenche o círculo */
    border-radius: 50%;
  }

  @media (max-width:420px){
    :root{ --btn-size: 80px; }
  }




    

  </style>



<style>
  :root{
    --btn-size: 100px; /* tamanho do círculo */
    --gap: 22px;
    --bg: #0b0b0c;
  }

  *{box-sizing:border-box}
  body{
    margin:0;
    min-height:100vh;
    display:grid;
    place-items:center;
    background: linear-gradient(180deg, var(--bg), #080808 80%);
    font-family: Arial, sans-serif;
    color:#fff;
  }

  .btn-grid{
    display:grid;
    grid-template-columns: repeat(2, var(--btn-size));
    gap: var(--gap);
    justify-items:center;
    align-items:center;
    padding: 24px;
  }

  .circle-btn{
    width: var(--btn-size);
    height: var(--btn-size);
    border-radius: 50%;
    overflow: hidden;
    cursor:pointer;
    position: relative;
    transition: transform .25s ease, box-shadow .25s ease;
    box-shadow: 0 12px 30px rgba(0,0,0,0.6);
  }

  .circle-btn:hover{
    transform: scale(1.1);
    box-shadow: 0 20px 40px rgba(0,0,0,0.7);
  }

  /* a imagem fica certinha no círculo */
  .circle-btn img{
    width: 100%;
    height: 100%;
    object-fit: cover; /* preenche o círculo */
    border-radius: 50%;
  }

  @media (max-width:420px){
    :root{ --btn-size: 80px; }
  }
</style>
</head>
<body>


<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Botões de Redes Sociais Animados</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        /* Estilos gerais do corpo da página */
        body {
            margin: 0;
            padding: 0;
            background-color: #282c36; /* Fundo escuro */
            display: flex;
            justify-content: center; /* Centraliza horizontalmente */
            align-items: center;     /* Centraliza verticalmente */
            height: 100vh;           /* Ocupa a altura total da viewport */
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            gap: 30px; /* Espaço entre os botões */
        }

        /* Estilo base para todos os botões de rede social */
        .social-button {
            display: inline-flex; /* Para alinhar o ícone e o texto */
            align-items: center;
            justify-content: center;
            padding: 15px 30px;
            border-radius: 50px; /* Bordas bem arredondadas */
            text-decoration: none; /* Remove sublinhado dos links */
            color: #ffffff; /* Cor do texto e ícone */
            font-size: 20px;
            font-weight: bold;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3); /* Sombra suave */
            transition: all 0.3s ease-in-out; /* Transição suave para todas as propriedades */
            cursor: pointer; /* Indica que é clicável */
        }

        /* Estilo específico para o botão do TikTok */
        .tiktok-button {
            background-color: #222222; /* Cor de fundo do TikTok */
            border: 2px solid #00f2ea; /* Borda ciano */
        }

        /* Efeito de hover para o botão do TikTok */
        .tiktok-button:hover {
            transform: scale(1.1); /* Aumenta o tamanho */
            background-color: #00f2ea; /* Muda a cor de fundo */
            color: #222222; /* Muda a cor do texto */
            box-shadow: 0 8px 20px rgba(0, 242, 234, 0.6); /* Sombra brilhante */
            border-color: #222222; /* Inverte a cor da borda */
        }

        /* Estilo específico para o botão do Instagram */
        .instagram-button {
            background-color: #222222; /* Cor de fundo similar */
            border: 2px solid #d62976; /* Borda rosa/roxo do Instagram */
        }

        /* Efeito de hover para o botão do Instagram */
        .instagram-button:hover {
            transform: scale(1.1); /* Aumenta o tamanho */
            /* Gradiente de fundo do Instagram */
            background: linear-gradient(45deg, #f09433 0%, #e6683c 25%, #dc2743 50%, #cc2366 75%, #bc1888 100%);
            color: #ffffff; /* Garante que o texto fique branco */
            box-shadow: 0 8px 20px rgba(220, 39, 67, 0.6); /* Sombra brilhante */
            border-color: #ffffff; /* Borda branca no hover */
        }

        /* Estilo para os ícones dentro dos botões */
        .social-button i {
            margin-right: 10px; /* Espaçamento entre o ícone e o texto */
            font-size: 24px; /* Tamanho maior para os ícones */
        }
    </style>
</head>
<body>

    <a href="https://www.tiktok.com/@nilton...568?is_from_webapp=1&sender_device=pc" target="_blank" class="social-button tiktok-button">
        <i class="fab fa-tiktok"></i>
        TikTok
    </a>

    <a href="https://www.instagram.com/niltondesouzabittencourtneto?igsh=MWZ4cGM0dW1wYWQ2aA==" target="_blank" class="social-button instagram-button">
        <i class="fab fa-instagram"></i>
        Instagram
    </a>

</body>
</html>


<a href="olk.html">
<button class="projeto1">
  <span>HTML</span>
  <svg width="15px" height="10px" viewBox="0 0 13 10">
    <path d="M1,5 L11,5"></path>
    <polyline points="8 1 12 5 8 9"></polyline>
  </svg>
</button>
</a>



<style>
  /* From Uiverse.io by alexmaracinaru */ 
.cta {
  position: relative;
  margin: auto;
  padding: 12px 18px;
  transition: all 0.2s ease;
  border: none;
  background: none;
  cursor: pointer;
}

.cta:before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  display: block;
  border-radius: 50px;
  background: #b1dae7;
  width: 45px;
  height: 45px;
  transition: all 0.3s ease;
}

.cta span {
  position: relative;
  font-family: "Ubuntu", sans-serif;
  font-size: 18px;
  font-weight: 700;
  letter-spacing: 0.05em;
  color: #234567;
}

.cta svg {
  position: relative;
  top: 0;
  margin-left: 10px;
  fill: none;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke: #234567;
  stroke-width: 2;
  transform: translateX(-5px);
  transition: all 0.3s ease;
}

.cta:hover:before {
  width: 100%;
  background: #b1dae7;
}

.cta:hover svg {
  transform: translateX(0);
}

.cta:active {
  transform: scale(0.95);
}




</style>


<a
  href="css.html">
<button class="cta">
  <span>CSS</span>
  <svg width="15px" height="10px" viewBox="0 0 13 10">
    <path d="M1,5 L11,5"></path>
    <polyline points="8 1 12 5 8 9"></polyline>
  </svg>
</button>
</a>



<style>
  /* From Uiverse.io by alexmaracinaru */ 
.cta {
  position: relative;
  margin: auto;
  padding: 12px 18px;
  transition: all 0.2s ease;
  border: none;
  background: none;
  cursor: pointer;
}

.cta:before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  display: block;
  border-radius: 50px;
  background: #b1dae7;
  width: 45px;
  height: 45px;
  transition: all 0.3s ease;
}

.cta span {
  position: relative;
  font-family: "Ubuntu", sans-serif;
  font-size: 18px;
  font-weight: 700;
  letter-spacing: 0.05em;
  color: #234567;
}

.cta svg {
  position: relative;
  top: 0;
  margin-left: 10px;
  fill: none;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke: #234567;
  stroke-width: 2;
  transform: translateX(-5px);
  transition: all 0.3s ease;
}

.cta:hover:before {
  width: 100%;
  background: #b1dae7;
}

.cta:hover svg {
  transform: translateX(0);
}

.cta:active {
  transform: scale(0.95);
}





</style>


<a href="js.html">
<button class="cta">
  <span>JS</span>
  <svg width="15px" height="10px" viewBox="0 0 13 10">
    <path d="M1,5 L11,5"></path>
    <polyline points="8 1 12 5 8 9"></polyline>
  </svg>
</button>

</a>


<style>
  /* From Uiverse.io by alexmaracinaru */ 
.cta {
  position: relative;
  margin: auto;
  padding: 12px 18px;
  transition: all 0.2s ease;
  border: none;
  background: none;
  cursor: pointer;
}

.cta:before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  display: block;
  border-radius: 50px;
  background: #b1dae7;
  width: 45px;
  height: 45px;
  transition: all 0.3s ease;
}

.cta span {
  position: relative;
  font-family: "Ubuntu", sans-serif;
  font-size: 18px;
  font-weight: 700;
  letter-spacing: 0.05em;
  color: #234567;
}

.cta svg {
  position: relative;
  top: 0;
  margin-left: 10px;
  fill: none;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke: #234567;
  stroke-width: 2;
  transform: translateX(-5px);
  transition: all 0.3s ease;
}

.cta:hover:before {
  width: 100%;
  background: #b1dae7;
}

.cta:hover svg {
  transform: translateX(0);
}

.cta:active {
  transform: scale(0.95);
}





</style>













</body>
</html>">
          <h3>Projeto 1</h3>
          <p>Um site responsivo com design moderno.</p>
        </div>
       ndnd
      
  <h3 >
    Projeto 2</h3>
  <p>Protótipo do login que desenvolvi em HTML e CSS.</p>
</div>

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
