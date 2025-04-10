!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Meu Portfólio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Olá, eu sou Seu Nome</h1>
    <p>Desenvolvedor(a) Web | Criador(a) de Projetos</p>
  </header>

  <section class="portfolio">
    <h2>Meus Projetos</h2>

    <div class="projeto">
      <img src="images/projeto1.png" alt="Projeto 1">
      <h3>Projeto 1</h3>
      <p>Descrição breve do projeto 1.</p>
      <a href="https://link-do-projeto1.com" target="_blank">Ver projeto</a>
    </div>

    <div class="projeto">
      <img src="images/projeto2.png" alt="Projeto 2">
      <h3>Projeto 2</h3>
      <p>Descrição breve do projeto 2.</p>
      <a href="https://link-do-projeto2.com" target="_blank">Ver projeto</a>
    </div>

    <!-- Adicione mais projetos abaixo, se quiser -->
  </section>

  <footer>
    <p>© 2025 - Seu Nome</p>
  </footer>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f9f9f9;
  color: #333;
}

header {
  background-color: #282c34;
  color: white;
  padding: 2rem;
  text-align: center;
}

.portfolio {
  padding: 2rem;
}

.projeto {
  background-color: white;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
  margin-bottom: 2rem;
  padding: 1rem;
}

.projeto img {
  max-width: 100%;
  border-radius: 5px;
}

.projeto h3 {
  margin-top: 1rem;
}

.projeto a {
  display: inline-block;
  margin-top: 0.5rem;
  text-decoration: none;
  color: #0066cc;
}

footer {
  background-color: #282c34;
  color: white;
  text-align: center;
  padding: 1rem;
}
meu-portfolio/
│
├── index.html
├── style.css
└── images/
    ├── projeto1.png
    └── projeto2.png
