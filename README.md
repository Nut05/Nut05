<div align="center">

# Hi, I'm Nhựt Thanh 👋

### Information Systems Student | Aspiring Data Engineer & BI Developer

Data Warehouse • ETL / ELT Pipelines • Turning raw data into business insights

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=14B8A6&center=true&vCenter=true&width=800&lines=Information+Systems+Student+%40+VNUHCM-US;Aspiring+Data+Engineer+%26+BI+Developer;Building+pipelines+with+dbt%2C+Mage+%26+PostgreSQL;Designing+Data+Warehouses+for+real-world+domains" alt="Typing SVG" />

</div>

---

## About Me

Hi, I'm **Nhựt Thanh**, a final-year **Information Systems** student at **VNUHCM – University of Science**.

I enjoy working on the **data side** of software: collecting data from many sources, modeling it into a **Data Warehouse**, and building **dashboards** that help people make decisions. Through my academic projects, I have worked across the whole BI lifecycle — from defining business questions and KPIs, designing dimensional models, and writing ETL/ELT pipelines, to building semantic models and reports in **Power BI**.

* 🎓 Information Systems student at VNUHCM – University of Science
* 🏗️ Interested in Data Engineering, Data Warehousing, and Business Intelligence
* 🔄 Building ELT pipelines with **Mage.ai**, **dbt**, and **PostgreSQL** on **Docker**
* 🧱 Practicing ETL with **SSIS** and **SQL Server**
* 🕸️ Crawling and standardizing web data with **Python** (Requests, BeautifulSoup)
* 📊 Designing KPIs and dashboards with **Power BI** & **DAX**
* 🚀 Looking for internship / early-career opportunities as a **Data Engineer**, **BI Developer**, or **Data Analyst**

---

## Connect With Me

<div align="center">

<a href="mailto:thanhnguyenttb1@gmail.com">
  <img src="https://img.shields.io/badge/Email-thanhnguyenttb1%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

<a href="https://github.com/Nut05">
  <img src="https://img.shields.io/badge/GitHub-Nut05-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

</div>

---

## Tech Stack

### Languages & Query

<p>
  <img src="https://img.shields.io/badge/SQL-025E8C?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/DAX-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Jinja_(dbt)-B41717?style=for-the-badge&logo=jinja&logoColor=white" />
</p>

### Databases & Data Warehouse

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Microsoft_SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" />
  <img src="https://img.shields.io/badge/Dimensional_Modeling-0F766E?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Star_%2F_Galaxy_Schema-115E59?style=for-the-badge" />
</p>

### Data Engineering (ETL / ELT)

<p>
  <img src="https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white" />
  <img src="https://img.shields.io/badge/Mage.ai-6B4FBB?style=for-the-badge" />
  <img src="https://img.shields.io/badge/SSIS-A91D22?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Web_Scraping-BeautifulSoup-3776AB?style=for-the-badge&logo=python&logoColor=white" />
</p>

### BI & Analytics

<p>
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" />
  <img src="https://img.shields.io/badge/KPI_Design-0EA5E9?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Data_Visualization-2F80ED?style=for-the-badge" />
</p>

### Tools

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" />
  <img src="https://img.shields.io/badge/draw.io-F08705?style=for-the-badge&logo=diagramsdotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" />
</p>

---

## Featured Projects

### 🛒 BI System with Generative AI – Olist E-commerce

An end-to-end **Business Intelligence system** built on the Brazilian **Olist e-commerce** dataset, from raw CSV files to interactive dashboards with AI-generated insights.

```
Kaggle CSV → Mage.ai (Full / Incremental Load) → PostgreSQL staging → dbt → DDS (Galaxy schema) → Power BI
                                                                              └→ AI module ↔ LLM
```

**Role:** Data Modeler & Analytics Engineer  
**Tech Stack:** Mage.ai, dbt, PostgreSQL, Docker, Power BI, DAX

**Key Contributions:**

* Defined **business questions, KPIs, and analysis scope** for each business process
* Wrote the **source-to-target mapping** for all tables in the DDS layer
* Built the full **dbt** project: staging → intermediate → **dimension** and **fact** models, with reusable macros (e.g. city-name normalization)
* Tuned PostgreSQL in Docker so `dbt build` runs reliably on large data
* Designed dashboard layouts and built the **Seller analysis page** in Power BI with DAX measures

**Repository:** 🔒 Private team repository

---

### 🧳 Data Warehouse for the Vietnamese Tourism Domain – Graduation Thesis

A **Data Warehouse** that integrates tour data from major Vietnamese travel companies (Vietravel, Saigontourist, Hanoitourist, Du Lịch Việt, Đất Việt Tour, PYS Travel) to support analysis of the tourism market.

**Role:** Data Analyst & DW Designer  
**Tech Stack:** Python (Requests, BeautifulSoup, openpyxl), SQL, draw.io

**Key Contributions:**

* Crawled and collected tour data from multiple travel websites using **Python**
* Built a **data dictionary** for each source and a **unified attribute matrix** across sources
* Designed the **NDS (Normalized Data Store)** model to integrate heterogeneous sources

**Repository:** 🔒 Private team repository (in progress)

---

### 🔁 ETL with SQL Server Integration Services (SSIS)

Hands-on ETL packages built with **SSIS** to extract, clean, and load data into a **SQL Server** data warehouse.

**Tech Stack:** SSIS, SQL Server, Visual Studio

---

## GitHub Activity

<div align="center">

<img src="https://streak-stats.demolab.com?user=Nut05&hide_border=true&ring=14B8A6&fire=14B8A6&currStreakLabel=14B8A6" alt="GitHub Streak" />

<br /><br />

<img src="https://ghchart.rshah.org/14B8A6/Nut05" alt="Contribution chart" width="100%" />

</div>

---

<div align="center">

### Thanks for stopping by ✨

I'm always happy to learn, collaborate, and talk about data engineering, data warehousing, and BI.

</div>
