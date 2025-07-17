
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Victoria Melo - Portfólio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Inter', sans-serif;
      background-color: #f5f5f5;
      color: #333;
    }

    header {
      background-color: #111;
      color: #ffd700;
      padding: 2rem 1rem;
      text-align: center;
    }

    nav {
      background-color: #222;
      padding: 0.5rem;
      text-align: center;
    }

    nav a {
      color: #ffd700;
      text-decoration: none;
      margin: 0 1rem;
      font-weight: 600;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #ffffff;
    }

    main {
      max-width: 900px;
      margin: 2rem auto;
      padding: 0 1rem;
    }

    section {
      margin-bottom: 3rem;
      padding: 2rem;
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.05);
    }

    h1, h2 {
      margin-bottom: 1rem;
    }

    h2 {
      color: #222;
      border-bottom: 2px solid #ffd700;
      padding-bottom: 0.3rem;
    }

    p, li {
      font-size: 1rem;
      margin-bottom: 0.7rem;
    }

    ul {
      padding-left: 1.5rem;
    }

    a {
      color: #333;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    .btn {
      display: inline-block;
      background: #ffd700;
      color: #000;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      margin-top: 0.5rem;
      font-weight: 600;
      transition: background 0.3s;
    }

    .btn:hover {
      background: #e6c200;
    }

    footer {
      background-color: #111;
      color: #fff;
      text-align: center;
      padding: 1.5rem 1rem;
      margin-top: 2rem;
    }

    @media (max-width: 600px) {
      nav a {
        display: block;
        margin: 0.5rem 0;
      }

      header h1 {
        font-size: 1.8rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Victoria Melo</h1>
    <p>Suporte Técnico & Marketing Digital</p>
  </header>

  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#habilidades">Habilidades</a>
    <a href="#projetos">Projetos</a>
    <a href="#contato">Contato</a>
  </nav>

  <main>
    <section id="sobre">
      <h2>Sobre Mim</h2>
      <p>
        Em transição para a área de tecnologia, com experiência em suporte técnico, atendimento multicanal e marketing digital. Cursando Análise e Desenvolvimento de Sistemas (UNICID).
      </p>
    </section>

    <section id="habilidades">
      <h2>Habilidades</h2>
      <ul>
        <li>Suporte técnico (hardware, software, impressoras)</li>
        <li>Atendimento ao cliente</li>
        <li>Criação de conteúdo e automações com IA</li>
        <li>Ferramentas: Canva, WhatsApp Business, Trello</li>
      </ul>
    </section>

    <section id="projetos">
      <h2>Projetos</h2>
      <ul>
        <li><a href="#">Sistema de Fidelização - Projeto interno de farmácia</a></li>
        <li><a href="#">Automação com IA - Exemplos práticos</a></li>
        <li><a href="#">Portfólio Profissional em PDF</a> <span class="btn">Ver</span></li>
      </ul>
    </section>

    <section id="contato">
      <h2>Contato</h2>
      <p>Email: <a href="mailto:victoriabarros30@icloud.com">victoriabarros30@icloud.com</a></p>
      <p>WhatsApp: <a href="https://wa.me/5511933400248" target="_blank">(11) 93340-0248</a></p>
      <p>LinkedIn: <a href="https://linkedin.com/in/victoriawho" target="_blank">linkedin.com/in/victoriawho</a></p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Victoria Melo</p>
  </footer>

</body>
</html>

