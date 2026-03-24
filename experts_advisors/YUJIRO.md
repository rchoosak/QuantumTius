# ⚡ **Yujiro** - BTC/USD Scalper Bot ⚡

**Yujiro** is an automated trading bot designed specifically for the cryptocurrency market, especially for **BTC/USD trading**. This scalper uses proven technical indicators such as the **Simple Moving Average (SMA)** and the **Relative Strength Index (RSI)** to detect the best opportunities and execute short-term trades.

---

## 🧠 **Description du Bot** <img src="../images/Yujiro_Hanma.png" alt="Doppo Bot" width="150" height="150" align="right" style="border-radius: 50%;">

**Bot name:** Yujiro Hanma  
**Bot type:** Scalper for BTC/USD trading  
**Technology:** MQL5 (MetaTrader 5)

Inspired by the ultimate fighter **Yujiro Hanma** from *Baki*, this bot applies a relentless strategy, making fast and calculated decisions to exploit small price fluctuations while limiting risk through effective **Take Profit** and **Stop Loss** management.

---

## ⚙️ **Fonctionnalités**

- **BTC/USD scalping**: Takes positions on small price moves on BTC/USD.
- **Indicators used**:
  - **Simple Moving Average (SMA)**: Helps detect market trends.
  - **RSI (Relative Strength Index)**: Identifies overbought and oversold conditions.
- **Risk management**: Uses fixed **Stop Loss** and **Take Profit** for each position to protect capital.
- **Position entry**:
  - **Buy**: When the moving average is in an uptrend and RSI is below 30 (oversold).
  - **Sell**: When the moving average is in a downtrend and RSI is above 70 (overbought).

---

## 🛠️ **Installation**

### **Prérequis** :
- **MetaTrader 5 (MT5)**: This bot is designed to run on MetaTrader 5.
- **Trading account**: You need a trading account to test and run the bot.
- **Market data access**: Make sure you have BTC/USD market data access via your broker.

### **Étapes d'installation** :

1. Download `BTC_USD_Scalper.mq5`.
2. Open **MetaEditor** from MetaTrader 5.
3. Go to **File > Open Data Folder**.
4. Place `BTC_USD_Scalper.mq5` in **MQL5 > Experts**.
5. Compile the file in MetaEditor to generate the EX5 file.
6. Open a **BTC/USD** chart in MetaTrader 5.
7. Drag the "Yuujirou" bot from the **Navigator** onto the BTC/USD chart.
8. Enable **Auto Trading** in MetaTrader 5.

---

## ⚙️ **Configuration**

You can adjust the bot parameters when adding it to a chart or directly in the source file. Here are the default configurable settings:

- **MovingAveragePeriod**: Moving average period. Default: `14`.
- **RSIPeriod**: RSI period. Default: `14`.
- **LotSize**: Position size (lots). Default: `0.1`.
- **TakeProfit**: Take Profit in pips. Default: `10`.
- **StopLoss**: Stop Loss in pips. Default: `10`.

---

## 🛑 **Stratégie de Trading**

- **Buy signal**: When the moving average is in an uptrend and RSI is below 30, a buy order is executed.
- **Sell signal**: When the moving average is in a downtrend and RSI is above 70, a sell order is executed.
- **Stop Loss and Take Profit**: Positions are closed automatically if price reaches either the Stop Loss or Take Profit level.

---

## ⚠️ **Avertissements**

- **Risk of loss**: As with any trading strategy, there is a risk of loss. First test the bot in a **demo account** environment before using real money.
- **No profit guarantee**: This bot follows an algorithmic strategy, but past results do not guarantee future performance.
- **Regular monitoring**: Even though the bot is automated, it’s important to monitor performance regularly and adjust settings when needed.

---

## 📜 **Licence**

This bot is released under the **MIT License**, which allows you to modify and use it for your own purposes, as long as you include the license and credit the author.

---

## 👨‍💻 **Auteurs**

- **Creator**: Don-Gio (Inspiration: *Baki* universe)
- **Developer**: Don-Gio

---

## 📞 **Contact**

If you have questions or need support, feel free to contact the development team via:

- **Email**: contact@topimaso.com
- **Website**: [TopiMaso Studio](https://www.topimaso.com)

---

**May your trading be as ruthless and precise as Yuujirou Hanma in the ring!** 💥
