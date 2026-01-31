Welcome! This portfolio showcases my projects across **data engineering, analytics engineering, and data science**, demonstrating end-to-end workflows, production-ready pipelines, and business-oriented analysis.

---

## Portfolio Overview

This collection highlights projects that cover the **full data lifecycle**:

- Raw data ingestion / cleaning  
- Transformation and pipeline optimization  
- Analytics, modeling, and visualization  
- Reporting and downstream usage  

Each repo includes documentation and workflow examples, highlighting both technical skill and business impact.

---

## Projects

### 1. [Snowflake Daily Update Demo](https://github.com/msfellhauer/Snowflake-Workflow-Creation)
**Skills Highlighted:** SQL & Snowflake, ETL pipeline design, task scheduling, performance optimization  

**Summary:**  
This repo demonstrates a **production-oriented workflow** for updating a Snowflake table daily.  

- Pre-joins two tables with a `LEFT JOIN` and filters by the previous day  
- Uses clustering to reduce runtime (~40% improvement)  
- Scheduled with a Snowflake task to refresh daily at 6:00 AM PST  
- Designed to feed SSRS reports filtered by `funding_date`  
- Materialized views weren’t used due to join limitations  

This repo shows how to **optimize large datasets while maintaining report stability**.

---

### 2. [Omega Python Data Cleaning](https://github.com/msfellhauer/Omega_Watches)
**Skills Highlighted:** Python ETL, data cleaning, transformation, reproducible pipelines  

**Summary:**  
This project demonstrates my ability to take **messy CSV data**, clean and preprocess it using Python and pandas, and produce a polished dataset ready for analysis or external consumption.  

- The initial data load came from a CSV dataset, imported into Spyder for cleaning, then exported to an external stage.  
- Cleaning included handling missing data, truncating text columns, converting prices to numeric, and creating price tiers.  
- The process was designed as a **skill demonstration** for Python-based ETL on a manageable dataset.  

This repo shows **data preprocessing and cleanup for complex datasets**, including validation, standardization, and integration.

---

### 3. [Data Science R Code](https://github.com/msfellhauer/Stragegic-ADRA-Resource-Decisions-in-Private-Lending)
**Skills Highlighted:** R analytics, statistical modeling, data visualization, reproducible research  

**Summary:**  
This repo contains the code base for **private lending research**, part of my Doctoral Dissertation:

> *STRATEGIC A.D.R.A. RESOURCE DECISIONS IN PRIVATE LENDING: THE ROLE OF ADAPTIVE LEARNING AS MEDIATED BY RISK AND ENTREPRENEURIAL ATTITUDES*  

- Foundational elements presented at the Academy of Business Research (2015) and Midwest Academy of Management (2018); Dissertation defended in 2025  
- Data gathered via Qualtrics survey and Prolific population, exported as CSV  
- Data cleaning was done in Excel due to small dataset size and pre-cleaned survey responses  

This repo demonstrates **exploratory data analysis, regression modeling, and visualization** in R, with a focus on extracting insights and communicating results clearly.

---

### 4. [JSON Lateral Flatten](https://github.com/msfellhauer/JSON_Array_Extraction)
**Skills Highlighted:** JSON ingestion, SQL lateral flatten, data transformation  

**Summary:**  
This project demonstrates the transformation of **raw JSON data** into a structured, production-ready table in Snowflake.  

- Source data came from nested JSON in the Bronze layer of the Snowflake data warehouse  
- SQL features like `LATERAL FLATTEN` and type casting were used to produce a clean, flattened dataset  
- Output suitable for analytics, reporting, and downstream modeling  

This repo highlights the ability to **handle nested data structures, transform them efficiently, and prepare them for SQL-based analytics or reporting**.

---

## Key Takeaways

Across these repositories, I demonstrate:  

- **Technical Proficiency:** SQL, Snowflake, Python, R, ETL, JSON processing  
- **Business Awareness:** Efficient pipelines, report-ready tables, stakeholder requirements  
- **Production-Ready Workflows:** Scheduled tasks, clustering, reproducible scripts  
- **End-to-End Understanding:** From raw data to cleaned, transformed, and report-ready outputs  

> Explore the repos to see detailed implementations, workflow designs, and example outputs — all demonstrating production-level thinking and business impact.

