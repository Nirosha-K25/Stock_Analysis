# Stock_Analysis
Stock Data Analysis

Problem Statement:
The Stock Performance Dashboard aims to provide a comprehensive visualization and analysis of the Nifty 50 stocks' performance over the past year. The project will analyze daily stock data, including open, close, high, low, and volume values. Clean and process the data, generate key performance insights, and visualize the top-performing stocks in terms of price changes, as well as average stock metrics. The solution will offer interactive dashboards using Streamlit and Power BI to help Investors, analysts, and enthusiasts make informed decisions based on the stock performance trends.

Business Use Cases:
Stock Performance Ranking: Identify the top 10 best-performing stocks (green stocks) and the top 10 worst-performing stocks (red stocks) over the past year.
Market Overview: Provide an overall market summary with average stock performance and insights into the percentage of green vs red stocks.
Investment Insights: Help investors quickly identify which stocks showed consistent growth and which ones had significant declines.
Decision Support: Provide insights on average prices, volatility, and overall stock behavior, useful for both retail and institutional traders.

Approach:
Data Extraction and Transformation:
Data is provided in YAML format, organized by months.
Within each month's folder, there are date-wise data entries.
The task is to extract this data from the YAML file and transform it into a CSV format, organized by symbols 
This will result in 50 CSV files after the extraction process, one for each symbol or data category

Results:
A fully functional dashboard showing the top-performing and worst-performing stocks over the last year.
Insights on the overall market with clear indicators of stock performance trends.
Interactive visualizations using Power BI and Streamlit to make the data easily accessible for users.

Project Deliverables:
SQL Database: Contains clean and processed data.
Python Scripts: For data cleaning, analysis, and database interaction.
Power BI Dashboard: Visualizations for stock performance.
Streamlit Application: Interactive dashboard for real-time analysis.
