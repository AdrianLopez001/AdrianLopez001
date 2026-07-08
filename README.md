# Olá, eu sou o Adrian Lopes! 👋 / Hello, I'm Adrian Lopes! 🇧🇷 🇺🇸

<div align="center">
  <img src="https://img.shields.io/badge/Status-Open%20To%20Work-green?style=for-the-badge&logo=github" alt="Open To Work"/>
  <img src="https://img.shields.io/badge/Contact-adrianlopes.dev%40gmail.com-blue?style=for-the-badge&logo=gmail" alt="Email"/>
</div>

---

## 🇧🇷 Versão em Português

Desenvolvedor de Software focado na construção de sistemas robustos, escaláveis e integrados com Inteligência Artificial. Atualmente cursando **Análise e Desenvolvimento de Sistemas (ADS)**, busco alinhar rigor técnico de Engenharia de Software com soluções de valor para o negócio. Estou ativamente em busca de oportunidades como **Desenvolvedor Backend (Java/Python) ou Full-Stack**.

### 💻 Minhas Especialidades & Foco Técnico
*   **Backend de Alta Performance:** APIs RESTful bem estruturadas, arquitetura de microsserviços, mensageria assíncrona e persistência relacional.
*   **Inteligência Artificial e RAG:** Pipelines de preparação de dados, busca semântica corporativa (RAG), embeddings e explicabilidade de modelos de Machine Learning (SHAP values).
*   **Frontend Moderno:** Dashboards interativos e responsivos com foco em performance e boas práticas de UX.

---

## 🇺🇸 English Version

Software Developer focused on building robust, scalable systems integrated with Artificial Intelligence. Currently studying **Systems Analysis and Development (ADS)**, I aim to combine Software Engineering technical rigor with business value solutions. I am actively looking for opportunities as a **Backend (Java/Python) or Full-Stack Developer**.

### 💻 Technical Focus & Specialties
*   **High-Performance Backend:** Well-structured RESTful APIs, microservices architecture, asynchronous messaging, and relational databases.
*   **AI & RAG:** Data prep pipelines, corporate semantic search (RAG), text embeddings, and ML model explainability (SHAP values).
*   **Modern Frontend:** Interactive and responsive dashboards focusing on performance and UX best practices.

---

## 🛠️ Toolbox / Tecnologias

<div align="center">

| Categoria / Category | Tecnologias / Technologies |
| :--- | :--- |
| **Backend & APIs** | ![Java](https://img.shields.io/badge/Java_17+-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6db33f?style=flat-square&logo=springboot&logoColor=white) ![Spring Security](https://img.shields.io/badge/Spring_Security-6db33f?style=flat-square&logo=springsecurity&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) |
| **Data & AI** | ![Python](https://img.shields.io/badge/Python_3.9+-3776AB?style=flat-square&logo=python&logoColor=white) ![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-1E88E5?style=flat-square&logo=xgboost&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) |
| **Frontend** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Next.js 15](https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) |
| **Bancos & Filas / DBs & Queues** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![H2 Database](https://img.shields.io/badge/H2-Database-blue?style=flat-square) ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white) |
| **DevOps & CI/CD** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) |

</div>

---

## 🚀 Projetos em Destaque / Featured Projects

### ⚽ [Now or Never — MatchMind AI](https://github.com/AdrianLopez001/Now-or-Never)
Plataforma de inteligência preditiva para partidas de futebol com geração de probabilidades calibradas e explicabilidade por SHAP values.
*   **Backend:** Spring Boot (Java 17+) controlando a persistência (H2) e orquestrando o pipeline de ML via invocação assíncrona.
*   **Pipeline de ML:** Python executando ensemble de modelos (`RandomForest`, `LogisticRegression`, `GradientBoosting`), engenharia de features dinâmicas a partir de classificações oficiais e geração de explicações textuais (PT-BR) baseadas nos impactos SHAP das variáveis de cada time. Inclui rate limit inteligente de 10 req/min com auto-retry.
*   **Frontend:** Dashboard dinâmico em Next.js 15 renderizando probabilidades de 9 mercados diferentes por jogo e gráficos analíticos.

### 🧠 [Corporate RAG Engine](https://github.com/AdrianLopez001/Corporate-RAG-Engine)
[![CI](https://github.com/AdrianLopez001/Corporate-RAG-Engine/actions/workflows/ci.yml/badge.svg)](https://github.com/AdrianLopez001/Corporate-RAG-Engine/actions/workflows/ci.yml)
Mecanismo de busca semântica empresarial utilizando técnica de Geração Aumentada por Recuperação (RAG).
*   Desenvolvido em Java/Spring Boot com indexação e recuperação inteligente de documentos técnicos em banco de dados vetorial (`pgvector` / PostgreSQL).
*   Utiliza Spring AI para integração flexível com embeddings de texto e modelos de linguagem OpenAI (GPT-4o-mini).
*   *Testes automatizados integrados com mockito e carregamento de contexto mockado.*

### 🏥 [CareSync](https://github.com/AdrianLopez001/CareSync)
[![CI](https://github.com/AdrianLopez001/CareSync/actions/workflows/ci.yml/badge.svg)](https://github.com/AdrianLopez001/CareSync/actions/workflows/ci.yml)
Plataforma moderna de gestão médica integrada que simplifica a ponte entre equipes clínicas e pacientes através de microsserviços orientados a eventos.
*   **Arquitetura:** Microsserviços independentes (`appointment-service` e `notification-service`) comunicando-se assincronamente via **RabbitMQ** (Topic Exchange).
*   **Segurança & Validação:** Persistência em base PostgreSQL com consistência transacional garantindo publicação pós-commit de transação.
*   *Possui cobertura de testes unitários de regras de negócio (JUnit 5/Mockito) e testes de API web (MockMvc) integrados no pipeline CI.*

### 💰 [FINTRACK-SYSTEM](https://github.com/AdrianLopez001/FINTRACK-SYSTEM)
Sistema backend em Python para auditoria e controle financeiro pessoal/empresarial.
*   Foco em integridade de dados financeiros, processamento de extratos e categorização inteligente de transações para geração de relatórios fiscais e orçamentários.

---

## 📊 Estatísticas do GitHub / GitHub Stats

<div align="center">
  <img height="180em" src="https://github-stats-extended.vercel.app/api?username=AdrianLopez001&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-stats-extended.vercel.app/api/top-langs/?username=AdrianLopez001&layout=compact&langs_count=7&theme=tokyonight"/>
</div>

---

## 📫 Conecte-se Comigo / Get in Touch

*   **Email:** [adrianlopes.dev@gmail.com](mailto:adrianlopes.dev@gmail.com) 📧
*   **LinkedIn:** [adrian-lopes-a42699371](https://www.linkedin.com/in/adrian-lopes-a42699371) 💼
*   **GitHub:** [AdrianLopez001](https://github.com/AdrianLopez001) 💻
*   **Localização / Location:** Natal, RN - Brasil 🇧🇷 (Disponível para vagas Home Office globais e nacionais / Open for global and national remote opportunities)
