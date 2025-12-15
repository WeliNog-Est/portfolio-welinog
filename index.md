---
layout: default
title: Ciência de Dados
subtitle: Portfólio de Projetos por Welington Nogueira
---

<style>

/* REMOVER TÍTULO PADRÃO DO TEMA MINIMA */
.page-header,
.post-header,
.post-header h1,
.page-title {
    display: none !important;
}

/* FUNDO GLOBAL */
html, body {
    background: #f7f7f7 !important;
    background-color: #f7f7f7 !important;
}

/* LIMPAR FUNDOS DO TEMA */
.wrapper,
.site,
.site-header,
.site-footer,
.site-nav,
.page-content,
.page,
.home,
.page-wrapper {
    background: transparent !important;
}

* {
    background-color: transparent !important;
}

/* TEXTO GLOBAL */
body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif !important;
    line-height: 1.6 !important;
    margin: 0 auto !important;
    max-width: 900px !important;
    padding: 20px !important;
    color: #2e3440 !important;
}

/* HEADER */
.header-container {
    margin-bottom: 35px !important;
}

.header-container h1 {
    font-size: 2.6rem !important;
    font-weight: 700 !important;
    color: #0f2a44 !important;
}

.header-container h2 {
    font-size: 1.2rem !important;
    font-weight: 400 !important;
    color: #6b7280 !important;
    margin-top: 6px !important;
}

/* TÍTULOS */
h1, h2, h3 {
    color: #0f2a44 !important;
}

/* SKILLS */
.skills-container {
    display: flex !important;
    flex-wrap: wrap !important;
    gap: 12px !important;
}

.skill-badge {
    display: flex !important;
    align-items: center !important;
    background: #f9fafb !important;
    border: 1px solid #e5e7eb !important;
    padding: 8px 12px !important;
    border-radius: 8px !important;
    gap: 8px !important;
    color: #0f2a44 !important;
    font-size: 0.95rem !important;
}

.skill-badge img {
    width: 20px !important;
    height: 20px !important;
}

/* CARDS */
.project-card {
    background: #ffffff !important;
    border: 1px solid #e5e7eb !important;
    border-left: 5px solid #0f2a44 !important;
    border-radius: 10px !important;
    padding: 18px !important;
    margin-top: 18px !important;
    box-shadow: 0 2px 8px rgba(15,42,68,0.05) !important;
    transition: all 0.2s ease-in-out !important;
}

.project-card:hover {
    transform: translateY(-2px) !important;
    box-shadow: 0 6px 18px rgba(15,42,68,0.12) !important;
}

.project-title {
    font-size: 1.3rem !important;
    color: #0f2a44 !important;
}

.project-tech {
    font-weight: 600 !important;
    color: #374151 !important;
    font-size: 0.95rem !important;
}

.project-link {
    display: inline-block !important;
    margin-top: 8px !important;
    color: #1f4fd8 !important;
    font-weight: bold !important;
    text-decoration: none !important;
}

.project-link:hover {
    text-decoration: underline !important;
}

</style>

<!-- HEADER -->
<div class="header-container">
  <h1>{{ page.title }}</h1>
  <h2>{{ page.subtitle }}</h2>
</div>

# 🧑‍💻 Sobre mim

Sou Cientista de Dados, graduado em Estatística pela Universidade Federal Fluminense (UFF) e pós-graduado em Análise de Dados, Data Mining e Inteligência Artificial pela FIA. Atuo há anos com análise estatística, modelagem preditiva e inteligência analítica aplicadas a problemas reais.

Tenho experiência sólida nos setores público e de saúde, incluindo projetos estratégicos desenvolvidos na Força Aérea Brasileira, com foco em governança de dados, indicadores institucionais, epidemiologia e apoio à tomada de decisão.

---

# ⚙️ Skills

<div class="skills-container">
  <div class="skill-badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg">Python</div>
  <div class="skill-badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/r/r-original.svg">R</div>
  <div class="skill-badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg">SQL</div>
  <div class="skill-badge"><img src="https://img.icons8.com/color/48/amazon-web-services.png">AWS</div>
  <div class="skill-badge"><img src="https://img.icons8.com/color/48/power-bi.png">Power BI</div>
  <div class="skill-badge"><img src="https://img.icons8.com/ios-filled/50/000000/combo-chart.png">Métricas de Negócio</div>
  <div class="skill-badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/scikitlearn/scikitlearn-original.svg">Machine Learning</div>
  <div class="skill-badge"><img src="https://img.icons8.com/ios-filled/50/000000/communication.png">Comunicação</div>
  <div class="skill-badge"><img src="https://img.icons8.com/ios-filled/50/000000/idea.png">Criatividade</div>
  <div class="skill-badge"><img src="https://img.icons8.com/ios-filled/50/000000/conference-call.png">Trabalho em equipe</div>
</div>

---

# 📂 Projetos

<div class="project-card">
  <div class="project-title">🔍 Decisão de Compra (Análise Fatorial)</div>
  <div class="project-tech">PCA · Análise Fatorial</div>
  <p>Identificação de fatores latentes que influenciam decisões de compra.</p>
  <a class="project-link" href="https://nbviewer.org/github/WeliNog-Est/portfolio-welinog/raw/main/projetos/Decisão%20de%20compra%20(Análise%20Fatorial)/decisao_analise_fatorial.ipynb">Abrir projeto →</a>
