Welcome! This portfolio showcases my projects across **data engineering, analytics engineering, and data science**, demonstrating end-to-end workflows, production-ready pipelines, and business-oriented analysis.

---

## **Portfolio Overview**

This collection highlights projects that cover the full data lifecycle:

1. **Raw data ingestion / cleaning**  
2. **Transformation and pipeline optimization**  
3. **Analytics, modeling, and visualization**  
4. **Reporting and downstream usage**  

Each repo includes documentation and workflow examples, highlighting both technical skill and business impact.

---

## **Projects**

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

### 2. [Omega Python Data Cleaning](https://github.com/msfellhauer/Omega_Watches)
**Skills Highlighted:** Python ETL, data cleaning, transformation, reproducible pipelines  
**Summary: This project demonstrates my ability to take messy CSV data, clean and preprocess it using Python and pandas, and produce a polished dataset ready for analysis or external consumption.

This is a data cleaning exercise in Python. The initial data load came from a .csv dataset, imported into Spyder (where the cleaning occurred), then exported to an external stage where the cleaned data could be consumed. The main reason for moving from a raw .csv -> python data frame -> cleaned .csv was purely skill demonstration. this is a relatively small data set, which allowed for this process. I wanted to save the extra step of moving it into a database -> data frame, and just upload it into a data frame because of the size and structure of the data set.

The goal is to take a raw Omega watch dataset and transform it into a clean, analyzable format, including handling missing data, truncating text columns, converting prices to numeric, and creating price tiers.**  
This project demonstrates **data preprocessing and cleanup** in Python for complex datasets, including validation, standardization, and integration. Ideal for preparing raw data for analysis or downstream pipelines.

### 3. [Data Science R Code](https://github.com/msfellhauer/Stragegic-ADRA-Resource-Decisions-in-Private-Lending)
**Skills Highlighted:** R analytics, statistical modeling, data visualization, reproducible research  
**Summary: This is the code base for private lending research. The results were part of my Doctoral Dissertation entitled

STRATEGIC A.D.R.A. RESOURCE DECISIONS IN PRIVATE LENDING: THE ROLE OF ADAPTIVE LEARNING AS MEDIATED BY RISK AND ENTREPRENEURIAL ATTITUDES

The foundational, theoritical, elements were presented at the Academy of Business Research (2015), and the Midwest Academy of Management (2018). The final Dissertation was defended in 2025. This research is the first quantiative test of ADRA logic, and one of the first academic studies in hard money lending. The data was gathered via a survey in available in qualtrics, a population defined in prolific, with the final data set coming through as a .csv file. The data set was cleaned in excel, then imported into R. The rationale behind cleaning in excel was due to the small data sets, that did not require extra coding in R. Further, having developed the survey, I was able to extract the data in a more efficient manner that did not require extensive cleaning (e.g. non-responses were removed from the overall dataset).**  
This repo contains **R-based analytics and modeling workflows**, including exploratory data analysis, regression modeling, and visualization. It shows the ability to extract insights and communicate results clearly.

### 4. [JSON Lateral Flatten](https://github.com/msfellhauer/JSON_Array_Extraction)
**Skills Highlighted:** JSON ingestion, SQL lateral flatten, data transformation  
**Summary: This project demonstrates the transformation of raw JSON data into a structured, production-ready table in Snowflake. The source data originated from nested JSON stored in the Bronze layer of the Snowflake data warehouse. Using SQL and Snowflake-specific features such as LATERAL FLATTEN and type casting, the data was transformed into a clean, flattened format suitable for analytics, reporting, and downstream modeling.**  
This project demonstrates **flattening complex JSON data into relational tables** for analysis. Highlights the ability to handle nested data structures, transform them efficiently, and prepare them for SQL-based analytics or reporting.

---

## **Key Takeaways**

Across these repositories, I demonstrate:  
- **Technical Proficiency:** SQL, Snowflake, Python, R, ETL, JSON processing  
- **Business Awareness:** Efficient pipelines, report-ready tables, stakeholder requirements  
- **Production-Ready Workflows:** Scheduled tasks, clustering, reproducible scripts  
- **End-to-End Understanding:** From raw data to cleaned, transformed, and report-ready outputs  

> Explore the repos to see detailed implementations, workflow designs, and example outputs — all demonstrating production-level thinking and business impact.
