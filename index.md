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

/* FORÇAR FUNDO EM TODA A PÁGINA */
html, body {
    background: #f7f7f7 !important;
    background-color: #f7f7f7 !important;
}

/* REMOVER FUNDOS DO TEMA QUE SOBRESCREVEM O BODY */
.wrapper,
.site,
.site-header,
.site-footer,
.site-nav,
.page-content,
.page,
.home,
.page-wrapper,
div {
    background: transparent !important;
}

/* GARANTIR QUE NENHUM ELEMENTO HERDE FUNDO BRANCO */
* {
    background-color: transparent !important;
}

/* REAPLICAR FUNDOS ESPECÍFICOS DO SEU DESIGN */
.project-card,
.skill-badge {
    background: #ffffff !important;
}

.project-card:hover {
    background: #fafafa !important;
}

/* ESTILO GERAL */
body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif !important;
    line-height: 1.6 !important;
    margin: 0 auto !important;
    max-width: 900px !important;
    padding: 20px !important;
}

/* HEADER */
.header-container {
    text-align: left !important;
    margin-top: 10px !important;
    margin-bottom: 35px !important;
}

.header-container h1 {
    font-size: 2.6rem !important;
    font-weight: 700 !important;
    margin-bottom: 0 !important;
}

.header-container h2 {
    font-size: 1.2rem !important;
    font-weight: 400 !important;
    margin-top: 8px !important;
    color: #777 !important;
}

/* TÍTULOS DE SEÇÃO */
.section-title {
    font-size: 1.8rem !important;
    margin-top: 40px !important;
    border-bottom: 2px solid #eaeaea !important;
    padding-bottom: 4px !important;
}

/* SKILLS */
.skills-container {
    display: flex !important;
    flex-wrap: wrap !important;
    gap: 12px !important;
    margin-top: 10px !important;
}

.skill-badge {
    display: flex !important;
    align-items: center !important;
    padding: 8px 12px !important;
    border-radius: 8px !important;
    font-size: 0.95rem !important;
    gap: 8px !important;
    border: 1px solid #ddd !important;
}

.skill-badge img {
    width: 20px !important;
    height: 20px !important;
}

/* CARDS DE PROJETOS */
.project-card {
    border: 1px solid #e0e0e0 !important;
    border-radius: 10px !important;
    padding: 18px !important;
    margin-top: 18px !important;
    transition: 0.2s ease-in-out !important;
    box-shadow: 0 1px 3px rgba(0,0,0,0.05) !important;
}

.project-card:hover {
    transform: scale(1.01) !important;
    box-shadow: 0 2px 6px rgba(0,0,0,0.10) !important;
}

.project-title {
    font-size: 1.3rem !important;
    margin-bottom: 6px !important;
}

.project-tech {
    font-weight: 600 !important;
    color: #444 !important;
}

.project-link {
    display: inline-block !important;
    margin-top: 8px !important;
    color: #0366d6 !important;
    font-weight: bold !important;
}

</style>

<!-- HEADER FINAL ESTILIZADO -->
<div class="header-container">
  <h1>{{ page.title }}</h1>
  <h2>{{ page.subtitle }}</h2>
</div>

# 🧑‍💻 Sobre mim

Meu nome é Welington Nogueira, sou graduado em Estatística pela Universidade Federal Fluminense (UFF) e pós-graduado em Análise de Dados, Data Mining e Inteligência Artificial pela FIA. Minha formação une rigor estatístico, pensamento analítico e aplicação de técnicas modernas de machine learning voltadas à solução de problemas de negócio.

Atuo como Cientista de Dados, com experiência sólida nos setores público e de saúde, incluindo projetos estratégicos durante minha atuação na Força Aérea Brasileira. Nesse período, trabalhei com modelagem preditiva, inteligência analítica, governança de dados, análise multivariada, criação de KPIs institucionais e desenvolvimento de soluções que fortalecem a tomada de decisão no nível tático e estratégico.