</div>

<div class="project-card">
  <div class="project-title">🎯 Análise RFM</div>
  <div class="project-tech">Marketing Analytics</div>
  <p>Segmentação estratégica de clientes para retenção.</p>
  <a class="project-link" href="https://nbviewer.org/github/WeliNog-Est/portfolio-welinog/raw/main/projetos/Análise%20RFM_Marketing/analise_rfm.ipynb">Abrir projeto →</a>
</div>

<div class="project-card">
  <div class="project-title">👥 Clusterização de Clientes</div>
  <div class="project-tech">K-Means</div>
  <p>Formação de grupos homogêneos de clientes.</p>
  <a class="project-link" href="https://nbviewer.org/github/WeliNog-Est/portfolio-welinog/raw/main/projetos/Agrupamento%20de%20Clientes%20(K-Means)/grupos_kmeans.ipynb">Abrir projeto →</a>
</div>

<div class="project-card">
  <div class="project-title">✈️ Ocorrências Aeronáuticas</div>
  <div class="project-tech">Regressão Logística</div>
  <p>Classificação de severidade de ocorrências.</p>
  <a class="project-link" href="https://nbviewer.org/github/WeliNog-Est/portfolio-welinog/raw/main/projetos/Classificação%20de%20Ocorrência%20Aeronáutica%20(Regressão%20Logística)/classificacao_ocorrencia_aeronautica.ipynb">Abrir projeto →</a>
</div>

<div class="project-card">
  <div class="project-title">📊 EDA Multivariada</div>
  <div class="project-tech">Análise Exploratória</div>
  <p>Exploração de padrões multivariados.</p>
  <a class="project-link" href="https://nbviewer.org/github/WeliNog-Est/portfolio-welinog/raw/main/projetos/EDA%20Banco%20Multivarido/eda_multivariada.ipynb">Abrir projeto →</a>
</div>

<div class="project-card">
  <div class="project-title">🌍 Expectativa de Vida</div>
  <div class="project-tech">Regressão Linear Múltipla</div>
  <p>Modelagem de fatores socioeconômicos.</p>
  <a class="project-link" href="https://nbviewer.org/github/WeliNog-Est/portfolio-welinog/raw/main/projetos/Expectativa%20de%20Vida%20(Regressão%20Linear%20Múltipla)/regressao_linear_multipla.ipynb">Abrir projeto →</a>
</div>

<div class="project-card">
  <div class="project-title">🛡️ Fraudes com Criptomoedas</div>
  <div class="project-tech">XGBoost</div>
  <p>Detecção de fraudes em transações financeiras.</p>
  <a class="project-link" href="https://nbviewer.org/github/WeliNog-Est/portfolio-welinog/raw/main/projetos/Fraudes%20de%20Criptomoedas%20(XGBoost)/fraudes_cripto_xgboost.ipynb">Abrir projeto →</a>
</div>

---

# 🧩 Consultoria

<div class="project-card">
  <div class="project-title">📊 Perfil Materno e Desfechos Neonatais — SINASC</div>
  <div class="project-tech">R · Estatística · Saúde Pública</div>
  <p>Análise epidemiológica de gestações gemelares no Brasil (2017–2023) com dados do SINASC.</p>
  <a class="project-link" href="https://welinog-est.github.io/portfolio-welinog/consultoria/SINASC/" target="_blank">Abrir visualização →</a>
</div>

<div class="project-card">
  <div class="project-title">🩺 Diabetes e Fatores Associados — PNS</div>
  <div class="project-tech">R · Regressão Logística · Saúde Pública</div>
  <p>Análise dos fatores associados ao diagnóstico de diabetes no Brasil usando dados da PNS.</p>
  <a class="project-link" href="https://welinog-est.github.io/portfolio-welinog/consultoria/PNS_diabetes/" target="_blank">Abrir visualização →</a>
</div>

<div class="project-card">
  <div class="project-title">🩸 Anemia e Fatores Associados em Indígenas</div>
  <div class="project-tech">R · Epidemiologia · Regressão</div>
  <p>Estudo transversal sobre anemia e fatores associados entre adultos indígenas Xavante.</p>
  <a class="project-link" href="https://welinog-est.github.io/portfolio-welinog/consultoria/anemia_xavante/" target="_blank">Abrir visualização →</a>
</div>

<div class="project-card">
  <div class="project-title">🏥 Internações e Fatores Associados</div>
  <div class="project-tech">R · Estatística · Qui-Quadrado + V de Crammer</div>
  <p>Análise de internações com testes de independência e regressão logística para identificação de fatores associados.</p>
  <a class="project-link" href="https://welinog-est.github.io/portfolio-welinog/consultoria/internacao/" target="_blank">Abrir visualização →</a>
</div>

---

# 📫 Contato

📧 <strong>nogueiraswns@gmail.com</strong><br>
🔗 <strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/welington-n-99484571/" target="_blank">linkedin.com/in/welington-n-99484571</a><br>
💻 <strong>GitHub:</strong> <a href="https://github.com/WeliNog-Est" target="_blank">github.com/WeliNog-Est</a>






























