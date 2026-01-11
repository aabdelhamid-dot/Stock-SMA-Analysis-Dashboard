# Stock-SMA-Analysis-Dashboard
📈 Stock Trend Analysis Dashboard (Python)
A Python-based, multi-timeframe stock analysis dashboard that uses 20-period (SMA-20) and 50-period (SMA-50) Simple Moving Averages to identify and visualize market trends on hourly and daily charts.
The dashboard evaluates the relative position of both moving averages to automatically determine trend direction for each timeframe.

🚀 Features
Hourly & Daily Trend Detection
- SMA-20 & SMA-50 indicators
- Automatic Bullish / Bearish / Neutral signals
- Interactive or static chart visualization
- Clean, professional dashboard layout

🧠 Strategy Logic

Two moving averages are calculated for each timeframe:

SMA-20 → short-term momentum

SMA-50 → medium-term trend

Trend is determined as:

Condition	Trend
SMA-20 > SMA-50	Bullish 📈
SMA-20 < SMA-50	Bearish 📉
SMA-20 ≈ SMA-50	Neutral ➖

This logic is applied separately to hourly and daily data, allowing multi-timeframe confirmation of trends.

📊 Dashboard Output

The dashboard shows:

Hourly candlestick or line chart

Daily candlestick or line chart

SMA-20 & SMA-50 overlays

Trend label for each timeframe

This allows you to quickly identify:

Trend alignment

Trend reversals

Conflicting timeframe signals

🧰 Tech Stack

Python

Pandas

NumPy

Matplotlib / Plotly

yFinance / CSV / API data source

















  
