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

<img width="1536" height="1024" alt="ChatGPT Image 2 de abr  de 2026, 23_47_16" src="https://github.com/user-attachments/assets/7b232d7f-e797-4044-abb8-de630bbf56a4" />


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
<img width="1024" height="1536" alt="book" src="https://github.com/user-attachments/assets/c474c194-bfa3-41db-8d10-a92d72bbfccd" />
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

