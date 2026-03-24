# QuantumTius <img src="./images/quantum.png" alt="Doppo Bot" width="150" height="150" align="right" style="border-radius: 50%;">

**QuantumTius** is a centralized repository for Expert Advisors (EAs), trading signals, and other tools built with **MQL5** for **MetaTrader 5 (MT5)**. This project brings together automated strategies, trading scripts, and optimization solutions for MT5 traders, with a particular focus on scalping **BTC/USD** and **XAU/USD**.

## Goal

The goal of **QuantumTius** is to provide a complete library of automated trading tools for **MetaTrader 5 (MT5)** users. This project is intended for creating, optimizing, and sharing **algorithmic trading strategies**, with special attention to popular pairs such as **BTC/USD** and **XAU/USD**.

## Features

- **Expert Advisors (EAs)**: MQL5 scripts for automated trading strategies, including scalping bots.
- **Trading signals**: Signal setups to support buy/sell decisions based on advanced technical analysis.
- **Strategy optimization**: Optimized algorithms for fast execution and effective risk management.
- **Backtesting**: Test strategies on historical data to validate effectiveness before going live.
- **Scalping on BTC/USD and XAU/USD**: Target high-frequency opportunities on these two popular markets.
- **Technical analysis scripts**: Indicators and scripts to support advanced technical analysis.

## Repository structure

Here is an overview of this repository’s structure:
```
QuantumTius/ 
│ ├── experts_advisors/ # Contains MT5 EAs
  │ ├── BTC_USD_Scalper.mq5 
  │ ├── XAU_USD_Scalper.mq5 
  │ └── ... 
│ ├── signaux/ # Contains trading signals
  │ ├── BTC_USD_Signal.mq5 
  │ ├── XAU_USD_Signal.mq5 
  │ └── ... 
│ ├── Indicators/ # Technical indicators for MT5
  │ ├── EMA_Crossover.mq5 
  │ ├── RSI_Indicator.mq5 
  │ └── ... 
│ ├── scripts/ # Analysis and optimization scripts
  │ ├── Backtest_Script.mq5 
  │ └── ... 
│ └── README.md # This file
```

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/ton-utilisateur/QuantumTius.git
   ```

2. Copy the `.mq5` files into the `Experts` directory of your MetaTrader 5 installation. By default, this directory is located at:
  ```sh
  C:\Program Files\MetaTrader 5\MQL5\Experts\
  ```

3. Open **MetaTrader 5**, then click **File > Open Data Folder**. Next, go to the `MQL5` directory and copy the files into the appropriate subfolder (Experts, Indicators, etc.).

4. Compile the `.mq5` files in MetaEditor to ensure they are ready to use.

5. Run the EAs or signals directly from MetaTrader 5 by adding the tools to your charts.

## Configuration
EAs and signals may require parameter adjustments to work correctly with your account and trading preferences.

Example configuration for a BTC/USD scalping EA:
```mql
input int    Slippage = 2;          // Allowed slippage
input double LotSize = 0.1;         // Position size
input int    TakeProfit = 50;       // Take profit in pips
input int    StopLoss = 30;         // Stop loss in pips
input string Symbol = "BTCUSD";     // Pair symbol
input int    TimeFrame = 5;         // Timeframe in minutes (5 minutes)
```

## Backtesting
You can test **QuantumTius** trading strategies on historical data in **MetaTrader 5** using the **Strategy Tester**. This lets you validate EA effectiveness and tune parameters to improve performance.

## Contributing
Contributions are welcome. If you have improvement ideas, bugs to report, or features to add, please open an issue or submit a pull request.

## How to contribute
* Fork the project.
* Create a new branch for your feature or bug fix.
* Make your changes and submit a pull request.

## License
This project is licensed under the MIT License. You are free to use and modify this code, but please remember to credit the original author.
