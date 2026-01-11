# Stock-SMA-Analysis-Dashboard
A multi-timeframe stock analysis dashboard that uses 20-period (SMA-20) and 50-period (SMA-50) Simple Moving Averages to identify and visualize market trends on hourly and daily charts.
The dashboard automatically evaluates the relative position of both moving averages to determine trend direction, helping traders and analysts quickly assess market conditions across timeframes.
🚀 Features
Multi-timeframe analysis
  Hourly trend detection
  Daily trend detection
Moving average strategy
  SMA-20 (short-term trend)
  SMA-50 (medium-term trend)
Automatic trend detection
  Identifies Bullish, Bearish, or Neutral trends based on SMA positioning
Visual dashboard
  Clean, professional chart layout
  Trend labels for each timeframe

🧠 How It Works
The system calculates two moving averages for each timeframe:
  SMA-20 → short-term momentum
  SMA-50 → medium-term trend

| Condition       | Trend       |
| --------------- | ----------  |
| SMA-20 > SMA-50 | Bullish 📈  |
| SMA-20 < SMA-50 | Bearish 📉  |
| SMA-20 ≈ SMA-50 | Neutral ➖  |

This logic is applied separately to hourly and daily price data, allowing you to see alignment or divergence between short- and long-term trends.

🖥️ Dashboard Output
The dashboard displays:
  Hourly chart with SMA-20 and SMA-50
  Daily chart with SMA-20 and SMA-50
  Trend label for each timeframe
This makes it easy to spot:
  Trend confirmations
  Trend reversals
  Timeframe conflicts (e.g., bullish daily, bearish hourly)

📊 Use Cases
Swing trading
Trend following strategies
Market condition monitoring
Multi-timeframe technical analysis

⚙️ Tech Stack
Python
Pandas
NumPy
Plotly / Matplotlib / TradingView (or your charting library)
API or CSV price data


















  
