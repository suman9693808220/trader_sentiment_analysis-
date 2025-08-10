# trader_sentiment_analysis-
This project explores the relationship between trader performance and Bitcoin market sentiment (Fear &amp; Greed Index) to uncover patterns that can guide smarter trading strategies.
🔍 Project Overview
We use two datasets:

Bitcoin Market Sentiment Dataset – Contains daily Fear/Greed classifications.

Historical Trader Data (Hyperliquid) – Includes trade details such as account, symbol, execution price, size, side, closed PnL, leverage, and more.

The analysis includes:

Cleaning and preprocessing timestamp, trade, and sentiment data.

Merging sentiment data with trader performance metrics.

Feature engineering (PnL%, win/loss ratio, trade duration, etc.).

Exploratory Data Analysis (EDA) with visualizations.

Modeling trader performance prediction based on sentiment & trade features.

├── data/
│   ├── historical_data.csv          # Trader data
│   ├── fear_greed_index.csv         # Market sentiment data
├── trader_sentiment_analysis.ipynb  # Jupyter Notebook with full analysis
├── README.md                        # Project documentation
└── requirements.txt                 # Python dependencies
📈 Key Insights
Market sentiment correlates with certain trading behaviors and profitability.

Fear periods tend to reduce high-leverage profitable trades.

Greed periods often lead to over-leveraging and increased volatility in PnL.

⚙️ Tech Stack
Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

Jupyter Notebook for interactive analysis


