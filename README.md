# projeto_feminicídio
Pipeline de dados sobre feminicídio com Python, MySQL e Power BI

# 🔴 Projeto de Dados: Feminicídio em Dados

<p align="center">
  <img src="https://img.shields.io/badge/status-em%20desenvolvimento-red">
  <img src="https://img.shields.io/badge/python-3.10+-black">
  <img src="https://img.shields.io/badge/mysql-database-red">
  <img src="https://img.shields.io/badge/powerbi-dashboard-black">
  <img src="https://img.shields.io/badge/license-MIT-red">
</p>

---

## 📊 Visão Geral

Este projeto foi desenvolvido com o objetivo de construir um pipeline completo de dados para análise de feminicídio, transformando dados públicos em insights estratégicos para apoio à tomada de decisão.

---

## 🎯 Objetivo

✔ Criar pipeline end-to-end
✔ Estruturar dados em modelo dimensional
✔ Disponibilizar dados para BI
✔ Gerar insights sociais relevantes

---

## 🧱 Arquitetura

```mermaid
flowchart LR
    A[API JSON] --> B[ETL Python]
    B --> C[MySQL DW]
    C --> D[Power BI]
```

---

## 🗂️ Estrutura do Projeto

```bash
projeto_feminicidio/
│
├── data/
├── scripts/
│   ├── extract.py
│   ├── transform.py
│   ├── load.py
│
├── sql/
│   └── create_tables.sql
│
├── dashboard/
├── notebooks/
└── README.md
```

---

## ⚙️ Stack Tecnológica

| Camada        | Tecnologia        |
| ------------- | ----------------- |
| Ingestão      | Python (Requests) |
| Processamento | Pandas            |
| Banco         | MySQL             |
| BI            | Power BI          |

---

## 🔄 Pipeline de Dados

* 📥 Extração via API pública (JSON)
* 🔧 Transformação e limpeza dos dados
* 🧱 Modelagem dimensional (Star Schema)
* 💾 Carga em Data Warehouse (MySQL)
* 📊 Visualização em Power BI

---

## 🧠 Modelagem

**Fato:**

* fato_feminicidio → quantidade de casos

**Dimensões:**

* dim_tempo
* dim_local
* dim_vitima

---

## 📊 Dashboard

### Principais análises:

* Evolução temporal dos casos
* Distribuição por estado
* Perfil das vítimas
* Comparativo entre períodos

---

## 📸 Preview do Dashboard

<p align="center">
  <img src="docs/dashboard.png" width="700">
</p>

---



---

## 👨‍💻 Autor

**Kleber Marques**
Analista de Dados Jr.

---

## ❤️ Impacto

Este projeto demonstra como dados podem apoiar decisões para reduzir a violência contra a mulher.

> ✊ Não ao feminicídio

