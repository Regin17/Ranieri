<!Doctype html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <style>
    }
    header {
      background-color: #000000;
      color: white;
      padding: 20px 0;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #f5d104;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
      transition: background 0.3s;
    }
    nav a:hover {
      background-color: #e605b5;
    }
    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .servicos {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }
    .card {
      flex: 1;
      min-width: 250px;
      background: #f4f4f4;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 8px rgba(0, 0, 0, 0.1);
    }
    footer {
      background-color: #000000;
      color: white;
      text-align: center;
      padding: 15px 10px;
    }
  </style>
</head>
<body>
     <header>
    <!-- Imagem da fachada -->
    <img src="imagem.jpg.jpg" alt="Foto Ranieri Cell - Fachada da loja" />
  </header>

  <nav>
    <a href="#inicio">Início</a>
    <a href="#sobre">Sobre</a>
    <a href="#servicos">Serviços</a>
    <a href="#contato">Contato</a>
  </nav>

  <section id="inicio">
    <h2>Bem-vindo à Foto Ranieri</h2>
    <p>Somos especialistas em oferecer soluções personalizadas para ajudar você no que precisar.</p>
  </section>

  <section id="sobre">
    <h2>Sobre Nós</h2>
    <p>A Copiadora ranieri atua há mais de 29 anos anos no mercado, com foco em qualidade, inovação e atendimento ao cliente.</p>
  </section>

  <section id="servicos">
    <h2>Nossos Serviços</h2>
    <div class="servicos">
      <div class="card">
        <h3>Aqui fazemos</h3>
          <h3>Troca de pelicula </h3>    
        <h3>Xerox</h3>
         <h3>Assistência Técnica para celular</h3>
          <h3>Impressões Diversas</h3>
          <h3>E Muito mais</h3>
       
      <div class="card">
        <h3>Suporte Técnico</h3>
        <p>Fazemos Também </p>
        <p>Conserto de celular </p>
        <p>Reset tanto para celular quanto para computador</p>
        <p>Tiramos virus</p>
      </div>
    </div>
  </section>

  <section id="contato">
    <h2>Fale Conosco</h2>
    <p>Email: fotoranieribackup@gmail.com</p>
    <p>Telefone: (11) 9.7020-5469</p>
    <p>Endereço: Rua alvaro ferreira, 28 - São Paulo, SP</p>
  </section>

  <footer>
    <p>&copy; 1996 Foto Copiadora Ranieri cell . Todos os direitos reservados.</p>
  </footer>

</body>
</html>
