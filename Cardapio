<!DOCTYPE html><html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cardápio Maverick</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #111;
      margin: 0;
      padding: 0;
      color: #f8f8f8;
    }
    header {
      background: #d62828;
      color: #fff;
      text-align: center;
      padding: 25px 15px;
      box-shadow: 0px 4px 10px rgba(0,0,0,0.4);
    }
    h1 {
      margin: 0;
      font-size: 2.4rem;
      letter-spacing: 1px;
    }
    .categoria {
      background: #1c1c1c;
      margin: 20px;
      padding: 20px;
      border-radius: 16px;
      box-shadow: 0px 4px 12px rgba(0,0,0,0.5);
    }
    .categoria h2 {
      margin-bottom: 15px;
      font-size: 1.6rem;
      color: #ffba08;
      border-bottom: 2px solid #d62828;
      padding-bottom: 5px;
    }
    .produto {
      margin-bottom: 18px;
      padding-bottom: 12px;
      border-bottom: 1px solid #333;
    }
    .produto:last-child {
      border: none;
    }
    .produto h3 {
      margin: 0;
      font-size: 1.2rem;
      color: #fff;
      display: flex;
      justify-content: space-between;
    }
    .produto p {
      margin: 5px 0 0;
      font-size: 0.95rem;
      color: #ccc;
    }
    .preco {
      font-weight: bold;
      color: #ffba08;
      margin-left: 10px;
    }
    #qrcode {
      display: flex;
      flex-direction: column;
      align-items: center;
      margin-top: 20px;
      padding: 10px;
      background: #fff;
      border-radius: 16px;
      width: max-content;
      margin-left: auto;
      margin-right: auto;
    }
    #qrcode p {
      margin-top: 10px;
      color: #111;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <header>
    <h1>🍔 Cardápio Maverick</h1>
  </header>  <!-- Categorias com exemplos de produtos -->  <section class="categoria">
    <h2>Baratíssimos Maverick</h2>
    <div class="produto">
      <h3>Maverick Salada 80g <span class="preco">R$19,90</span></h3>
      <p>Delicioso burger smash artesanal de 80g, queijo cremoso, salada, tomates frescos e maionese da casa em pão de gergelim.</p>
    </div>
    <div class="produto">
      <h3>Maverick Melt 80g <span class="preco">R$21,90</span></h3>
      <p>Hambúrguer smash 80g, cheddar cremoso, cebola caramelizada, molho barbecue em pão australiano selado.</p>
    </div>
  </section>  <section class="categoria">
    <h2>Milk Shake 500ml</h2>
    <div class="produto"><h3>Milk Shake de Paçoca <span class="preco">R$18,00</span></h3></div>
    <div class="produto"><h3>Milk Shake de Nutella <span class="preco">R$19,00</span></h3></div>
  </section>  <section class="categoria">
    <h2>Porções</h2>
    <div class="produto"><h3>Onion Rings 8 Unidades <span class="preco">R$14,90</span></h3><p>Crocantes e sequinhas.</p></div>
    <div class="produto"><h3>Nuggets de Frango 4 Unidades <span class="preco">R$9,90</span></h3></div>
  </section>  <!-- QR Code do cardápio -->  <section class="categoria">
    <h2>QR Code do Cardápio</h2>
    <div id="qrcode">
      <p>Escaneie para acessar o cardápio completo</p>
    </div>
  </section>  <script src="https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js"></script>  <script>
    var urlDoCardapio = "https://seusite.com/cardapio.html"; // substitua pela URL real
    new QRCode(document.getElementById("qrcode"), {
      text: urlDoCardapio,
      width: 200,
      height: 200,
      colorDark : "#000000",
      colorLight : "#ffffff",
      correctLevel : QRCode.CorrectLevel.H
    });
  </script></body>
</html>
