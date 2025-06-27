A Python-based algorithmic trading system that uses RSI and moving averages to generate buy/sell signals. It logs trades to Google Sheets and sends alerts via Telegram. The system also trains a Decision Tree model using features like RSI, returns, volatility, and volume to predict stock price movement. Accuracy achieved: 61% (RELIANCE, TCS), 50% (INFY)
-->Modular Codebase
main.py: Orchestration
strategy.py: Trading logic
backtest.py: Simulation engine
ml_model.py: ML feature engineering & training
google_sheet.py: Sheets integration
telegram_bot.py: Bot messaging
