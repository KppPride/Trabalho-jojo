<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Exercício de CSS</title>

  <style>
    /* Seletor por TAG */
    body {
      background-color: #851ABA;
      font-family: Arial, sans-serif;
    }

    h1 {
      color: blue;
      text-align: center;
    }

    /* Seletor por CLASSE */
    .destaque {
      color: red;
      font-weight: bold;
    }

    /* Seletor por ID */
    #rodape {
      background-color: #6EF2FF;
      color: white;
      text-align: center;
      padding: 10px;
      margin-top: 20px;
    }

    /* Seletor por TAG */
    h2 {
      color: green;
    }
  </style>
</head>
<body>

  <h1>Loja Eletrônica Celulares</h1>
  <p>Confira as promoções:</p>

  <h2>Assistênica de Celular</h2>
  <p>Concerte celular, ou compre um novo.</p>

  <h2 class="destaque">Manutenção</h2>
  <p>Conserto de eletrônicos.</p>

  <h2>Venda de Celulares</h2>
  <p>Todas as Marcas.</p>

  <div id="rodape">
    © 2025 Miguel Tek
  </div>

</body>
</html>
