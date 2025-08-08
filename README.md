# o-lobo-de-wall-street
venda
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <title>Lobo de Wall Street - Site de Vendas</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      margin: 0; padding: 0;
    }
    header {
      background-color: #111;
      color: gold;
      text-align: center;
      padding: 20px;
    }
    nav a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
    }
    main {
      max-width: 700px;
      margin: 20px auto;
      padding: 20px;
      background: white;
      border-radius: 8px;
    }
    section {
      margin-bottom: 40px;
    }
    .produto {
      margin-bottom: 30px;
      padding: 20px;
      border: 1px solid #ddd;
      border-radius: 6px;
      text-align: center;
    }
    .produto h2 {
      margin-top: 0;
    }
    .botao {
      display: inline-block;
      background-color: gold;
      color: black;
      padding: 12px 25px;
      text-decoration: none;
      font-weight: bold;
      border-radius: 5px;
      margin-top: 10px;
    }
    #pixInfo, #pixInfo2 {
      background: #fff3cd;
      border: 1px solid #ffeeba;
      color: #856404;
      padding: 15px;
      margin-bottom: 15px;
      border-radius: 5px;
      font-weight: bold;
      text-align: center;
      cursor: pointer;
      user-select: all;
    }
    footer {
      background-color: #111;
      color: gold;
      text-align: center;
      padding: 10px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

<header>
  <h1>Lobo de Wall Street - Vendas</h1>
  <nav>
    <a href="#produtos">Produtos</a>
    <a href="#contato">Contato</a>
  </nav>
</header>

<main>

  <section id="produtos">
    <h2>Produtos</h2>

    <div class="produto">
      <h2>Consulta Rápida - R$5</h2>
      <p>Antes de acessar, faça o pagamento via PIX:</p>
      <div id="pixInfo" onclick="mostrarLink('produto1')" title="Clique aqui após realizar o pagamento para liberar o acesso">
        PIX: <strong>susucertesa@gmail.com</strong><br>
        Clique aqui após realizar o pagamento para liberar o acesso
      </div>
      <a id="produto1" class="botao" href="https://t.me/puxadasdolobinhooo/2895260" target="_blank" style="display:none;">
        Acessar Conteúdo
      </a>
    </div>

    <div class="produto">
      <h2>CPF/CNPJ Checker - R$5</h2>
      <p>Antes de acessar, faça o pagamento via PIX:</p>
      <div id="pixInfo2" onclick="mostrarLink('produto2')" title="Clique aqui após realizar o pagamento para liberar o acesso">
        PIX: <strong>susucertesa@gmail.com</strong><br>
        Clique aqui após realizar o pagamento para liberar o acesso
      </div>
      <a id="produto2" class="botao" href="https://t.me/puxadasdolobinhooo/2895260" target="_blank" style="display:none;">
        Acessar Conteúdo
      </a>
    </div>

  </section>

  <section id="contato">
    <h2>Contato</h2>
    <p>Entre em contato conosco pelo Discord:</p>
    <a href="https://discord.gg/CKyfMYS3" target="_blank">https://discord.gg/CKyfMYS3</a>
  </section>

</main>

<footer>
  <p>&copy; 2025 Lobo de Wall Street. Todos os direitos reservados.</p>
</footer>

<script>
  function mostrarLink(id) {
    document.getElementById('pixInfo').style.display = 'none';
    document.getElementById('pixInfo2').style.display = 'none';
    document.getElementById(id).style.display = 'inline-block';
  }
</script>

</body>
</html>
