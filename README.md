# Forex OJP Robot

## Overview
The Forex OJP Robot is a trading robot developed by the Forex Robot Easy Team. It is designed to simplify the SMA (Simple Moving Average) trading strategy. This code demonstrates how the robot calculates the SMA and checks for SMA crossovers to generate buy or sell signals.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/forex-ojp-robot-review-simplifying-sma-trading-strategy/). Please note that ForexRobotEasy is not the official developer of this product. We are only showcasing a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

## Code Explanation
### calculateSMA
This function calculates the Simple Moving Average (SMA) for a given time period. It takes an array of prices and the period as input. It iterates over the prices array and calculates the sum of the prices. Finally, it divides the sum by the period to get the SMA.

### isSMACrossover
This function checks if an SMA crossover has occurred. It takes an array of prices, fast SMA period, and slow SMA period as input. It calls the calculateSMA function to calculate the fast and slow SMAs. It then checks if the fast SMA is greater than the slow SMA and if the current price is below the fast SMA and above the slow SMA. If all conditions are met, it returns true indicating a crossover has occurred.

### OnTick
This is the main trading function that is called on every tick. It initializes an array of sample price data. It then calls the isSMACrossover function to check for an SMA crossover of 50-day and 200-day SMAs. If a crossover is detected, it executes a buy or sell order based on the direction of the crossover.

## Usage
To use the Forex OJP Robot, you need to have a trading platform that supports MQL5. You can find the official developer of this product on MQL5. For detailed reviews and trading results, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/forex-ojp-robot-review-simplifying-sma-trading-strategy/).

Please note that this code is just a sample and may need to be customized or integrated with other components to work as a fully functional trading robot.
