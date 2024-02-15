# AU 79 Gold EA MT5

AU 79 Gold EA MT5 is an expert advisor (EA) that trades on the XAUUSD (gold) currency pair. It is designed to open buy and sell positions based on certain price thresholds and close positions when the take profit or stop loss levels are reached.

## Features

- Trades on the XAUUSD currency pair
- Uses a specified lot size for each trade
- Sets a stop loss level to limit potential losses
- Sets a take profit level to secure potential profits
- Monitors the open position and closes it when the take profit or stop loss levels are reached

## How It Works

The EA uses the `OnTick` function to monitor the current price of gold. If there is no open position, it checks if the current price is above a certain threshold to open a buy position or below a certain threshold to open a sell position.

Once a position is opened, the EA continuously checks if the position has reached the take profit or stop loss levels. If either level is reached, the EA closes the position.

The EA also includes the `OnInit` function to enable trading and the `OnDeinit` function to close any open positions before deinitialization.

## Product Description

AU 79 Gold EA MT5 is an expert advisor designed to automate trading on the XAUUSD currency pair. It utilizes a unique strategy to identify potential trading opportunities and open positions based on specific price levels. With the ability to set a customizable lot size, stop loss, and take profit levels, this EA provides traders with the flexibility to manage their risk and maximize their profits.

This EA is developed by Forex Robot Easy Team and is not affiliated with ForexRobotEasy.com. For detailed reviews and trading results of this product, please visit [https://forexroboteasy.com/forex-robot-review/au-79-gold-ea-mt5-review-key-features-analysis/](https://forexroboteasy.com/forex-robot-review/au-79-gold-ea-mt5-review-key-features-analysis/).

Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.
