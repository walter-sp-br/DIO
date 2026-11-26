# Cronograma Semanal (Semanas 1 a 4)

**Ritmo:** 1 hora por dia durante 30 dias.  
**Objetivo final:** Construir a base de Analytics Engineering e publicar um mini-projeto integrador documentado no GitHub.

---

## Semana 1: SQL Avançado, Modelagem Dimensional e Git/GitHub

- [ ] **Dias 1 a 3 — SQL Avançado**
  - Revisão e prática de CTEs (*Common Table Expressions*).
  - Prática de Window Functions (`ROW_NUMBER`, `RANK`, `LAG`/`LEAD`).
  - Boas práticas de escrita e otimização de consultas.
- [ ] **Dias 4 e 5 — Modelagem Dimensional**
  - Conceitos de tabelas Fato e Dimensão.
  - Comparação entre Star Schema e Snowflake Schema.
  - Definição de granularidade de dados.
- [ ] **Dias 6 e 7 — Versionamento (Git/GitHub)**
  - Configuração do ambiente local.
  - Comandos essenciais do Git (`init`, `add`, `commit`, `branch`, `push`, `pull`).
  - Criação do primeiro repositório dedicado no GitHub (ex.: `jornada-engenharia-dados`).

---

## Semana 2: Transformação de Dados com dbt (Data Build Tool)

- [ ] **Dias 8 e 9 — Fundamentos do dbt**
  - Arquitetura do dbt.
  - Estrutura de pastas de um projeto (`models`, `seeds`, `tests`).
  - Configuração inicial (dbt Core ou dbt Cloud).
- [ ] **Dias 10 a 12 — Modelagem Modular**
  - Criação de camadas de dados (`staging`, `intermediate` e `marts`).
  - Aplicação da modelagem dimensional vista na Semana 1.
  - Uso da função `ref()` para encadear modelos.
- [ ] **Dias 13 e 14 — Qualidade e Documentação**
  - Implementação de testes nativos (`unique`, `not_null`, `accepted_values`, `relationships`).
  - Criação de documentação em arquivos `.yml`.
  - Versionamento do projeto no GitHub.

---

## Semana 3: Python Voltado para Dados

- [ ] **Dias 15 e 16 — Fundamentos e Estruturas**
  - Revisão de sintaxe Python focada em listas, dicionários e funções.
  - Criação e uso de ambientes virtuais (`venv`).
- [ ] **Dias 17 a 19 — Manipulação de Arquivos e Pandas**
  - Leitura, limpeza, tratamento de nulos e tipagem de dados.
  - Trabalho com formatos `CSV`, `JSON` e `Parquet`.
- [ ] **Dias 20 e 21 — Consumo de APIs**
  - Uso da biblioteca `requests` para extrair dados de uma API pública simples.
  - Armazenamento local dos dados extraídos de forma estruturada.

---

## Semana 4: Noções de Data Warehouse, Cloud e Projeto Integrador

- [ ] **Dias 22 e 23 — Arquitetura Cloud e DW**
  - Diferença entre bancos transacionais (`OLTP`) e analíticos (`OLAP`).
  - Conceitos de Data Warehouse, Data Lake e arquitetura moderna de dados (`ELT` vs. `ETL`).
- [ ] **Dias 24 e 25 — Prática na Nuvem**
  - Criação de conta gratuita (Free Tier / Sandbox) no Google BigQuery ou Snowflake.
  - Carregamento de tabelas brutas no ambiente escolhido.
- [ ] **Dias 26 a 30 — Mini-Projeto Final (Portfólio)**
  - Conectar o script Python (extração) → carga no Data Warehouse → transformação e testes com dbt.
  - Publicação final documentada no GitHub (`README`, arquitetura, instruções e resultados).
