# LT Super Trend

The LT Super Trend is a custom indicator designed to identify trends in the financial markets. It is developed by [Forex Robot Easy Team](https://forexroboteasy.com), a third-party developer in the trading community. Please note that ForexRobotEasy is not the official developer of this product, but we provide a sample code that can work as described in this product.

## Indicator Parameters

The LT Super Trend indicator has the following input parameters:

- `SuperTrendPeriod`: The period used to calculate the Super Trend indicator. Default value is 10.
- `SuperTrendMultiplier`: The multiplier used to calculate the Super Trend indicator. Default value is 2.0.

## Indicator Functionality

The LT Super Trend indicator uses the Average True Range (ATR) to calculate the upper and lower bands of the trend. It determines whether the market is in a bullish or bearish trend based on the price action in relation to these bands.

The indicator works as follows:

1. It initializes the indicator buffers and sets the styles and colors for the upper and lower trend lines.
2. It initializes the trend variables for bullish and bearish trends.
3. It calculates the Super Trend for each bar in the price data.
4. If the closing price is above the previous Super Trend upper band or if the previous closing price was above the previous Super Trend upper band and the current closing price is below or equal to the previous upper band, it indicates a bullish trend. The Super Trend upper and lower bands are calculated accordingly.
5. If the closing price is below the previous Super Trend lower band or if the previous closing price was below the previous Super Trend lower band and the current closing price is above or equal to the previous lower band, it indicates a bearish trend. The Super Trend upper and lower bands are calculated accordingly.
6. If none of the above conditions are met, the Super Trend upper and lower bands and the trend variables are set to their previous values.

## Usage

To use the LT Super Trend indicator in your trading strategy, follow these steps:

1. Install the indicator in your MetaTrader 5 platform.
2. Set the desired values for the `SuperTrendPeriod` and `SuperTrendMultiplier` input parameters.
3. Use the Super Trend upper and lower bands, along with the trend variables, to identify and trade bullish and bearish trends in the market.

## Product Description

The LT Super Trend is a powerful indicator that provides valuable insights into market trends. It helps traders identify potential entry and exit points, allowing them to make informed trading decisions.

Key Features:
- Easy to use and customizable input parameters.
- Accurate trend identification based on price action and ATR.
- Clear visualization of the Super Trend upper and lower bands.
- Bullish and bearish trend confirmation with trend variables.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/lt-super-trend-forex-software-unbiased-review-and-results/). Please note that ForexRobotEasy is not the official developer of this product. To find the official developer of this product, please visit the MQL5 marketplace.

Take your trading to the next level with the LT Super Trend indicator. Start using it in your trading strategy today and experience the benefits of accurate trend identification.
