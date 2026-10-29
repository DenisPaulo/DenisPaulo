<div align="center">
  <h1>👋 Denis Paulo</h1>
  <h3>Da manutenção industrial (ABB/PLC) para TI &amp; Engenharia de Dados</h3>
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

Cursando Tecnólogo em IA na FIAP, construo projetos de Python, SQL e dados, e levo da indústria o cuidado com confiabilidade, dados de sensores e processos que não podem parar.

Hoje meu foco é uma vaga de **estágio ou júnior em Engenharia de Dados**: pipelines com SQL, dbt, Airflow e Databricks (PySpark + Delta Lake).

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
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8%20(Ultralytics)-00FFFF?style=for-the-badge&logoColor=black)
![ECharts](https://img.shields.io/badge/ECharts-AA344D?style=for-the-badge&logo=apacheecharts&logoColor=white)

### Web
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Engenharia de Dados
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark%20%2F%20PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD4?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)

### Nuvem
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)

### IoT
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge)

### Automação Industrial (diferencial)
**Robótica ABB** · **PLCs** (Rockwell, Siemens, Omron) · **Inversores** · **Manutenção preditiva e corretiva**

</div>

---

## 🌟 Projetos em Destaque

### 🏭 Pipeline de Dados Industriais — do ETL ao Databricks
[![CI](https://github.com/DenisPaulo/pipeline-dados-industriais/actions/workflows/ci.yml/badge.svg)](https://github.com/DenisPaulo/pipeline-dados-industriais/actions/workflows/ci.yml)

Portfólio de engenharia de dados construído em versões, sempre sobre o mesmo domínio: leituras de sensores e falhas de máquinas (**AI4I 2020** + leituras simuladas).

| Versão | Entrega | Status |
|---|---|---|
| **V1** | ETL em Python → **Parquet** particionado → carga **idempotente** em **PostgreSQL 16**, com **Docker Compose** e CI no GitHub Actions | ✅ Feito |
| **V2** | **dbt** em camadas `staging` → `intermediate` → `marts` (modelo estrela) · `dbt build` com **PASS=63** (7 modelos + 56 testes) | ✅ Feito |
| **V3** | Orquestração com **Airflow** (DAG ETL → `dbt build`, alerta de falha) + testes de freshness e volume | ✅ Feito |
| **V4** | **Databricks** com **PySpark** + **Delta Lake**, arquitetura medallion **bronze → silver → gold**, Job `pipeline-industrial` e dashboard **AI/BI** · [repositório](https://github.com/DenisPaulo/pipeline-industrial-databricks) | ✅ Feito |
| **V5** | Nuvem: armazenamento (ADLS ou S3), IAM e custos — primeiros passos em **AWS** (S3, SNS, CloudFormation) na FIAP | 🟡 Em andamento |

**Resultado real:** 26.271 linhas lidas · 24.511 válidas · 1.760 descartadas · 18 máquinas · 586 falhas

<a href="https://github.com/DenisPaulo/pipeline-industrial-databricks">
  <img src="https://raw.githubusercontent.com/DenisPaulo/pipeline-industrial-databricks/main/docs/img/dashboard_databricks.png" alt="Dashboard AI/BI no Databricks sobre as tabelas gold" width="800"/>
</a>

**Stack:** Python · Pandas · SQL · PostgreSQL · dbt · Airflow · Databricks · PySpark · Delta Lake · Docker · pytest · GitHub Actions

[Repositório](https://github.com/DenisPaulo/pipeline-dados-industriais) · [Roadmap](https://github.com/DenisPaulo/pipeline-dados-industriais/blob/main/docs/ROADMAP.md) · [V4 no Databricks](https://github.com/DenisPaulo/pipeline-industrial-databricks)

---

### 🔧 Manutenção Preditiva com IA — Falhas e vida útil remanescente com XGBoost + SHAP
[![CI](https://github.com/DenisPaulo/manutencao-preditiva-ia/actions/workflows/ci.yml/badge.svg)](https://github.com/DenisPaulo/manutencao-preditiva-ia/actions/workflows/ci.yml)

"A máquina vai falhar? Quantos ciclos ela ainda aguenta? E por quê?" — modelos XGBoost com explicação de cada previsão via **SHAP** e painel interativo em Streamlit.

| Versão | Entrega | Resultado no teste |
|---|---|---|
| **V1** | Classificação de falhas no dataset **AI4I 2020 (UCI)** | recall **0,824** · precisão **0,757** · F1 **0,789** · PR-AUC **0,884** |
| **V2** | Previsão de **vida útil remanescente (RUL)** no **NASA C-MAPSS FD001** com `XGBRegressor`, SHAP em ciclos e aba nova no Streamlit | RMSE **11,13 ciclos** · MAE **8,31** · R² **0,923** · NASA Score **176,8** |

**22 testes** automatizados no CI (GitHub Actions).

**Stack:** Python · Pandas · XGBoost · SHAP · scikit-learn · Streamlit · pytest

**Demo:** [painel no Streamlit](https://manutencao-preditiva-ia-3xvamtyr7vvjvcxdbsdnze.streamlit.app/) · [Repositório](https://github.com/DenisPaulo/manutencao-preditiva-ia)

---

### 🌱 FarmTech Solutions (FIAP) — Agricultura digital do sensor à nuvem
**Trabalho em grupo · turma 1TIAOB**

Projeto contínuo do curso, evoluído fase a fase sobre a mesma empresa fictícia de agronegócio.

| Fase | Entrega | Links |
|---|---|---|
| **Fase 2** | Irrigação inteligente para café: ESP32/Wokwi (C++) aciona a bomba conforme solo/pH/NPK e suspende se a OpenWeather prevê chuva; análise em R | [Repositório](https://github.com/DenisPaulo/fase2-farmtech-irrigacao-cafe) · [Vídeo](https://youtu.be/ZhRJwmskorw) |
| **Fase 3** | Banco de dados estruturado em **Oracle/SQL** e CRUD de sensores agrícolas em Python | [Repositório](https://github.com/DenisPaulo/fase3-farmtech-banco-dados) |
| **Fase 4** | Dashboard interativa em **Streamlit** e modelos **Scikit-Learn** para manejo de irrigação e estimativa de produtividade | [Repositório](https://github.com/DenisPaulo/fase4-farmtech-dashboard-ml) |
| **Fase 5** | Arquitetura **AWS** com CloudFormation, IAM de menor privilégio, comparativo de custos (us-east-1 × sa-east-1) e sanitização de telemetria IoT | [Repositório](https://github.com/DenisPaulo/fase5-farmtech-cloud-aws) |
| **Fase 6** | Visão computacional com **YOLOv8** para detecção de ferrugem, broca e maturação no café | [Repositório](https://github.com/DenisPaulo/fase6-farmtech-visao-yolo) |
| **Fase 7** | Consolidação das fases em uma solução integrada | 🔒 Privado |

**Stack:** ESP32 (C++) · Python · R · Oracle · Streamlit · scikit-learn · AWS · YOLOv8

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

## 🔒 Projetos privados (manutenção industrial)

Projetos pessoais sem link público, construídos com **dados simulados**:

- **Pipeline de ordens de serviço em camadas** — arquitetura **bronze → silver → gold** para ordens de serviço de manutenção, com SQL, testes de qualidade e dashboard.
- **Monitor de OS com indicadores de confiabilidade** — indicadores no padrão **ISO 14224 / SMRP**: MTBF, MTTR, disponibilidade, backlog e Pareto de falhas.

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

### Cursos
- **Get Started with Data Engineering** — Databricks Academy (Out 2026) — *Concluído*

---

<div align="center">
  <h3>📫 Vamos conversar?</h3>
  <p>Aberto a oportunidades de estágio ou júnior em Engenharia de Dados</p>

  <a href="https://www.linkedin.com/in/denispaulodiassilva/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</div>

<br>

<div align="center">
  <img src="https://raw.githubusercontent.com/DenisPaulo/DenisPaulo/output/github-contribution-grid-snake.svg" alt="Snake contribution graph"/>
</div>
