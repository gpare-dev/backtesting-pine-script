The objective of this project was to develop profitable trading strategies using Pine Script, based on a combination of technical analysis indicators and candlestick patterns, including RSI, Bollinger Bands, candlestick patterns, and support/resistance levels. Pine Script is a programming language specifically designed for trading, and it enables traders to create their custom indicators, backtest trading strategies, and automate trade execution on the TradingView platform.

The first step of the project involved identifying technical indicators and candlestick patterns that have been shown to have predictive power in trading, as well as key levels of support and resistance. The chosen indicators and patterns were then coded into Pine Script, and trading strategies were developed based on them. The strategies were backtested using historical market data to assess their performance across different timeframes and market conditions.

In addition to the technical indicators and candlestick patterns, the backtesting process for this project included using a fixed Risk Reward (RR) ratio of 3. This ratio was chosen because it is a suitable risk management approach for traders who want to manage their risk effectively. By using a fixed RR ratio, the strategies were designed to maximize profits while minimizing losses and maintaining a healthy risk-to-reward ratio.

All backtests were conducted on the TradingView platform, using the last 5,000 bars of data for each timeframe. For example, for a 1-minute timeframe, the backtest covers the last 2 weeks of data, while for a 1-day timeframe, the backtest covers the last 30 years of data. The use of a consistent time frame across all strategies allowed for meaningful comparisons between them and ensured that the results were reliable and consistent.

It is important to note that the project did not involve fine-tuning parameters or "playing" with the historical data to achieve better results. This practice, known as data snooping, can lead to overfitting and unreliable trading strategies. Instead, the focus was on identifying robust trading strategies based on a combination of technical analysis indicators and candlestick patterns, as well as key levels of support and resistance.

Overall, the project aimed to develop profitable trading strategies using Pine Script, based on a combination of technical analysis indicators, candlestick patterns, and key levels of support and resistance. The results were backtested using a fixed RR ratio of 3 and across different timeframes, to ensure that they were reliable and consistent. The findings of this project could be useful for traders and investors looking to optimize their trading strategies and maximize their profits while managing risk effectively.

Below are the net profit results from backtesting various strategies across different timeframes. The analysis provides insights into the performance of each strategy under distinct time intervals. These results are essential for assessing the effectiveness and adaptability of the strategies.


| Strategy | 1m | 3m | 5m | 15m | 30m | 45m | 1h | 2h | 3h | 4h | 1d | 1w |
| ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| Support & Resistance | -2.00% | -5.00% | -7.73% | 0.39% | 8.01% | 6.53% | -17.43% | -5.23% | -14.12% | -9.62% | -20.11% | -2.91% |
| RSI | -1.97% | -1.00% | 1.98% | -6.08% | -7.76% | -19.09% | -29.35% | -13.02 % | -22.48% | -6.82 % | -34.09% | -6.27% |
| Bollinger Bands | -2.00% | -1.02% | 1.98% | -9.68% | -8.68% | -24.95% | 8.78% | -12.72% | 3.45% | -11.38% | -39.77% | -21.57% |
| Marubozu | N/A | -1.99% | -2.96% | 5.89% | -1.80% | 9.87% | 32.51% | 6.28% | 4.47% | 22.14% | 35.78% | 2.21% |
| Hammer & Hanging Man | N/A | N/A | N/A | N/A | N/A | N/A | -1.82% | 1.96% | -4.70% | -0.98% | -13.39% | -5.69% |
| Inverted Hammer & Shooting Star | N/A | -1.99% | 1.97% | -4.91% | 2.92% | 4.78% | 15.05% | 4.18% | -0.64% | 3.86% | 0.79% | 7.90% |
| Engulfing | -1.99% | -1.02% | 0.95% | -2.98% | 4.94% | 14.94% | -30.60% | -8.60% | 2.78% | 18.96% | 1.56% | 9.35% |
| Tweezer | -1.01% | -2.00% | -4.92% | 2.66% | 7.05% | 2.94% | 2.24% | 8.66% | 0.94% | 5.07% | 13.22% | -1.25% |
| Morning Star & Evening Star | N/A | N/A | N/A | -2.94% | 1.67% | -5.18% | -1.81% | -3.05% | -1.44% | 8.18% | -4.81% | 4.89% |
| White Soldiers & Black Crows | -2.03% | -2.00% | -2.03% | -2.06% | 4.02% | 8.17% | -4.21% | 3.00% | N/A | N/A | -1.70% | N/A |