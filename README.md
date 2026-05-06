*Read this in [English](README_en.md).*

# Olá, eu sou o Marcus 👋

### 📊 Data Engineering | Data Science | Geospatial Intelligence

Sou um profissional de dados focado em construir soluções de ponta a ponta, unindo a modelagem analítica com o desenvolvimento de software. 

Minha carreira é construída sobre uma fundação dupla e versátil: possuo profunda expertise em **Inteligência Geoespacial e Sensoriamento Remoto**, atuando lado a lado com a arquitetura de **Ciência de Dados "Pura" e Engenharia de Machine Learning**. 

Meu objetivo é transformar dados complexos — sejam eles matrizes de pixels ou bancos de dados relacionais corporativos — em produtos de software escaláveis e inteligência de negócio. Posso atuar tanto na criação de infraestruturas tradicionais de dados quanto em desafios de alta complexidade espacial.

---

### 🛠️ Áreas de Atuação & Stack Tecnológico

Para navegar entre esses dois mundos, divido minha stack da seguinte forma:

#### 🧠 Data Science, MLOps & Engenharia de Dados
Desenvolvimento de pipelines, inteligência artificial e deploy de aplicações.
* **Linguagens & Web:** Python, SQL, Streamlit, FastAPI.
* **Machine Learning:** Scikit-Learn, Pandas, Numpy, Criação e Operação de Pipelines Preditivos.
* **Engenharia & LLMOps:** Docker, PostgreSQL, RAG Systems, Bancos Vetoriais (ChromaDB), Integração de APIs (Groq/Meta, Google).

#### 🌍 Inteligência Geoespacial & Remote Sensing
Análise espacial, processamento de imagens e automação GIS.
* **Geotecnologias:** QGIS, GDAL/OGR, PostGIS, ArcGIS.
* **Sensoriamento Remoto:** Fusão de dados ópticos e SAR, cálculo de índices biofísicos, monitoramento e modelagem ambiental.
* **Automação:** Desenvolvimento de plugins em Python para QGIS, processamento em lote.

---

### 🚀 Projetos em Destaque

#### 🛰️ [Spatial Agentic RAG (Orquestração Multi-Agente & GIS)](https://github.com/MarcusBarrozo1/spatial-agentic-api)
*Um pipeline de orquestração Agentic AI para automatizar análises de risco de crédito agrícola.*
*   **O que é:** Um ecossistema de microsserviços onde um LLM atua como orquestrador (Máquina de Estado), raciocinando sobre as demandas do usuário e acionando autonomamente pipelines de Visão Computacional geoespacial. O Agente toma decisões e dispara requisições POST para segmentar talhões e calcular saúde vegetativa (NDVI).
*   **Stack:** Python, LangGraph (StateGraph/Tool Calling), FastAPI, Docker, Groq API (Llama 3), U-Net (Keras), Rasterio/NumPy.
*   **Impacto:** Demonstra forte capacidade em MLOps e Engenharia de Software: treinamento de redes neurais do zero (U-Net para segmentação multiespectral), conteinerização de APIs para inferência (FastAPI/Docker) e roteamento não-linear de agentes de IA para eliminar gargalos de operação manual no setor AgTech.

#### 🤖 [Multi-Cloud RAG Assistant (Domínio AgTech)](https://github.com/MarcusBarrozo1/geo_rag_assistant)
*Um ecossistema de LLMOps rodando localmente e na nuvem.*
* **O que é:** Um microsserviço de Inteligência Artificial Generativa construído do zero. Ele atua como um assistente que cruza telemetria SQL em tempo real com busca vetorial de documentos densos.
* **Stack:** Python, Docker, PostgreSQL, ChromaDB, HuggingFace Embeddings, Groq API (Llama 3), Streamlit.
* **Impacto:** Demonstra capacidade de arquitetar sistemas RAG resilientes (com fallback de APIs), ingestão de dados e criação de interfaces interativas para o usuário final.

#### 📈 [Pipeline de Machine Learning & Classificação Preditiva](https://github.com/MarcusBarrozo1/portfolio_agtech_iot) - [Repo-2](https://github.com/MarcusBarrozo1/portfolio_ml_agtech).
*Modelagem preditiva.*
* **O que é:** Pipeline de tratamento de dados (Data Wrangling) e treinamento de modelos de classificação utilizando algoritmos clássicos (Random Forest, etc).
* **Stack:** Pandas, Scikit-Learn, Matplotlib/Seaborn.
* **Impacto:** Foco na limpeza de dados reais, feature engineering e validação rigorosa de modelos através de métricas de negócio.

#### 🗺️ [Geospatial Automation - MVP & Roadmap Arch](https://github.com/MarcusBarrozo1/meca-qgis-plugin)
*Engenharia de Software e Data Science aplicadas à gestão de recursos hídricos.*
*   **O que é:** Um Produto Mínimo Viável (MVP) em Python/QGIS que traduziu o algoritmo científico SAFER (originalmente em R) para estimar o consumo hídrico agrícola via balanço de energia.
*   **Visão de Engenharia & Roadmap:** Este repositório foca não apenas no código legado, mas na capacidade de auditar processos e desenhar arquiteturas escaláveis. O roadmap de refatoração documentado inclui:
    *   Desacoplamento do processamento visual (QGIS/PyQt) para rotinas vetorizadas puras em memória RAM via `NumPy`.
    *   Transição para o paradigma *Cloud-Native Geospatial* (STAC/COGs), eliminando o download de cenas orbitais.
    *   Governança Territorial: Construção de pipelines de cruzamento relacional espacial (*Spatial Join*) entre modelos de Visão Computacional (Crop Boundary) e bases fundiárias jurídicas (CAR).
*   **Impacto:** Demonstra forte maturidade técnica para herdar lógicas científicas complexas, identificar gargalos estruturais (como I/O de disco) e arquitetar a migração para infraestruturas de dados modernas e autônomas.

---

### 📬 Sempre aberto a discutir arquitetura de dados, novos paradigmas de ML e como a inteligência espacial pode alavancar produtos tradicionais.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marcus-barrozo-092236301/)
[![E-mail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:barrozo.marcus1@gmail.com)
