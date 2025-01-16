# AtliQ Mart Campaign Analysis Project

## Project Overview
AtliQ Mart is a retail giant with over 50 supermarkets located in the southern region of India. During the Diwali 2023 and Sankranti 2024 festive seasons, all stores launched a massive promotion on AtliQ branded products. The sales director, Bruce Haryali, wanted to evaluate the success of these promotions to inform future promotional strategies.

This project aims to provide actionable insights into the performance of various promotions, highlighting what worked well and what didn’t.

---

## File Structure

### 1. **Dashboard**
   - Contains the project dashboard created in **Power BI**.
   - Formats:
     - `.pbix` (Power BI file)
     - `.pdf` (Dashboard exported as a PDF for easy sharing).

### 2. **Database**
   - This folder includes the raw data used for the analysis:
     - `dim_campaigns.csv` – Campaign details.
     - `dim_stores.csv` – Store metadata.
     - `dim_products.csv` – Product details.
     - `fact_events.csv` – Fact table with sales and event data.
     - `retail_events_db.sql` – SQL dump for database creation.

### 3. **Images**
   - Contains visual outputs:
     - SQL query results.
     - Graphs and KPIs.
     - Screenshots of the Power BI dashboard.

### 4. **Project Documents**
   - Documents related to the project:
     - Problem statement.
     - Metadata descriptions.
     - Recommended insights based on the analysis.
     - Ad-hoc-requests sql queries.
     - How to get started - a step by step guide.
     - Project Details.

### 5. **SQL**
   - SQL scripts used in the project:
     - `retail_events_db.sql` – Database setup script.
     - `Script1.sql` – Ad-hoc SQL queries for answering specific business questions.
     - `Script1.pdf` - For better readability of the sql file.

---

## Key Components

### Problem Statement
The goal of the project is to analyze the performance of AtliQ Mart’s festive promotions to:
- Identify campaigns that succeeded.
- Determine campaigns that underperformed.
- Provide actionable recommendations for future promotional strategies.

### Methodology
1. **Data Exploration and Cleaning**:
   - Examined datasets for completeness and consistency.
   - Prepared data for analysis by loading into a relational database.

2. **SQL Queries**:
   - Wrote ad-hoc queries to answer specific business questions.
   - Extracted insights and key metrics from the `retail_events_db` database.

3. **Visualization in Power BI**:
   - Created an interactive dashboard to display KPIs, trends, and insights.

4. **Insights and Recommendations**:
   - Generated actionable insights based on data analysis.
   - Documented insights in the Project Documents folder.

### Tools Used
- **Power BI**: For creating the dashboard.
- **SQL**: For querying and analyzing the data.
- **CSV**: Data storage and preprocessing.
- **Microsoft Excel**: For data exploration.

---

## Dashboard Overview
The dashboard includes:
- **Key Metrics**: Sales, ROI, and campaign performance.
- **Comparative Analysis**: Performance of Diwali vs Sankranti campaigns.
- **Visuals**: Bar charts, line graphs, and KPIs for easy interpretation.
- **Filters**: Dynamic filters for stores, campaigns, and product categories.

---

## How to Use This Repository
1. **Setup the Database**:
   - Use `retail_events_db.sql` to create the database.
   - Load the CSV files into the respective tables.

2. **Run SQL Queries**:
   - Use `Script1.sql` or `Script1.pdf` for ad-hoc queries and insights.

3. **Explore the Dashboard**:
   - Open the `.pbix` file in Power BI to interact with the dashboard.
   - View the static dashboard in the `.pdf` file.

---

## Contact
For questions or feedback regarding this project, feel free to reach out:

* Email: [skjaveriya.11@gmail.com]
* LinkedIn: [www.linkedin.com/in/javeriya-shaikh-57869a231]
* GitHub: [https://github.com/Shaikh-Javeriya]


---
