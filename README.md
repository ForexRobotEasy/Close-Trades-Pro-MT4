# Close Trades Pro MT4

**Close Trades Pro MT4** is an expert advisor for MetaTrader 4 that allows you to automatically close trades based on specified conditions. This expert advisor is designed to revolutionize your forex trading by providing a convenient and efficient way to manage your trades.

## Features

- Automatic closure of trades based on specified conditions
- Customizable profit target and stop loss levels
- Time-based closure of trades
- Real-time monitoring of trade performance
- Ability to calculate total profit and loss

## How it Works

The expert advisor uses the `OnTick` function to check if it's time to update trade information. It updates the total profit and loss every 5 seconds by looping through all open positions and calculating the profit/loss for each position. The total profit and loss are then stored in global variables.

The expert advisor also checks for closure conditions and closes positions accordingly. It loops through all open positions and checks if the position meets the closure conditions, which include a profit target of 100, a stop loss of -100, and a time duration of 1 hour. If a position meets these conditions, it is closed using the `PositionClose` function.

In addition to these functions, the expert advisor includes custom functions such as `CalculateProfitLoss` and `MonitorTrades`. The `CalculateProfitLoss` function calculates the total profit and loss by looping through all open positions and adding the profit/loss for each position. The `MonitorTrades` function provides real-time monitoring of trade performance by printing information about each open position, including profit, loss, and open time.

## Product Description

**Close Trades Pro MT4** is a powerful expert advisor that revolutionizes your forex trading experience. With its automatic trade closure feature, you can easily set profit targets and stop losses, ensuring that your trades are closed at the desired levels. The expert advisor also allows you to schedule time-based closures, giving you full control over your trading strategy.

Notable features of **Close Trades Pro MT4** include customizable profit target and stop loss levels, real-time monitoring of trade performance, and the ability to calculate total profit and loss. These features provide you with valuable insights into your trading performance and help you make informed decisions.

Please note that ForexRobotEasy is not the official developer of this product. We are providing this sample code to demonstrate how the expert advisor works, based on the information provided in the product review by [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/close-trades-pro-mt4-review-revolutionize-your-forex-trading-now/). To find the official developer of this product, please refer to MQL5.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/close-trades-pro-mt4-review-revolutionize-your-forex-trading-now/).

**Forex Robot Easy Team**  
[https://forexroboteasy.com](https://forexroboteasy.com)
