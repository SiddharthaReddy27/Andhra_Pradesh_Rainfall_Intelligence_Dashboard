# 🌧️ Andhra Pradesh Rainfall Intelligence Dashboard

An end-to-end Business Intelligence project that transforms district-wise rainfall data into actionable insights using **Python, SQLite, SQL, and Power BI**. The project covers the complete analytics workflow from data preprocessing and database design to advanced SQL analysis and interactive dashboard development.

---

## 📌 Project Overview

This project analyzes **23,478+ district-wise rainfall records (2021–2025)** for Andhra Pradesh to uncover rainfall trends, district performance, seasonal variations, and extreme rainfall events.

The workflow includes:

- Data Cleaning & Feature Engineering using Python (Pandas & NumPy)
- Star Schema Design using SQLite
- Advanced SQL Analytics
- Interactive Power BI Dashboard
- Business Intelligence & Data Storytelling


---

# 🏗️ Project Architecture

```text
                 Raw Rainfall Data (2021–2025)
                           │
                           ▼
        Python (Pandas & NumPy - Data Cleaning & Transformation)
                           │
                           ▼
             SQLite Database (Star Schema Design)
                           │
                           ▼
          Advanced SQL Analytics (30+ SQL Queries)
                           │
                           ▼
        Power BI Dashboard (DAX, KPIs & Visualizations)
                           │
                           ▼
             Business Insights & Decision Support
```

---

# 📊 Dashboard Preview

## Executive Overview

![Overview](Dashboard/Screenshots/Overview.png)

---

## District Analysis

![District Analysis](Dashboard/Screenshots/District_Analysis.png)

---

## Temporal Analysis

![Temporal Analysis](Dashboard/Screenshots/Temporal_Analysis.png)

---

# 🗄️ Data Model

The project follows a **Star Schema** data model to support efficient analytical querying and reporting.

### Fact Table
- **rainfall_fact** – Stores rainfall measurements and links to dimension tables.

### Dimension Tables
- **date_dim** – Date, Month, Quarter, Year
- **district_dim** – District information

### Data Model

![Power BI Data Model](Dashboard/Screenshots/PowerBI_Data_Model.png)

The star schema minimizes data redundancy, improves query performance, and provides a scalable foundation for Power BI reporting.

---

## Insights & Extremes

![Insights & Extremes](Dashboard/Screenshots/Insights_and_Extremes.png)


---

# 📂 Project Structure

```text
Andhra_Pradesh_Rainfall_Intelligence_Dashboard
│
├── Data
│   ├── Raw_Data
│   ├── Processed_Data
│   └── Analytics_Output
│
├── Notebooks
│   └── Rainfall_Analytics.ipynb
│
├── Dashboard
│   ├── AP_Rainfall_Intelligence_Dashboard.pbix
│   ├── Dashboard.pdf
│   └── Screenshots
│
├── README.md
├── LICENSE
└── requirements.txt
```

---

# 🛠️ Technologies Used

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Data Processing | Pandas, NumPy |
| Database | SQLite |
| Query Language | SQL |
| Notebook Environment | Jupyter Notebook |
| Business Intelligence | Power BI |
| Data Modeling | Star Schema |
| Analytics | DAX, KPI Design |
| Visualization | Power BI Visuals |
| Version Control | Git & GitHub |


---

# ⭐ Project Features

- ✅ Cleaned and transformed **23,478+ district-wise rainfall records (2021–2025)** using Python.
- ✅ Designed an optimized **Star Schema** with fact and dimension tables in SQLite.
- ✅ Developed **30+ advanced SQL queries** using joins, CTEs, window functions, subqueries, and aggregations.
- ✅ Built an interactive **4-page Power BI dashboard** with DAX measures, KPI cards, synchronized slicers, and analytical visualizations.
- ✅ Performed district-wise, temporal, and extreme rainfall analysis to generate actionable business insights.
