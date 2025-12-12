Trader Behavior vs Market Sentiment — Analytical Study

This project investigates how trader actions—such as profitability, trade size, leverage usage, and overall risk exposure—shift in response to market sentiment captured by the Fear & Greed Index. Through exploratory analysis, clustering techniques, correlation studies, and regression modeling, the aim is to reveal behavioral patterns and sentiment-driven signals that can support smarter trading decisions.

Project Layout
ds_kalashbagde/
├── notebook_1.ipynb        # Main analysis: EDA, clustering, regression
├── notebook_2.ipynb        # Optional secondary exploration
├── csv_files/              # Cleaned datasets and processed outputs
├── outputs/                # Visualizations, charts, and cluster figures
├── ds_report.pdf           # Final consolidated report
└── README.md               # Project summary and setup guide

Core Findings

Fear-driven market conditions often correlate with stronger profitability, even with comparatively lower trading volume.

Greed phases typically bring larger volume and more aggressive risk-taking, but do not always translate into better returns.

Some volatility-based metrics appear to move before sentiment shifts, indicating possible predictive behavior.

Using lagged sentiment (previous day’s sentiment value) improves forecasting ability in certain regression models.

How to Use This Repository

Open notebook_1.ipynb in Google Colab.

Upload the raw trader dataset and sentiment CSVs when prompted.

Run the notebook top-to-bottom to generate processed data, visual outputs, and insights.

Final results, plots, and summaries will be saved into the csv_files and outputs folders.

Datasets Used

Trader Execution Data
Contains account-level trade details such as timestamps, execution prices, trade size, PnL, leverage, and trade direction.

Fear & Greed Index Data
Daily sentiment classification allowing market-behavior comparison between “Fear” and “Greed” environments.

Download Links:

Historical Trader Data:
https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing

Fear & Greed Index:
https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing

(Both datasets are also provided in the repository under the csv_files/ directory.)
