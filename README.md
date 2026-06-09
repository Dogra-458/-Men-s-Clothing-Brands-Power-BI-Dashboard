# 👕 Men's Clothing Brands — Power BI Dashboard

An end-to-end data analytics project that explores pricing trends, brand comparisons, and discount insights across **144 Men's T-Shirt brands** — built using **Azure SQL**, **Power BI**, **Excel**, and **SQL**.

---

## 📊 Project Overview

This project analyzes a dataset of **1,444 men's T-shirt listings** scraped from e-commerce platforms. The data was loaded into **Azure SQL Database**, queried and transformed using **SQL**, and visualized through an interactive **Power BI** dashboard. The goal is to uncover pricing patterns, discount rates, and brand performance across a wide range of clothing labels — from budget-friendly Indian brands to premium international names.

---

## 🗂️ Dataset

**File:** `Men_Tshirt.csv`

| Column | Description |
|---|---|
| `Brand` | Name of the clothing brand |
| `Title` | Product title / name of the T-shirt |
| `Original Price` | MRP / listed price (INR ₹) |
| `Sale Price` | Discounted / selling price (INR ₹) |

- **Total Records:** 1,444
- **Unique Brands:** 144
- **Sample Brands:** Louis Philippe, Tommy Hilfiger, Levi's, H&M, Allen Solly, Jack & Jones, U.S. Polo Assn., Peter England, Superdry, and more

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| ![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white) **Azure SQL Database** | Cloud-hosted relational database used to store and manage the dataset |
| ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black) **Power BI Desktop** | Connected to Azure SQL as a live data source; used to build and publish the interactive dashboard |
| ![SQL](https://img.shields.io/badge/SQL-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white) **SQL** | Querying, filtering, and transforming data within Azure SQL before loading into Power BI |
| ![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white) **Microsoft Excel** | Initial data exploration, cleaning, and validation before ingestion into Azure SQL |

---

## 🏗️ Architecture & Workflow

```
Raw CSV Data (Men_Tshirt.csv)
        │
        ▼
 Microsoft Excel
 (Data Cleaning & Exploration)
        │
        ▼
  Azure SQL Database
  (Cloud Data Storage & SQL Queries)
        │
        ▼
   Power BI Desktop
   (Connected via Azure SQL connector)
        │
        ▼
 Interactive Dashboard (.pbix)
```

---

## 📈 Dashboard Highlights

The Power BI report (`Azure_PowerBI_Project.pbix`) includes visuals and insights such as:

- **Brand-wise Average Sale Price** — Compare average selling prices across all 144 brands
- **Discount Analysis** — Original vs. Sale price comparison to identify top discounted brands
- **Price Range Distribution** — Understand how listings are spread across budget, mid-range, and premium segments
- **Top Brands by Listing Count** — See which brands have the highest product variety
- **Premium vs. Budget Segmentation** — Identify international premium brands vs. Indian value brands

---

## 🚀 Getting Started

### Prerequisites

- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
- Access to Azure SQL Database (or restore data locally)
- Microsoft Excel (for raw data preview)

### Steps to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/Dogra-458/-Men-s-Clothing-Brands-Power-BI-Dashboard
   ```

2. **Set up Azure SQL Database**
   - Create an Azure SQL Database instance
   - Import `Men_Tshirt.csv` into a table (e.g., `dbo.MensTshirts`)
   - Run any SQL transformation scripts if included

3. **Open Power BI Report**
   - Open `Azure_PowerBI_Project.pbix` in Power BI Desktop
   - Update the data source credentials to point to your Azure SQL server
   - Navigate to **Home → Transform Data → Data Source Settings** and enter your server/database details

4. **Refresh Data**
   - Click **Refresh** in Power BI to load the latest data from Azure SQL

---

## 📁 Project Structure

```
📦 mens-clothing-powerbi
 ┣ 📊 Azure_PowerBI_Project.pbix   # Power BI dashboard file
 ┣ 📄 Men_Tshirt.csv               # Raw dataset
 ┗ 📘 README.md                    # Project documentation
```

---

## 🔍 Key Insights (Sample)

- Over **144 unique brands** are represented, ranging from local Indian labels to global fashion houses
- Significant discount gaps exist between **Original Price** and **Sale Price** across most listings
- Premium brands like **Tommy Hilfiger**, **Armani Exchange**, and **Brooks Brothers** command the highest average sale prices
- Budget-friendly Indian brands such as **The Indian Garage Co**, **DNMX**, and **Snitch** dominate listing volume

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo, improve the dashboard, add new visuals, or enhance the SQL queries. Open a pull request with a clear description of your changes.

---


## 👤 Author

**Sumit Dogra**
- GitHub: [@Dogra-458](https://github.com/Dogra-458)
- LinkedIn: [sumit-kumar-69b33423b](https://www.linkedin.com/in/sumit-kumar-69b33423b)

---

> *Built with Azure SQL + Power BI + Excel + SQL — turning raw clothing data into actionable retail insights.*
