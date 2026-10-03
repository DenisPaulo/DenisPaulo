<div align="center">
  <h1>👋 Denis Paulo</h1>
  <h3>Do chão de fábrica (ABB/PLC) para TI &amp; Engenharia de Dados</h3>
  <p>Transformando experiência em automação industrial e manutenção em soluções de dados confiáveis com Python, SQL e Machine Learning</p>

  <a href="https://www.linkedin.com/in/denispaulodiassilva/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:denispaulo.silva@outlook.com">
    <img src="https://img.shields.io/badge/Email-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white" alt="Email"/>
  </a>
</div>

<br>

<div align="center">
  <img height="170em" src="https://github-readme-stats-one-bice.vercel.app/api?username=DenisPaulo&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&locale=pt-br&hide_border=true" alt="Estatísticas GitHub"/>
  <img height="170em" src="https://github-readme-stats-one-bice.vercel.app/api/top-langs/?username=DenisPaulo&layout=compact&langs_count=6&theme=tokyonight&locale=pt-br&custom_title=Tecnologias&hide_border=true" alt="Tecnologias mais usadas"/>
</div>

---

## 🚀 Sobre Mim

Venho da **automação industrial** — robôs ABB, CLPs e manutenção — e estou migrando para **TI com foco em Engenharia de Dados**.

Cursando Tecnólogo em IA na FIAP, construo projetos de Python, SQL e dados, e levo do chão de fábrica o cuidado com confiabilidade, dados de sensores e processos que não podem parar.

---

## 🛠️ Tecnologias & Habilidades

<div align="center">

### Linguagens
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### Data Science & Machine Learning
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6B00?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

### Web
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Dados & IoT
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge)

### Automação Industrial (diferencial)
**Robótica ABB** · **PLCs** (Rockwell, Siemens, Omron) · **Inversores** · **Manutenção preditiva e corretiva**

</div>

---

## 🌟 Projetos em Destaque

### 🔧 Manutenção Preditiva com IA — Previsão de falhas com XGBoost + SHAP
[![CI](https://github.com/DenisPaulo/manutencao-preditiva-ia/actions/workflows/ci.yml/badge.svg)](https://github.com/DenisPaulo/manutencao-preditiva-ia/actions/workflows/ci.yml)

"Com essas leituras dos sensores, a máquina vai falhar? E por quê?" — modelo XGBoost treinado no dataset **AI4I 2020 (UCI)**, com explicação de cada previsão via **SHAP** e painel interativo em Streamlit.

**No teste:** recall **0,824** · precisão **0,757** · F1 **0,789** · PR-AUC **0,884**

**Stack:** Python · XGBoost · SHAP · scikit-learn · Streamlit

**Demo:** [painel no Streamlit](https://manutencao-preditiva-ia-3xvamtyr7vvjvcxdbsdnze.streamlit.app/) · [Repositório](https://github.com/DenisPaulo/manutencao-preditiva-ia)

---

### 🏭 Pipeline de Dados Industriais — ETL com PostgreSQL e Docker
[![CI](https://github.com/DenisPaulo/pipeline-dados-industriais/actions/workflows/ci.yml/badge.svg)](https://github.com/DenisPaulo/pipeline-dados-industriais/actions/workflows/ci.yml)

Pipeline de engenharia de dados para sensores industriais: ingestão do **AI4I 2020** mais leituras simuladas, **Parquet** particionado, limpeza com regras explícitas e carga **idempotente** em **PostgreSQL 16**, tudo reproduzível com **Docker Compose**.

**Resultado real:** 26.271 linhas lidas · 24.511 válidas · 1.760 descartadas · 18 máquinas · 586 falhas

**Stack:** Python · Pandas · Parquet · PostgreSQL · Docker · pytest · GitHub Actions

**Próximos passos:** dbt + qualidade de dados + painel (V2), Airflow + nuvem (V3)

[Repositório](https://github.com/DenisPaulo/pipeline-dados-industriais)

---

### 🌱 FarmTech Solutions — Irrigação Inteligente para Cafeicultura
**FIAP · Fase 2**

Irrigação automática no ESP32 quando solo/pH/NPK ok; suspende se a OpenWeather prevê chuva.

**Stack:** ESP32 (C++) · Python · R + ggplot2 · OpenWeather API

[Repositório](https://github.com/DenisPaulo/fase2-farmtech-irrigacao-cafe) · [Vídeo](https://youtu.be/ZhRJwmskorw)

---

### 🌾 CanaTech — Agricultura Digital (FIAP)
CRUD de talhões com cálculo automático de perda (%) e prejuízo (R$), com persistência em JSON/Oracle.

**Stack:** Python · Oracle

[Repositório](https://github.com/DenisPaulo/CanaTech)

---

### 📊 Python & R Solutions — FarmTech / Agricultura Digital
CRUD de insumos em Python + estatística e clima (Open-Meteo) em R.

[Repositório](https://github.com/DenisPaulo/python-and-r-solutions)

---

### 🎮 Mapadev Week — Arcade VS
Character select arcade com VS Mode, CRT e FIGHT! — HTML/CSS/JS.

**Demo:** [denispaulo.github.io/projeto-mapadev-week](https://denispaulo.github.io/projeto-mapadev-week/) · [Repositório](https://github.com/DenisPaulo/projeto-mapadev-week)

---

### 📋 Fluxo de Caixa — HTML/CSS/JS
Fluxo de caixa + simulação de RDB (juros compostos) — HTML/CSS/JS.

**Demo:** [denispaulo.github.io/fluxo-caixa](https://denispaulo.github.io/fluxo-caixa/) · [Repositório](https://github.com/DenisPaulo/fluxo-caixa)

---

## 💼 Experiência

**Técnico em Manutenção Eletroeletrônica** — Saint-Gobain Sekurit  
*Março 2023 – Presente*

- Manutenção e otimização de robôs ABB
- Programação e diagnóstico de CLPs Rockwell, Siemens e Omron
- Estratégias de manutenção preditiva e corretiva

---

## 🎓 Formação

- **Tecnólogo em Inteligência Artificial** — FIAP São Paulo (Fev 2026 – Dez 2028) — *Em andamento*
- **Análise e Desenvolvimento de Software** — Centro Universitário FAM (Ago 2021 – Dez 2023)
- **Técnico em Eletrotécnica** — Instituto Edson (2014 – 2015)

---

<div align="center">
  <h3>📫 Vamos conversar?</h3>
  <p>Aberto a oportunidades em Engenharia de Dados, IA, Dados, Automação Inteligente e Agrotech</p>

  <a href="https://www.linkedin.com/in/denispaulodiassilva/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</div>

<br>

<div align="center">
  <img src="https://raw.githubusercontent.com/DenisPaulo/DenisPaulo/output/github-contribution-grid-snake.svg" alt="Snake contribution graph"/>
</div>
