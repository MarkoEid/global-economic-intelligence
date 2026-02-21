# 🌍 Global World Economics Analysis

## 📖 Project Overview
This project provides a macro-economic evaluation of global markets, focusing on key indicators such as **GDP Growth, Inflation, Unemployment, and Debt**. A standout feature of this analysis is the integration of **Web Scraping** to resolve data quality issues, ensuring a complete dataset for global comparison.

---

## 📂 Dataset Information
* **Source:** [Kaggle](https://www.kaggle.com/) (World Economic Indicators)
* **Data Enrichment:** Implemented **Wikipedia Web Scraping** to fill missing data gaps for regions like **Monaco**, ensuring 100% data integrity for core indicators.
* **Domain:** Global Macro-Economics / Finance

### 📋 Key Indicators Analyzed
| Indicator | Description |
| :--- | :--- |
| **GDP Growth** | Annual percentage growth rate of a nation's GDP. |
| **Inflation** | Measurement of price level increases across goods and services. |
| **Dept/GDP** | The ratio of public debt to the country's economic output. |
| **Current Account** | International transaction records (Trade balance). |
| **Jobless Rate** | Unemployment metrics across different global regions. |

---

## 🛠️ Data Cleaning & Advanced Processing
* **Automated Data Retrieval:** Used `BeautifulSoup` and `requests` to scrape missing values directly from Wikipedia tables when Kaggle data was incomplete.
* **Complex Aggregation:** Created specialized data subsets for "High Inflation" and "Debt-Heavy" nations.
* **Professional Reporting:** Developed an automated pipeline using `pd.ExcelWriter` to export **10 distinct analysis sheets** into one business-ready file:
    * `main4` - `main10`: Includes Current Account, Debt/GDP, High Inflation, and Jobless analytics.

---

## 💻 Tech Stack
* **Language:** Python 3.x
* **Libraries:** `Pandas`, `NumPy`, `BeautifulSoup` (Scraping), `Requests`.
* **Tool:** Jupyter Notebook

---
