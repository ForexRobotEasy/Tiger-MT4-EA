# Tiger MT4 EA ReadMe File

## Introduction
Thank you for choosing Tiger MT4 EA! This expert advisor has been developed by the Forex Robot Easy Team and is designed to optimize forex trading through grid trading strategies. This ReadMe file provides an overview of the code and explains how the expert advisor works.

Please note that ForexRobotEasy is not the official developer of this product. We are only showcasing a sample code that can work as described in the official product. For detailed reviews and trading results of Tiger MT4 EA, please visit the official developer's website at [https://forexroboteasy.com/forex-robot-review/tiger-mt4-ea-review-optimize-forex-with-grid-trading/](https://forexroboteasy.com/forex-robot-review/tiger-mt4-ea-review-optimize-forex-with-grid-trading/).

## Code Description
The Tiger MT4 EA code is written in MQL5 language and is designed to be used in the MetaTrader 4 platform. Below is a detailed description of the code:

### Input Parameters
The expert advisor allows you to customize certain parameters to suit your trading preferences. These input parameters include:

- `lotSize`: Specifies the lot size for each trade.
- `gridSpacing`: Determines the distance between each grid level.
- `maxOrders`: Sets the maximum number of orders to open.
- `magicNumber`: Assigns a unique magic number to identify trades.

### Expert Initialization
The `OnInit` function is responsible for initializing the expert advisor. It sets the magic number using the `ExpertMagicNumber` function.

### Expert Deinitialization
The `OnDeinit` function is called when the expert advisor is being removed from the chart. It can be used to perform any necessary cleanup tasks.

### Expert Tick
The `OnTick` function is the main function that is executed on every tick. It checks if the current price is within the grid spacing and opens new trades at each grid level.

The function performs the following steps:

1. Retrieves the current price using `SymbolInfoDouble` function.
2. Calculates the grid level based on the current price and grid spacing.
3. Opens buy and sell trades at each grid level using `OrderSend` function.
4. Checks if the orders were successfully opened and handles successful trades.

## Product Description
Tiger MT4 EA is an expert advisor developed by the Forex Robot Easy Team. It utilizes grid trading strategies to optimize forex trading. The expert advisor allows you to customize parameters such as lot size, grid spacing, and maximum number of orders to suit your trading preferences.

Please note that ForexRobotEasy is not the official developer of this product. We only showcase a sample code that can work as described in the official product. For detailed reviews and trading results of Tiger MT4 EA, please visit the official developer's website at [https://forexroboteasy.com/forex-robot-review/tiger-mt4-ea-review-optimize-forex-with-grid-trading/](https://forexroboteasy.com/forex-robot-review/tiger-mt4-ea-review-optimize-forex-with-grid-trading/).

## Backlink and Official Developer
For detailed reviews and trading results of Tiger MT4 EA, please visit the official developer's website at [https://forexroboteasy.com/forex-robot-review/tiger-mt4-ea-review-optimize-forex-with-grid-trading/](https://forexroboteasy.com/forex-robot-review/tiger-mt4-ea-review-optimize-forex-with-grid-trading/). Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in the product. To find the official developer of Tiger MT4 EA, please use MQL5.
