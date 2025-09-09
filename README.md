# ds_-Mohammed_Adil-
Project Title:

Bitcoin Trader Performance Analysis Using Market Sentiment

Overview:
This project analyzes how Bitcoin market sentiment affects trader performance using historical trades from Hyperliquid and the Fear & Greed Index. The analysis identifies profitable trading periods, risks, and strategy recommendations based on market sentiment.

Objective:
Understand the relationship between market sentiment and trader performance.
Identify low-risk, high-profit trading opportunities.
Provide actionable insights for traders and strategy designers.

Datasets Used:
Historical Trader Data – 32,550 trades, including profit/loss and trade volume.
Bitcoin Market Sentiment Data – 2,644 days of Fear & Greed Index scores.

Methodology:
Data Cleaning – Process timestamps, handle missing values.
Data Merging – Combine trades with corresponding sentiment labels by date.
Exploratory Data Analysis (EDA) – Analyze PnL distribution, trading volume, win rates, and losses by sentiment.
Insights Extraction – Identify patterns in trader performance across different sentiment phases.

Key Findings:
Neutral Sentiment: Balanced profits, high win rate, low losses – safest trading period.
Fear: High profits, moderate risk – strong opportunities.
Extreme Greed: High win rate, moderate profit – requires careful risk management.
Greed & Extreme Fear: High-risk periods with large losses; not recommended for inexperienced traders.

Summary Table:
Sentiment	        Trades	Avg PnL (₹)	Win Rate	Total Volume (₹)	Risk Level
Neutral           5,854	  105.9	      46.3%	    0.88M	            Low
Fear	            9,761	  165.9	      40.2%	    4.35M	            Medium
Extreme Greed	    6,924	  59.2	      48.4%	    254M	            Medium
Greed	8,758	103.6	40.8%	27.8M	High
Extreme Fear	1,246	258.9	32.9%	1.67M	Very High
Recommendations

For Traders:
Focus on Neutral and Fear periods for balanced profitability and stability.
Be cautious during Extreme Greed; manage trade sizes carefully.
Avoid Extreme Fear unless experienced due to high volatility.

For Strategy Design:
Increase position sizes during Neutral and Fear phases.
Reduce exposure during Extreme Greed and Extreme Fear.
Use Extreme Greed spikes as early warning signals for potential market corrections.

Deliverables:
Google Colab Notebook – Full code with EDA and visualizations.
Graphs – Sentiment distribution, Profit trends, Trading volume analysis.
Final Report – Summarized insights and recommendations (PDF format).

How to Use:
Open the Google Colab notebook or run the Python scripts.
Follow the instructions to load datasets and perform analysis.
Generate visualizations and insights automatically.

Technologies Used:
Python (Pandas, NumPy, Matplotlib, Seaborn)
Jupyter/Google Colab
FPDF (for generating PDF reports)
