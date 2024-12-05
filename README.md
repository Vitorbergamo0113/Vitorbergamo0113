<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Site Responsivo</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Cabeçalho -->
  <header class="header">
    <div class="logo">Logo</div>
    <nav class="menu">
      <ul>
        <li><a href="#">Início</a></li>
        <li><a href="#">Produtos</a></li>
        <li><a href="#">Contato</a></li>
      </ul>
    </nav>
    <div class="menu-hamburguer">☰</div>
  </header>

  <!-- Banner -->
  <section class="banner">
    <h1>Bem-vindo ao Nosso Site</h1>
    <p>Encontre os melhores produtos aqui.</p>
    <input type="text" placeholder="Pesquisar...">
  </section>

  <!-- Carrossel -->
  <section class="carrossel">
    <div class="swiper-container">
      <div class="swiper-wrapper">
        <div class="swiper-slide">Slide 1</div>
        <div class="swiper-slide">Slide 2</div>
        <div class="swiper-slide">Slide 3</div>
      </div>
      <div class="swiper-pagination"></div>
    </div>
  </section>

  <!-- Cards -->
  <section class="cards">
    <div class="card">
      <img src="imagem1.jpg" alt="Produto 1">
      <h3>Produto 1</h3>
      <p>Descrição do produto 1.</p>
    </div>
    <div class="card">
      <img src="imagem2.jpg" alt="Produto 2">
      <h3>Produto 2</h3>
      <p>Descrição do produto 2.</p>
    </div>
    <div class="card">
      <img src="imagem3.jpg" alt="Produto 3">
      <h3>Produto 3</h3>
      <p>Descrição do produto 3.</p>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <p>&copy; 2024 - Todos os direitos reservados.</p>
    <form>
      <input type="email" placeholder="Seu e-mail">
      <button type="submit">Enviar</button>
    </form>
  </footer>

  <script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>
  <script>
    const swiper = new Swiper('.swiper-container', {
      pagination: {
        el: '.swiper-pagination',
        clickable: true,
      },
    });
  </script>
</body>
</html>
