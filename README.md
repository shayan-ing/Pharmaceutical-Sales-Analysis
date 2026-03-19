# 💊 Pharmaceutical Sales Analysis

[![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![Dataset](https://img.shields.io/badge/Dataset-Foresight%20BI-blue)](https://foresightbi.com.ng/practice-data/3-datasets-for-your-portfolio/)

A comprehensive data analysis project exploring sales performance for **Foresight Pharmaceuticals** across the German and Polish markets. This repository contains the cleaned dataset, transformation steps, and a dynamic dashboard built in Microsoft Excel to uncover key business insights.

---

## 📖 Introduction

**Foresight Pharmaceuticals** is a global leader in the pharmaceutical industry, operating through a network of distributors rather than selling directly to customers. In exchange for distribution rights, the company has agreements with its partners to receive sales data.

This project dives deep into the sales data shared by distributors from two key European markets: **Germany** and **Poland**. The primary objective is to analyze this data to provide actionable insights that can drive strategic business decisions.

---

## ❓ Problem Statement

The core goal of this analysis is to answer critical business questions that will help Foresight Pharmaceuticals understand its market position and performance. The investigation focuses on the following areas:

*   **Market Performance:** Which country (Germany or Poland) generates the most sales, and what underlying factors contribute to this disparity?
*   **Product Analysis:** Which pharmaceutical products are the top performers, and which products are underperforming in each market?
*   **Sales Channels:** Which distribution channels and sub-channels are most effective at driving revenue?
*   **Year-over-Year Growth:** How has sales performance changed year-over-year for each sales channel?

---

## 📊 Dashboard Preview

Here’s a sneak peek at the interactive Excel dashboard created for this project. It provides a high-level overview of all the key metrics and findings.

![Pharmaceutical Sales Dashboard](https://github.com/shayan-ing/Pharmaceutical-Sales-Analysis/blob/main/Dashboard.png)

---

## 📂 Data Sourcing

The dataset used for this analysis is a simulated, practice-oriented dataset published by **Foresight BI & Analytics Global Solutions**. It is designed to mimic real-world business data, making it perfect for portfolio projects and skill development.

*   **Source:** [Foresight BI Practice Datasets](https://foresightbi.com.ng/practice-data/3-datasets-for-your-portfolio/)

---

## 🛠️ Data Transformation with Power Query

To ensure the data was clean, consistent, and ready for analysis, I performed a series of transformations using **Power Query Editor** in Microsoft Excel. The main steps included:

1.  **Promoting Headers:** The first row of the raw data was promoted to become the column headers for better readability.
2.  **Validating Data Types:** I carefully reviewed and set the correct data type for each column (e.g., Date, Currency, Text) to ensure accuracy in calculations.
3.  **Removing Redundant Data:** The `Latitude` and `Longitude` columns were removed from the table as they were not required for the scope of this analysis.

Below is a screenshot of the data cleaning process within Power Query:

![Data Cleaning Process in Power Query](https://github.com/shayan-ing/Pharmaceutical-Sales-Analysis/blob/main/Data_cleaning.png)

---

## 🔍 Key Findings & Insights

The analysis revealed significant disparities between the two markets and highlighted critical areas for business attention.

### 🌍 1. Significant Market Imbalance
*   **Germany** is the dominant market, accounting for a staggering **94.23%** of total sales.
*   **Poland** only contributed **5.77%** to the overall sales figures.
*   A major contributing factor was the **complete absence of sales data from Poland for the years 2017, 2019, and 2020**. This suggests potential issues with data delivery from distributors or actual supply chain disruptions in the Polish market.

### 💊 2. Product Performance Polarization
*   **Top Performers:** The top 10 best-selling products were sold exclusively in the **German** market.
*   **Underperformers:** Conversely, the bottom 10 products with the lowest sales were all located in the **Polish** market.
*   This stark contrast underscores the performance gap between the two countries and points to a need for a deeper investigation into the Polish market's product strategy and distribution.

### 📈 3. (Add your findings for channels and YoY change here)
*   *Example:* The "Hospital" channel was the leading sub-channel in Germany, while "Retail" was more prominent in Poland's limited sales data.
*   *Example:* Year-over-year analysis shows a steady growth in Germany through the "Pharmacy" channel, while Polish channels show inconsistent activity due to missing data years.

---

## 🚀 How to Use This Project

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/shayan-ing/Pharmaceutical-Sales-Analysis.git
    ```
2.  **Open the Excel File:** Navigate to the folder and open the `Pharmaceutical_Sales_Analysis.xlsx` file (or whatever your main Excel file is named).
3.  **Explore the Data:**
    *   Go to the **"Dashboard"** tab to view the interactive charts and summaries.
    *   Go to the **"Raw Data"** or **"Transformed Data"** tab to see the dataset used for the analysis.
    *   Explore the **"Queries"** tab in Power Query to see the step-by-step transformation applied to the data.

---

## 🤝 Connect & Contribute

Feel free to fork this project, raise issues, or submit pull requests. If you have any questions or suggestions, please drop a mail to me!

**If you find this project helpful, please consider giving it a ⭐!**

- In terms of the channel of distribution, pharmacy recorded the highest sales with **53.94%** in total sales. More sales were made via retail subchannel with about **4%** in sales ahead of institution.

- There was a **7.13%** increase in sales in sales in Germany via the hospital channel in 2018, but a **1.79%** and **-13.40%** in sales in 2019 and 2020 respectively. The sales representation in 2020 would have been as a result of the COVID19 pandemic.
