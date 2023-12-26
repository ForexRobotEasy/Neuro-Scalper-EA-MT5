# Neuro Scalper EA MT5 ReadMe File

## Description
Neuro Scalper EA MT5 is an expert advisor designed for automated trading on the MetaTrader 5 platform. It utilizes the NeuroScalper custom indicator to identify trading opportunities and execute trades based on predefined strategies. The EA is developed by the Forex Robot Easy Team and can be downloaded from their website at forexroboteasy.com.

## Installation
To use Neuro Scalper EA MT5, follow the steps below:
1. Download the EA file from the developer's website.
2. Open the MetaTrader 5 platform.
3. Go to 'File' > 'Open Data Folder' to open the data directory.
4. Copy the EA file into the 'MQL5' > 'Experts' folder.
5. Restart the MetaTrader 5 platform.
6. Open the desired chart and attach the EA to the chart.

## Requirements
Neuro Scalper EA MT5 requires the following libraries and functions:
- Trade.mqh library
- NeuroScalper.mqh custom indicator

## Configuration
The EA can be configured by modifying the variables in the code. The following variables can be adjusted:
- `SYMBOL`: The symbol to trade (e.g., 'XAUUSD' for Gold).
- `TIMEFRAME`: The timeframe for trading (e.g., PERIOD_H1 for 1-hour timeframe).
- `lotSize`: The lot size for each trade.
- `stopLoss`: The stop loss level in pips.
- `takeProfit`: The take profit level in pips.

## Usage
Once the EA is attached to a chart, it will start trading based on the predefined strategies. The EA will monitor the NeuroScalper custom indicator for new bar openings. When a new bar opens, the EA will determine the current strategy index and check if there is an open position. If there is an open position, it will be closed. Then, a new trade will be executed based on the selected strategy.

## Trade Events
The EA handles trade events in the `OnTrade()` function. When a position is closed, the trade result (profit/loss) will be printed.

## Removal
To remove the EA from the MetaTrader 5 platform, follow these steps:
1. Close any charts with the EA attached.
2. Go to 'Navigator' > 'Expert Advisors' in the MetaTrader 5 platform.
3. Right-click on the Neuro Scalper EA MT5 and select 'Remove'.
4. Restart the MetaTrader 5 platform.

## Disclaimer
This code is provided as a sample and is not the official development of the Neuro Scalper EA MT5. ForexRobotEasy is not the official developer of this product. For detailed reviews and trading results of the Neuro Scalper EA MT5, please visit the official developer's website or use the MQL5 platform.
