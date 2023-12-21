# RSI Divergence Limited ReadMe File

This code is an indicator for MetaTrader 5 that detects and trades RSI (Relative Strength Index) divergences in the forex market. It was developed by the Forex Robot Easy Team and can be found on their website [forexroboteasy.com](https://forexroboteasy.com).

## Indicator Settings

- RSI_Period: The period for calculating the RSI indicator. Default value is 14.
- Draw_Histogram: Choose between line or histogram drawing for the RSI indicator.

## How it Works

1. The indicator calculates the RSI using the `iRSI` function provided by the MetaTrader 5 platform.
2. It then checks for regular divergence using the `CheckRegularDivergence` function.
3. If regular divergence is detected, the indicator executes the trading logic for regular divergence.
4. It also checks for hidden divergence using the `CheckHiddenDivergence` function.
5. If hidden divergence is detected, the indicator executes the trading logic for hidden divergence.

## Product Description

This code sample is a part of the RSI Divergence Limited product available on [forexroboteasy.com](https://forexroboteasy.com). It is a powerful forex software that helps traders identify and trade RSI divergences in the forex market.

For detailed reviews and trading results of the RSI Divergence Limited product, please visit [here](https://forexroboteasy.com/forex-robot-review/rsi-divergence-limited-review-and-download-the-powerful-forex-software-for-real-results/). Please note that ForexRobotEasy is not the official developer of this product. We are only showcasing a sample code that can work as described in the official product. To find the official developer of this product, please refer to MQL5.
