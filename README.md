# Trader Behavior Insights <br>
## Trader Behavior & Market Sentiment Analysis
## Overview
This project analyzes the relationship between **trader performance** and **market sentiment** (Fear & Greed Index) in the Bitcoin market.  <br>
It combines **exploratory data analysis, hypothesis testing, predictive modeling, and risk analysis** to uncover meaningful insights.  <br>
<br>
---

## Project Structure 
ds_MahathiJampani/ <br>
├── notebook_1.ipynb # Colab notebook with all code <br>
├── csv_files/ # Processed / intermediate data <br>
│ ├── cleaned_trader_data.csv <br>
│ ├── daily_summary.csv <br>
│ └── weekly_summary.csv <br>
├── outputs/ # Visualizations (charts, plots, heatmaps) <br>
│ ├── avg_pnl_lagged.png <br>
│ ├── avg_pnl_sentiment.png <br>
│ ├── correlation_heatmap.png <br>
│ ├── pnl_distribution.png <br>
│ ├── proxy_leverage_boxplot.png <br>
│ ├── weekly_winrate.png <br>
│ └── winrate_lagged.png <br>
├── ds_report.pdf # Final summarized report <br>
└── README.md # Project documentation <br>
<br>
---

## 🛠️ Methods Used
- Data Cleaning & Preprocessing  <br>
- Exploratory Data Analysis (EDA)  <br>
- Hypothesis Testing (Levene’s test, ANOVA) <br> 
- Feature Engineering (lagged sentiment, leverage proxy) <br> 
- Predictive Modeling (Regression, Classification)  <br>
- Risk Analysis (VaR, CVaR)  <br>
<br>
---

## 📊 Key Insights
- **Profitability** is highest in *Extreme Greed* and lowest in *Neutral*.  <br>
- **Extreme Fear** phases show highest leverage and greatest downside risk. <br> 
- **Lagged sentiment** shows momentum effects (yesterday’s sentiment affects today’s PnL). <br> 
- Classification achieved **91.7% accuracy** in predicting win/loss outcomes.  <br>
- ANOVA (p-value < 0.001) confirms statistically significant differences in profitability across sentiment groups.  <br>
<br>
---

## 🚀 Technologies
- Python <br> 
- Google Colab / Jupyter Notebook  <br>
- ReportLab (PDF report generation)  <br>
<br>
---

## 📑 Report
For full details, refer to [ds_report.pdf](./ds_report.pdf).<br>
<br>
---

👩‍💻 **Author**: Mahathi Jampani
