This project analyzes how trader behavior and performance vary under different market sentiment conditions (Fear vs Greed) using historical crypto trading data and the Bitcoin Fear & Greed Index.

Project Structure

ds_manishankerreddy/
├── notebook_1.ipynb
├── notebook_2.ipynb
├── csv_files/
│   ├── historical_data.csv
│   ├── fear_greed_index.csv
│   └── processed_trader_sentiment_data.csv
├── outputs/
│   ├── avg_pnl_by_sentiment.png
│   ├── avg_position_size.png
│   └── trade_activity.png
├── ds_report.pdf
└── README.md



Notebooks Overview

Notebook 1: Data Cleaning & Preprocessing
- Loaded trader and sentiment datasets
- Converted timestamps to datetime format
- Normalized sentiment labels (Fear vs Greed)
- Removed neutral sentiment records
- Merged trade data with daily market sentiment
- Saved cleaned dataset for analysis

Notebook 2: Analysis & Insights
- Profitability comparison by sentiment
- Risk analysis using position size
- Trading activity and fee analysis
- Visualized key findings


Key Insights
- Greed periods show higher average PnL and win rate
- Fear periods involve larger position sizes and higher transaction costs
- Trader behavior shifts significantly based on market sentiment

Google Colab Links
- Notebook 1: [Add Colab Link Here]
- Notebook 2: [Add Colab Link Here]

Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab


How to Reproduce
1. Open the Colab notebooks using the links above
2. Ensure CSV files are placed inside `csv_files/`
3. Run notebooks sequentially (Notebook 1 → Notebook 2)

Report
Detailed findings and explanations are available in `ds_report.pdf`.
