<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Damytsi - Portfólio</title>
  <style>
    /* Reset básico */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    body {
      background: #f4f7f8;
      color: #333;
      line-height: 1.6;
      padding: 20px;
    }
    header {
      text-align: center;
      padding-bottom: 20px;
    }
    header h1 {
      font-size: 2.5rem;
      color: #007acc;
    }
    header p {
      font-size: 1.1rem;
      color: #555;
      margin-top: 8px;
    }
    nav {
      margin-top: 20px;
      text-align: center;
    }
    nav a {
      text-decoration: none;
      margin: 0 15px;
      color: #007acc;
      font-weight: 600;
      transition: color 0.3s ease;
    }
    nav a:hover {
      color: #004a80;
    }
    section {
      max-width: 900px;
      margin: 30px auto;
      background: #fff;
      border-radius: 8px;
      padding: 25px;
      box-shadow: 0 3px 10px rgba(0,0,0,0.1);
    }
    h2 {
      color: #007acc;
      margin-bottom: 15px;
    }
    ul.projects {
      list-style: none;
    }
    ul.projects li {
      margin-bottom: 15px;
      padding-bottom: 10px;
      border-bottom: 1px solid #eee;
    }
    ul.projects li a {
      color: #333;
      font-weight: 700;
      text-decoration: none;
    }
    ul.projects li a:hover {
      color: #007acc;
      text-decoration: underline;
    }
    footer {
      text-align: center;
      margin-top: 40px;
      color: #777;
      font-size: 0.9rem;
    }
    /* Responsividade */
    @media(max-width: 600px) {
      nav a {
        display: block;
        margin: 10px 0;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>Damytsi</h1>
  <p>Estudante de TSI | Desenvolvedor Web & Mobile | Projeto premiado na FICE 2024</p>
  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#projetos">Projetos</a>
    <a href="#contato">Contato</a>
  </nav>
</header>

<section id="sobre">
  <h2>Sobre Mim</h2>
  <p>Olá! Sou estudante do 5º período de Tecnologia em Sistemas para Internet no Instituto Federal Catarinense - Campus Camboriú. Tenho experiência em linguagens como Java, PHP, Python, JavaScript, HTML, C++, além de trabalhar com frameworks como React e Django. Também atuo com bancos de dados PostgreSQL e MongoDB.</p>
  <p>Meu projeto premiado na Feira de Iniciação Científica e Extensão (FICE) de 2024 envolveu a análise bibliométrica dos artigos científicos da feira, com desenvolvimento de banco de dados e análises estatísticas.</p>
</section>

<section id="projetos">
  <h2>Projetos</h2>
  <ul class="projects">
    <li>
      <a href="https://github.com/damytsi/fice-estudo-bibliometrico" target="_blank" rel="noopener noreferrer">
        FICE – Estudo Bibliométrico
      </a>  
      <p>Análise bibliográfica premiada na FICE 2024. Construção de banco de dados e estatísticas científicas.</p>
    </li>
    <li>
      <a href="#" target="_blank" rel="noopener noreferrer">
        App TCC (Em desenvolvimento)
      </a>
      <p>Aplicativo mobile focado em soluções práticas, utilizando React Native e integração com banco PostgreSQL.</p>
    </li>
    <!-- Adicione mais projetos aqui -->
  </ul>
</section>

<section id="contato">
  <h2>Contato</h2>
  <p>📧 Email: <a href="mailto:seuemail@ifc.edu.br">seuemail@ifc.edu.br</a></p>
  <p>🔗 LinkedIn: <a href="https://www.linkedin.com/in/seu-perfil-aqui" target="_blank" rel="noopener noreferrer">linkedin.com/in/seu-perfil-aqui</a></p>
  <p>🐙 GitHub: <a href="https://github.com/damytsi" target="_blank" rel="noopener noreferrer">github.com/damytsi</a></p>
</section>

<footer>
  &copy; 2025 Damytsi | Desenvolvedor em formação
</footer>

</body>
</html>
