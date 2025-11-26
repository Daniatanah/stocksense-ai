# Day 2 – Research & Resources  
**Project:** StockSense AI – Inventory Demand Forecaster  
**Date:** 20 November 2025  
**Prepared by:** Tana  

---

## 1. Objective  
The goal for Day 2 is to gather all relevant datasets, APIs, tools, and research insights needed to prepare for planning and design on Day 3. This phase focuses on understanding the data, selecting forecasting models, and sketching a rough high-level workflow.

---

## 2. Datasets Collected  

| Dataset Name | Source | Format | Notes |
|--------------|--------|--------|-------|
| Walmart Retail Sales Dataset | Kaggle | CSV | Daily/weekly sales data useful for prototyping forecasting models. |
| Synthetic Retail Sales Data | Generated | CSV | Custom sample dataset to validate preprocessing and forecasting logic. |
| Superstore Sales Dataset | Kaggle | CSV | Additional retail dataset for testing different product categories. |

All datasets uploaded to `/data/` directory.

---

## 3. Tools & Libraries (Researched and Selected)

### Programming & Data  
- **Python 3.9+** – primary development language  
- **Pandas, NumPy** – data cleaning and transformation  
- **Matplotlib, Plotly, Seaborn** – visualizations  

### Forecasting Models  
- **Prophet** – ideal for daily/weekly sales forecasting, strong seasonality handling  
- **ARIMA/SARIMA** – statistical baseline model for comparison  
- **Scikit-Learn** – may be needed for scaling, train/test splits  

### Prototype & Deployment  
- **Streamlit / Gradio** – quick UI for MVP  
- **Google Colab / Jupyter Notebook** – experimentation environment  
- **GitHub** – version control, documentation, and public portfolio  

---

## 4. Key Research Insights  

- Forecast accuracy depends heavily on data quality (missing dates, inconsistent product IDs, outliers).  
- Prophet is easier to implement and handles weekly, monthly, and yearly seasonality automatically.  
- ARIMA offers more control but requires manual parameter tuning (p, d, q).  
- Retail forecasting benefits from adding external indicators like promotions, holidays, events, or weather (future improvement).  
- MVP should prioritize simplicity: **CSV Upload → Clean Data → Forecast → Visual Charts → Download Results**.  

---

## 5. Rough Workflow (Initial Draft)

```text
User Uploads CSV
        ↓
Data Cleaning & Preprocessing
        ↓
Model Selection (Prophet / ARIMA)
        ↓
Forecast Generation (Days/Weeks Ahead)
        ↓
Visualization (Interactive Line Charts)
        ↓
Downloadable Output (CSV or PDF Report)

 Useful Resources
Resource	Type	Link
Prophet Documentation	Docs	https://facebook.github.io/prophet/docs/quick_start.html

Walmart Kaggle Dataset	Dataset	https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting

ARIMA Guide	Tutorial	https://machinelearningmastery.com/arima-for-time-series-forecasting-with-python/

Streamlit Starter	Docs	https://docs.streamlit.io/library/get-started

 Day 2 Deliverables (Completed)

Datasets collected and saved in /data/

Tools and forecasting libraries selected

Initial research insights documented

Rough forecasting workflow drafted

LinkedIn daily update prepared
Day 2 of the #AfritechAIChallenge
Today, I focused on gathering datasets, testing forecasting tools, and sketching the workflow for my AI Inventory Demand Forecaster.
It's fascinating to see how AI transforms raw sales data into clear demand predictions.
Can’t wait to start the design phase tomorrow!

#AI #DataScience #DemandForecasting #AfritechAIChallenge #ProductManagement #MachineLearning #InventoryManagement
