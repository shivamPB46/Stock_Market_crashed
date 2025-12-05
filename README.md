📉 Sensex Crash Detection & Market Early-Warning System

A complete analysis of market crashes, drawdowns, and early warning signals using Python & Plotly.

This project performs historical Sensex crash detection, identifies market drawdown clusters, visualizes major crash periods (1997, 2008, 2020), and generates a synthetic early-warning system for 2025 using rolling statistics.

The notebook provides interactive charts to understand how markets behave before, during, and after major crashes.

🚀 Key Features
✅ 1. Data Preprocessing

Reads Sensex historical data from CSV

Cleans and sorts date column

Computes daily returns

Sets datetime index for time-series analysis

✅ 2. Daily Crash Detection

Detects days where daily return ≤ –5%

Highlights crash points on interactive Plotly charts

Visualizes volatility spikes

✅ 3. Market Drawdown Analysis

Computes cumulative max

Calculates drawdown percentage

Marks deep drawdowns (≤ –20%)

Lists dates where major drops occurred

✅ 4. Crash Cluster Identification

Finds clusters where market remained under drawdown for consecutive days

Groups crashes into periods

Extracts start and end dates for each crash cluster

✅ 5. Visualizing Major Crash Events

Interactive charts for:

1997 Crash

2008–09 Global Financial Crisis

2020 COVID-19 Crash

Each plotted with:

Closing price

Daily returns

Drawdown

Highlighted crash window

✅ 6. Synthetic 2025 Early-Warning System

Simulates 2025 market behavior using:

Randomized daily returns

Rolling mean

Rolling volatility

Warning rule:

Rolling Mean < -0.5 AND Rolling Volatility > 2


Highlights potential early-warning signals for a market crash.

📊 Technologies Used

Python

Pandas

NumPy

Plotly (Interactive Graphs)

Time Series Analysis

📁 What This Notebook Shows

✔ Sensex historical movement
✔ Daily crash detection
✔ Drawdowns and market bottoms
✔ Crash period zoom-ins
✔ Early-warning signal model for future markets

🌟 Great For

Students learning financial data science

Market crash analysis

Visualization of time-series events

Algorithmic trading research

Portfolio risk analysis
