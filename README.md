# 📊Bitcoin-trader-sentiment-analysis
This project explores how Bitcoin traders perform under different market sentiments (Fear and Greed), uncovering behavioral patterns and insights that could be used to build smarter trading strategies.

---

## 🎯 Objective

To analyze whether market sentiment influences:
- Trader **profitability (PnL)**
- **Trade sizes** and **volumes**
- **Buy/Sell tendencies**
- Patterns in behavior during "Fear" vs "Greed" conditions

---

## 🧩 Datasets Used

### 1. 📈 Trader Data – [Hyperliquid Dataset]
- **Fields**: Account, Execution Price, Size USD, Side, Start Position, Closed PnL, Timestamp, etc.

### 2. 📉 Sentiment Data – [Bitcoin Fear and Greed Index]
- **Fields**: Date, Classification (Fear/Greed)

---

## 🔧 Methodology

- Cleaned and merged datasets based on matching trade dates.
- Mapped `Fear` and `Greed` into sentiment categories.
- Performed exploratory analysis and created visualizations to highlight behavioral differences.
- Analyzed trade size distribution and profit trends under varying sentiment.

---

## 📊 Key Visualizations

- **Average PnL by Sentiment**  
- **Total Volume by Sentiment**  
- **Distribution of Trade Sizes (KDE)**  
- **Buy vs Sell Frequency by Sentiment**

Plots were created using Seaborn and Matplotlib in Google Colab.

---

## 💡 Key Insights

- Traders show **higher average profits during Fear days** than Greed days.
- **More trading activity** occurs when the market is in a fearful state.
- Trade sizes are **generally small**, but their distribution shifts slightly based on sentiment.

These findings suggest that **cautious or opportunistic behavior during Fear** may lead to better outcomes.

---

## 📁 Project Files

| File Name                           | Description                                  |
|------------------------------------|----------------------------------------------|
| `Bitcoin_Trader_Sentiment_Analysis_Jevika.ipynb` | Main notebook with code, plots, insights     |
| `hyperliquid_trades.csv`           | Trader data (executions, sizes, PnL, etc.)   |
| `fear_greed_index.csv`             | Market sentiment per day (Fear/Greed)        |
| `README.md`                        | This documentation                           |

---

## 🚀 Technologies Used

- Python (Pandas, Seaborn, Matplotlib)
- Google Colab
- CSV + Google Drive Integration

---

## 👤 Author

**K. S. Jevika**  
Final Year B.E. CSE | Data Science & AI Enthusiast  
ksjevi2005@gmail.com

---

## 📜 License

This project is shared for academic and internship evaluation purposes only.

