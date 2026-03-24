# ⚡ Baki - XAU/USD Scalper Bot ⚡

**Baki Hanma** is an automated trading bot designed to dominate the gold market (XAU/USD). Like Baki in *Baki*, it uses sharp, powerful strategies to capture fast market moves. This scalping bot leverages proven technical indicators such as the **Simple Moving Average (SMA)** and the **RSI (Relative Strength Index)** to detect short-term trading opportunities while maximizing profits from small fluctuations.

---

## 🧠 Description du bot <img src="../images/Baki_hanma.png" alt="Doppo Bot" width="150" height="150" align="right" style="border-radius: 50%;">

**Bot name:** Baki Hanma  
**Bot type:** Scalper for XAU/USD trading (Gold vs US Dollar)  
**Technology:** MQL5 (MetaTrader 5)


---

## ⚙️ Fonctionnalités

- **XAU/USD scalping**: Take advantage of small fluctuations in the gold market.
- **Indicators used**:
  - **Simple Moving Average (SMA)**: Tracks the overall market trend.
  - **RSI**: Detects overbought and oversold conditions.
- **Risk management**: The bot applies fixed **Stop Loss** and **Take Profit** levels for each position.
- **Position entry**:
  - **Buy**: When an uptrend is confirmed and RSI is below 30.
  - **Sell**: When a downtrend is confirmed and RSI is above 70.

---

## 💻 Installation

### 🔧 Prérequis

- **MetaTrader 5**: The bot is designed for the MetaTrader 5 (MT5) platform.
- **Trading account**: You will need a trading account to test and run the bot.
- **Market data access**: Make sure your broker provides XAU/USD data.

### 📥 Étapes d'installation

1. Download `XAU_USD_Scalper.mq5`.
2. Open **MetaEditor** in MetaTrader 5.
3. Go to **File > Open Data Folder**.
4. Place `XAU_USD_Scalper.mq5` in **MQL5 > Experts**.
5. Compile the file in **MetaEditor** to generate the executable `.ex5`.
6. Open MetaTrader 5 and select an **XAU/USD** chart.
7. Drag the "Baki" bot from the **Navigator** onto the **XAU/USD** chart.
8. Enable **Auto Trading** in MetaTrader 5 to allow the bot to run.

---

## ⚙️ Configuration

You can adjust the bot parameters when you add it to the chart:

- **MovingAveragePeriod**: Moving Average period. Default: `14`.
- **RSIPeriod**: RSI period. Default: `14`.
- **LotSize**: Position size (lots). Default: `0.1`.
- **TakeProfit**: Take Profit distance in pips. Default: `10`.
- **StopLoss**: Stop Loss distance in pips. Default: `10`.

---

## 📈 Stratégie de Trading

- **Buy**: When the Moving Average indicates an uptrend and RSI is below 30, a buy order is executed.
- **Sell**: When the Moving Average indicates a downtrend and RSI is above 70, a sell order is executed.
- **Stop Loss and Take Profit**: Positions are automatically closed if price reaches the **Stop Loss** or **Take Profit** levels.

---

## ⚠️ Avertissements

- **Risk of loss**: As with any trading strategy, there is a risk of loss. Test the bot on a **demo account** before using it on a live account.
- **No profit guarantee**: Past performance does not guarantee future profits. Use the bot with caution.
- **Regular monitoring**: Even though the bot is automated, it’s recommended to monitor performance and retune settings when needed.

---

## 📜 Licence

This bot is released under the **MIT License**, which allows you to modify and use it for your own purposes, as long as you include the license and credit the author.

---

## 👨‍💻 Auteurs

- **Creator:** Don-Gio (Inspiration: *Baki* universe)
- **Developer:** Don-Gio

---

## 📞 Contact

For any questions or issues, contact the development team via:

- **Email:** contact@topimaso.com  
- **Website**: [TopiMaso Studio](https://www.topimaso.com)

---

### **May your gold trading be as strategic and relentless as Baki in the ring!** 💥🥋
