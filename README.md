# 🧸 Mexico Toy Sales - Power BI Dashboard

An interactive Power BI dashboard analyzing 2 years (2022–2023) of sales and inventory data for a fictitious toy store chain in Mexico. Built to answer real business questions around profitability, seasonality, stockouts, and inventory efficiency.

![Dashboard Preview](dashboard-preview.png)

---

## 📊 Project Overview

This project uses the **Mexico Toy Sales** dataset from [Maven Analytics](https://www.mavenanalytics.io/), which includes product, store, daily sales transaction, and inventory data for a chain called Maven Toys.

The goal wasn't just to build charts — it was to answer the dataset's own recommended analysis questions with insights a stakeholder could actually act on.

## ❓ Business Questions Answered

1. Which product categories drive the biggest profits?
2. Are there seasonal trends or patterns in the sales data?
3. Are we losing sales due to products being out of stock at certain locations?
4. How much money is tied up in inventory, and how long will it last?

## 🔍 Key Insights

- **Year-over-Year Reversal:** 2022 grew steadily to a December peak, while 2023 peaked early in March and declined every month since (data available through September). This isn't seasonality repeating — it's a real reversal worth investigating.
- **Stockout Risk:** 20 products are currently out of stock across multiple cities, with Monterrey, Hermosillo, and Guanajuato most affected. With 17 days of average stock coverage, restocking delays beyond that window risk further lost sales.
- **Margin Outlier:** Colorbuds drives the most total profit ($834.9K) but at a mid-tier margin (53.4%), while Jenga has the highest margin (70.1%) but far lower volume — worth asking whether Jenga is under-marketed or supply-constrained.

## 🛠️ Tools Used

- **Power BI** — data modeling, DAX measures, dashboard design
- **Power Query** — data cleaning and shaping

## 🧠 Process & Approach

Beyond building the visuals, a large part of this project focused on **quality control** — treating the dashboard the way a senior analyst or hiring manager would scrutinize it before it ships:

- Cross-referencing every KPI, table, and written insight against each other to catch inconsistencies (e.g., a written insight referencing a number that didn't match what a filtered view would show)
- Verifying that headline claims matched the actual shape of the underlying trend, not an assumption about it
- Prioritizing "so what" over "what happened" in every insight — the goal was decision-relevant findings, not just descriptive stats
- Iterating field names, number formatting, color consistency, and table structure to remove anything that looked like a first draft

## 📁 Dataset

- **Source:** [Maven Analytics – Mexico Toy Sales](https://www.mavenanalytics.io/data-playground)
- **License:** Public Domain
- **Records:** 499 | **Fields:** 25 | Multiple related tables (products, stores, transactions, inventory)

## 📌 Notes

This is a portfolio project built for practice and demonstration purposes. The dataset represents a fictitious company; all findings are illustrative.

---

⭐ If you found this useful or have feedback, feel free to open an issue or connect with me on [https://www.linkedin.com/in/nkanyiso-gwane](#).

