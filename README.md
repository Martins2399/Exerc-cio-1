<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Página Responsiva Simples</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 10px;
      padding: 0;
      background-color: #f0f0f0;
      color: #333;
    }

    header {
      background-color: #4CAF50;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav a {
      margin: 0 10px;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    main {
      margin-top: 20px;
    }

    .box {
      background-color: white;
      padding: 15px;
      margin-bottom: 15px;
      border-radius: 5px;
    }

    /* Responsivo: quando a tela for pequena */
    @media (max-width: 600px) {
      nav a {
        display: block;
        margin: 10px 0;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Minha Página Responsiva</h1>
    <nav>
      <a href="#">Início</a>
      <a href="#">Sobre</a>
      <a href="#">Contato</a>
    </nav>
  </header>

  <main>
    <div class="box">
      <h2>Seção 1</h2>
      <p>Esse é um exemplo simples de conteúdo na página.</p>
    </div>
    <div class="box">
      <h2>Seção 2</h2>
      <p>Este texto está dentro de outra seção para demonstrar a estrutura.</p>
    </div>
  </main>

</body>
</html>
