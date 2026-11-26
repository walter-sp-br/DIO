# Recursos e Materiais por Semana

Curadoria de referências gratuitas e diretas ao ponto para apoiar os blocos de 1 hora diária.

---

## 📌 Contexto e Alinhamento Inicial

- **Documento "Transição" (Google Drive / pasta local `Transição.docx`):** Utilize-o como guia mestre de alinhamento, pois ele mapeia os 5 pilares que conectam seu background de Análise de Dados ao mercado de Engenharia.
- **Conta do GitHub:** Você já possui acesso configurado na plataforma. Crie um repositório dedicado (ex.: `jornada-engenharia-dados`) para versionar os exercícios e entregas semanais.

---

## Semana 1 — SQL Avançado, Modelagem Dimensional e Git/GitHub

- **SQL:**
  - **Mode SQL Tutorial:** seções *Intermediate* e *Advanced* (foco em CTEs e Window Functions como `ROW_NUMBER`, `RANK`, `LAG`/`LEAD`).
  - **SQLBolt:** prática interativa de consultas e agregações.
- **Modelagem Dimensional:**
  - **The Data Warehouse Toolkit (Ralph Kimball):** resumos sobre tabelas Fato e Dimensão, granularidade e Star Schema vs. Snowflake Schema.
- **Git / GitHub:**
  - **GitHub Docs:** guia *Hello World* e *Git Cheat Sheet* oficial para comandos essenciais (`init`, `add`, `commit`, `branch`, `push`, `pull`).

---

## Semana 2 — Transformação de Dados com dbt (Data Build Tool)

- **Curso Oficial Gratuito:**
  - **dbt Fundamentals (plataforma dbt Learn):** ideal para acompanhar em blocos de 1 hora usando o **dbt Cloud** gratuito.
- **Referência Técnica:**
  - **Documentação oficial do dbt:** seção *Best Practices* para estruturação de projetos (`staging`, `intermediate`, `marts`), uso de `ref()`, testes nativos e documentação em `.yml`.

---

## Semana 3 — Python Voltado para Dados

- **Fundamentos e Pandas:**
  - **Kaggle Learn:** módulos **Python** e **Pandas** (lições curtas e interativas adequadas ao ritmo de 1h/dia).
- **APIs e Extração:**
  - **Documentação da biblioteca `requests`:** requisições HTTP em Python e tratamento de respostas JSON.
  - **APIs públicas gratuitas para prática:** ex. **BrasilAPI** ou **ViaCEP** para extrair e salvar dados localmente de forma estruturada (`CSV`, `JSON`, `Parquet`).

---

## Semana 4 — Data Warehouse, Cloud e Projeto Integrador

- **Ambiente Prático na Nuvem:**
  - **Google Cloud BigQuery Sandbox:** permite criar projetos e usar o BigQuery gratuitamente sem necessidade de cadastrar cartão de crédito (alternativa citada no plano: Free Tier do Snowflake).
- **Conceitos e Arquitetura:**
  - **Documentação introdutória do BigQuery** (conceitos de datasets, tabelas e carregamento de dados brutos).
  - **Guia de arquitetura Modern Data Stack (dbt Labs):** referência para consolidar conceitos de OLTP vs. OLAP, Data Warehouse, Data Lake e ELT vs. ETL no mini-projeto final.
