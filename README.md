<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Currículo - Helton Santos de Lima</title>
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 1rem;
      background: #f4f4f4;
      color: #333;
    }
    header {
      background: #fff;
      padding: 1rem 2rem;
      border-bottom: 2px solid #ddd;
      display: flex;
      flex-direction: column;
      gap: 0.5rem;
    }
    h1 {
      margin: 0;
      color: #222;
    }
    .contact {
      font-size: 0.95rem;
      color: #555;
    }
    .contact a {
      color: #0077b6;
      text-decoration: none;
    }
    section {
      background: #fff;
      margin: 1rem 0;
      border-radius: 8px;
      overflow: hidden;
      box-shadow: 0 2px 4px rgba(0,0,0,0.05);
    }
    h2 {
      margin: 0;
      padding: 1rem;
      background: #0077b6;
      color: #fff;
      font-size: 1.1rem;
      cursor: pointer;
    }
    .content {
      display: none;
      padding: 1rem;
    }
    ul {
      padding-left: 1.2rem;
    }
    li {
      margin-bottom: 0.4rem;
    }
    .keywords {
      background-color: #e0f0ff;
      padding: 0.8rem;
      border-radius: 5px;
      font-size: 0.9rem;
    }
    @media (max-width: 600px) {
      header {
        padding: 1rem;
      }
      .contact {
        font-size: 0.85rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>HELTON SANTOS DE LIMA</h1>
    <div class="contact">
      📍 Realengo – Rio de Janeiro/RJ<br />
      📞 (21) 97046-9779<br />
      ✉️ heltonsdl@outlook.com<br />
      🔗 <a href="https://linkedin.com/in/heltonsdl" target="_blank">linkedin.com/in/heltonsdl</a>
    </div>
  </header>

  <section>
    <h2 onclick="toggleSection(this)">🎯 Objetivo</h2>
    <div class="content">
      <p>Atuar como estagiário ou desenvolvedor júnior na área de tecnologia da informação.</p>
    </div>
  </section>

  <section>
    <h2 onclick="toggleSection(this)">🧠 Resumo Profissional</h2>
    <div class="content">
      <p>Estudante de Análise e Desenvolvimento de Sistemas, com background em suporte técnico e processos administrativos. Experiência com sistemas corporativos, atendimento ao cliente e interesse em desenvolvimento full stack e análise de dados. Conhecimentos em lógica de programação, Python, HTML, CSS, Git, banco de dados SQL, terminal Linux e ferramentas como VS Code.</p>
    </div>
  </section>

  <section>
    <h2 onclick="toggleSection(this)">🛠️ Habilidades Técnicas</h2>
    <div class="content">
      <ul>
        <li>Linguagens: Python, HTML5, CSS3</li>
        <li>Versionamento: Git, GitHub</li>
        <li>Web: Front-end, Back-end, APIs</li>
        <li>Dados: Manipulação, Limpeza, Análise</li>
        <li>Banco de Dados: SQL, MySQL</li>
        <li>Ferramentas: VS Code, Linux Terminal</li>
        <li>Conceitos: Lógica, MVC, Automação</li>
      </ul>
    </div>
  </section>

  <section>
    <h2 onclick="toggleSection(this)">💼 Experiência Profissional</h2>
    <div class="content">
      <p><strong>Administrativo de Loja – Grupo DPSP</strong><br>📍 Rio de Janeiro/RJ | 📅 Ago 2021 – Atual<br>
      • Atendimento, controle de estoque e caixa<br>
      • Apoio administrativo com sistemas internos</p>

      <p><strong>Suporte Técnico – Teleperformance</strong><br>📍 São Paulo/SP | 📅 Nov 2019 – Jul 2020<br>
      • Suporte remoto e orientações técnicas<br>
      • Registro de chamados e atendimento via CRM</p>

      <p><strong>Aux. Administrativo – Prime Contábil</strong><br>📍 Rio de Janeiro/RJ | 📅 Jun 2017 – Ago 2018<br>
      • Organização de arquivos e planilhas<br>
      • Cadastro e atualizações em sistemas</p>
    </div>
  </section>

  <section>
    <h2 onclick="toggleSection(this)">🎓 Formação Acadêmica</h2>
    <div class="content">
      <ul>
        <li>MBA em Big Data, BI e Inteligência Competitiva – UVA (Conclusão Prevista: Fev 2025)</li>
        <li>Tecnólogo em Análise e Desenvolvimento de Sistemas – UNINOVE (Conclusão: Mai 2024)</li>
        <li>Ensino Médio – CE Monsenhor Miguel de Santa Maria Móchon (2019)</li>
      </ul>
    </div>
  </section>

  <section>
    <h2 onclick="toggleSection(this)">📚 Cursos Complementares</h2>
    <div class="content">
      <ul>
        <li>Python 3 – Estudonauta / Curso em Vídeo</li>
        <li>Desenvolvimento Web – Dev em Dobro</li>
      </ul>
    </div>
  </section>

  <section>
    <h2 onclick="toggleSection(this)">🔍 Palavras-chave (ATS)</h2>
    <div class="content">
      <p class="keywords">Python, HTML, CSS, SQL, MySQL, Git, GitHub, APIs, VS Code, Linux, Análise de Dados, Automação, Estagiário de TI, Desenvolvedor Júnior, Suporte Técnico</p>
    </div>
  </section>

  <script>
    function toggleSection(header) {
      const content = header.nextElementSibling;
      const isVisible = content.style.display === 'block';
      content.style.display = isVisible ? 'none' : 'block';
    }
    // Inicializa todos os conteúdos como escondidos
    document.addEventListener("DOMContentLoaded", () => {
      document.querySelectorAll('.content').forEach(div => div.style.display = 'none');
    });
  </script>
</body>
</html>
