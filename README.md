# Customer Shopping Analysis: End-to-End Data Pipeline

## 🛒 Project Overview
This project performs a comprehensive analysis of customer shopping behavior using a dataset of 3,900 transactions. It demonstrates a full end-to-end data workflow—from initial data cleaning and feature engineering in **Python**, to structured data management in **SQL**, and finally, interactive storytelling in **Power BI**. The goal is to identify spending patterns, segment customers, and provide actionable business recommendations.

## 📊 Key Insights & Metrics
* [cite_start]**Demographic Revenue:** Identified **Young Adults** as the leading revenue contributors, generating over **$62,143** in total sales[cite: 93, 94].
* [cite_start]**Subscription Value:** Analyzed 1,053 subscribers who maintain a consistent average spend of **$59.49**, highlighting the stability of subscription-based revenue[cite: 83].
* [cite_start]**Shipping Behavior:** Discovered that **Express Shipping** users have a higher average purchase amount (**$60.48**) compared to Standard shipping users (**$58.46**)[cite: 80].
* [cite_start]**Customer Segmentation:** Successfully classified the database into **Loyal (3,116)**, **Returning (701)**, and **New (83)** segments to assist in targeted marketing efforts[cite: 87].
* [cite_start]**Category Dominance:** Found that the **Clothing** category leads in both sales volume and revenue, with **Blouses** and **Pants** being the top-performing items[cite: 18, 90].

## 🛠️ Technical Toolkit
* [cite_start]**Python (Pandas/NumPy):** Used for data cleaning, handling missing values in review ratings via median imputation, and feature engineering (age binning)[cite: 15, 20, 22].
* [cite_start]**SQL (MySQL/PostgreSQL):** Performed structured querying for customer segmentation, revenue calculation by gender, and ranking products within categories[cite: 27, 29, 30].
* [cite_start]**Power BI:** Developed an interactive dashboard to visualize key performance indicators (KPIs), sales by category, and demographic trends[cite: 96, 119].

## 🖥️ Project Workflow
1. [cite_start]**ETL Process:** Cleaned raw data in Python and standardized columns for database compatibility[cite: 15, 21].
2. [cite_start]**Database Integration:** Connected Python to SQL to store and query processed data efficiently[cite: 27].
3. [cite_start]**Exploratory Data Analysis:** Conducted deep-dive analysis on discount impacts, shipping types, and subscription statuses[cite: 14, 28].
4. [cite_start]**Visualization:** Built a multi-page Power BI report to present findings to stakeholders[cite: 95, 143].

## 📂 How to Run
1. Clone the repository and install requirements: `pip install pandas sqlalchemy psycopg2`.
2. Run the Python scripts to clean and load data into your SQL environment.
3. Open the `.pbix` file in Power BI to explore the interactive dashboard.

---
**Project by [Shreyas Seshadri]** *Connect with me on [LinkedIn](https://www.linkedin.com/in/shresesh/)*