Desenvolvi modelos estatísticos e preditivos, dashboards executivos, pipelines automatizados em Python, R e SQL, além de estruturar processos que aumentaram eficiência operacional e confiabilidade informacional. Minha atuação integra domínio técnico, visão de negócio e comunicação clara, sempre com foco em transformar dados complexos em soluções práticas, interpretáveis e de impacto real, facilitando a ponte entre equipes técnicas e gestores.

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
  <div class="project-tech">PCA · Análise Fatorial · Estatística Multivariada</div>
  <p>Identificação de fatores latentes que influenciam decisões de compra.</p>
  <a class="project-link" href="https://nbviewer.org/github/WeliNog-Est/portfolio-welinog/raw/main/projetos/Decisão%20de%20compra%20(Análise%20Fatorial)/decisao_analise_fatorial.ipynb">Abrir Projeto →</a>
</div>

<div class="project-card">
  <div class="project-title">🎯 Análise RFM (Marketing Analytics)</div>
  <div class="project-tech">Segmentação · Comportamento do Cliente</div>
  <p>Criação de segmentos estratégicos para ações de marketing e retenção.</p>
  <a class="project-link" href="https://nbviewer.org/github/WeliNog-Est/portfolio-welinog/raw/main/projetos/Análise%20RFM_Marketing/analise_rfm.ipynb">Abrir Projeto →</a>
</div>

<div class="project-card">
  <div class="project-title">👥 Clusterização de Clientes (K-Means)</div>
  <div class="project-tech">K-Means · Elbow Method · Segmentação</div>
  <p>Formação de grupos homogêneos de clientes para direcionamento comercial.</p>
  <a class="project-link" href="https://nbviewer.org/github/WeliNog-Est/portfolio-welinog/raw/main/projetos/Agrupamento%20de%20Clientes%20(K-Means)/grupos_kmeans.ipynb">Abrir Projeto →</a>
</div>

<div class="project-card">
  <div class="project-title">✈️ Classificação de Ocorrências Aeronáuticas</div>
  <div class="project-tech">Regressão Logística · Feature Engineering</div>
  <p>Previsão da severidade de ocorrências com foco em segurança operacional.</p>
  <a class="project-link" href="https://nbviewer.org/github/WeliNog-Est/portfolio-welinog/raw/main/projetos/Classificação%20de%20Ocorrência%20Aeronáutica%20(Regressão%20Logística)/classificacao_ocorrencia_aeronautica.ipynb">Abrir Projeto →</a>
</div>

<div class="project-card">
  <div class="project-title">📊 EDA Multivariada</div>
  <div class="project-tech">ANOVA · Correlação · Análise Exploratória</div>
  <p>Exploração de interações entre variáveis e padrões multivariados.</p>
  <a class="project-link" href="https://nbviewer.org/github/WeliNog-Est/portfolio-welinog/raw/main/projetos/EDA%20Banco%20Multivarido/eda_multivariada.ipynb">Abrir Projeto →</a>
</div>

<div class="project-card">
  <div class="project-title">🌍 Expectativa de Vida (Regressão Linear Múltipla)</div>
  <div class="project-tech">Regressão · Análise Global</div>
  <p>Modelagem dos fatores socioeconômicos que influenciam a expectativa de vida.</p>
  <a class="project-link" href="https://nbviewer.org/github/WeliNog-Est/portfolio-welinog/raw/main/projetos/Expectativa%20de%20Vida%20(Regressão%20Linear%20Múltipla)/regressao_linear_multipla.ipynb">Abrir Projeto →</a>
</div>

<div class="project-card">
  <div class="project-title">🛡️ Fraudes com Criptomoedas (XGBoost)</div>
  <div class="project-tech">XGBoost · Classificação · Detecção de Fraude</div>
  <p>Modelo robusto para detecção de transações suspeitas em exchanges de cripto.</p>
  <a class="project-link" href="https://nbviewer.org/github/WeliNog-Est/portfolio-welinog/raw/main/projetos/Fraudes%20de%20Criptomoedas%20(XGBoost)/fraudes_cripto_xgboost.ipynb">Abrir Projeto →</a>
</div>

---

# 📫 Contato

📧 <strong>nogueiraswns@gmail.com</strong><br>
🔗 <strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/welington-n-99484571/" target="_blank">linkedin.com/in/welington-n-99484571</a><br>
💻 <strong>GitHub:</strong> <a href="https://github.com/WeliNog-Est" target="_blank">github.com/WeliNog-Est</a>




















