<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>R.A. Anodização</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #f5f5f5;
      color: #222;
    }

    header {
      background: #111;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      background: #222;
      padding: 10px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      color: #333;
      margin-bottom: 20px;
    }

    .colors {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    .color-box {
      width: 120px;
      height: 40px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-weight: bold;
      border-radius: 4px;
    }

    .whatsapp-button {
      display: inline-block;
      background: #25d366;
      color: white;
      padding: 15px 25px;
      border-radius: 8px;
      font-size: 16px;
      font-weight: bold;
      text-decoration: none;
      position: fixed;
      bottom: 20px;
      right: 20px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
    }

    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>R.A. ANODIZAÇÃO</h1>
    <p>Especialistas em anodização de alumínio em diversas cores</p>
  </header>

  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#servicos">Serviços</a>
    <a href="#contato">Contato</a>
  </nav>

  <section id="sobre">
    <h2>Sobre nós</h2>
    <p>A R.A. Anodização oferece serviços de anodização de alumínio com qualidade, tecnologia e acabamento impecável. Trabalhamos com uma variedade de cores para atender diferentes necessidades e estilos.</p>
  </section>

  <section id="servicos">
    <h2>Serviços e Cores Disponíveis</h2>
    <p>Confira abaixo as opções de anodização disponíveis:</p>
    <div class="colors">
      <div class="color-box" style="background: black;">Preto</div>
      <div class="color-box" style="background: #4b4b4b;">Grafite</div>
      <div class="color-box" style="background: #c0c0c0; color: #000;">Natural</div>
      <div class="color-box" style="background: #001f4d;">Azul Escuro</div>
      <div class="color-box" style="background: #7ec8e3; color: #000;">Azul Bebê</div>
      <div class="color-box" style="background: #ff007f;">Rosa Pink</div>
      <div class="color-box" style="background: #e7b9c2; color: #000;">Rosé</div>
      <div class="color-box" style="background: red;">Vermelho</div>
      <div class="color-box" style="background: gold; color: #000;">Dourado</div>
      <div class="color-box" style="background: purple;">Roxo</div>
    </div>
  </section>

  <section id="contato">
    <h2>Contato</h2>
    <p>Entre em contato conosco pelo WhatsApp e faça seu orçamento!</p>
    <a href="https://wa.me/+5511977421765" class="whatsapp-button" target="_blank">Fale conosco no WhatsApp</a>
  </section>

  <footer>
    <p>&copy; 2025 R.A. ANODIZAÇÃO – Todos os direitos reservados.</p>
  </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Catálogo - R.A. Anodização</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
    }
    header {
      background: #111;
      color: white;
      padding: 20px;
      text-align: center;
    }
    h1 {
      margin: 0;
    }
    .catalogo {
      max-width: 1200px;
      margin: 30px auto;
      padding: 20px;
      background: white;
      border-radius: 8px;
    }
    .grid {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    .item {
      background: #fff;
      border: 1px solid #ddd;
      border-radius: 8px;
      padding: 10px;
      width: 280px;
      text-align: center;
    }
    .item img {
      max-width: 100%;
      border-radius: 5px;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 30px;
    }
    table, th, td {
      border: 1px solid #ddd;
    }
    th, td {
      padding: 10px;
      text-align: center;
    }
    th {
      background: #111;
      color: white;
    }
  </style>
</head>
<body>

<header>
  <h1>Catálogo - R.A. Anodização</h1>
  <p>Peças anodizadas até 1 metro em diversas cores</p>
</header>

<div class="catalogo">
  <h2>Galeria de Peças</h2>
  <div class="grid">
    <div class="item">
      <img src="imagens/preto.jpg" alt="Peça na cor Preto">
      <p>Peça na cor Preto</p>
    </div>
    <div class="item">
      <img src="imagens/grafite.jpg" alt="Peça na cor Grafite">
      <p>Peça na cor Grafite</p>
    </div>
    <!-- Adicione mais itens conforme as imagens -->
  </div>

  <h2>Tabela de Descrição</h2>
  <table>
    <tr>
      <th>Peça</th>
      <th>Cor</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td>Perfil Retangular</td>
      <td>Preto</td>
      <td>Alumínio anodizado até 1 metro</td>
    </tr>
    <tr>
      <td>Tubo Redondo</td>
      <td>Grafite</td>
      <td>Tubo 2" anodizado até 1 metro</td>
    </tr>
    <tr>
      <td>Cantoneira L</td>
      <td>Natural</td>
      <td>Cantoneira 20x20mm anodizada</td>
    </tr>
    <!-- Adicione mais linhas conforme necessário -->
  </table>
</div>

</body>
</html>
/site
│── index.html
└── /imagens
    ├── preto.jpg
    ├── grafite.jpg
    ├── natural.jpg
    ├── azul-escuro.jpg
    ├── azul-bebe.jpg
    ├── rosa-pink.jpg
    ├── rose.jpg
    ├── vermelho.jpg
    ├── dourado.jpg
    └── roxo.jpg
