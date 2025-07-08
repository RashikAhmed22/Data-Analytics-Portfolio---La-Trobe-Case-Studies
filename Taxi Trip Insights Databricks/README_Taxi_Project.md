# 🛺 Taxi Data Analysis with Azure Databricks

This project is part of a university assignment for the subject **BUS5WB – Big Data and Cloud Analytics**. It demonstrates how big data analytics can be performed on NYC Yellow Taxi trip data using **Azure Databricks**.

## 📘 Project Overview

The goal of this project is to extract valuable insights from a large dataset of taxi trips by performing exploratory data analysis (EDA) using Databricks and Python. The analysis includes:

- Fare distribution analysis
- Trip trends across weekdays
- Most profitable routes
- Pickup density by borough

## 🛠 Tools & Technologies

- **Azure Databricks**
- **Python (Pandas, Matplotlib, Seaborn)**
- **PySpark (optional for larger datasets)**
- **NYC Yellow Taxi Trip Data (January–March)**

## 📁 Dataset

Data Source: NYC Yellow Taxi Trips  
Files used: 
- `yellow_tripdata_2025-01.csv`
- `yellow_tripdata_2025-02.csv`
- `yellow_tripdata_2025-03.csv`

Each file contains millions of records with columns like pickup/dropoff time, location IDs, passenger count, payment type, fare amount, etc.

## 📊 Project Structure

| Part | Task Description |
|------|------------------|
| a)   | Distribution of fares – plotted histogram of fare amount |
| b)   | Weekly trends – number of trips per day of the week |
| c)   | Profitable routes – grouped by pickup/dropoff location IDs |
| d)   | Heatmaps of trip densities in Manhattan & The Bronx |

## 📷 Screenshots & Output

All visual output such as bar charts, grouped data tables, and heatmaps are included in the `outputs/` folder.

> These visuals were used for analysis only – evaluation is based on Databricks notebook and final PDF report.

## 🧪 How to Run

1. Upload the taxi CSV files into Azure Databricks FileStore or mount external blob storage.
2. Import the `.ipynb` notebook provided in this repo into your Databricks workspace.
3. Attach a compute cluster and run cells sequentially.
4. Modify parameters (e.g. file paths) as needed to suit your environment.

## 📁 Repository Contents

```
├── 22030444_Assignment_3_Starter_Notebook.ipynb
├── outputs/
│   ├── fare_distribution.png
│   ├── trip_count_by_day.png
│   ├── top_routes_table.png
│   └── pickup_heatmaps.png
└── README.md
```

## 🎓 Author Info

- **Name**: Rashik Ahmed Khan  
- **University**: La Trobe University  
- **Course**: Master of Business Analytics  
- **Subject**: BUS5WB – Big Data and Cloud Analytics

## 📌 Notes

This project was built under academic conditions. Code is optimized for clarity and pedagogy rather than production performance.
