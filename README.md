# Pairs Trading

I've implemented a Pairs Trading Strategy. Pairs trading is a market neutral trading strategy enabling traders to profit from virtually any market conditions: uptrend, downtrend, or sideways movement.

Please see **Pairs Traiding.ipynb** for the implementation.

## Trading Strategy

We buy 1 **ratio** (buy 1 ADBE stock and sell ratio x MSFT stock) when ratio is low i.e. z < -1, sell 1 ratio (sell 1 ADBE stock and buy ratio x MSFT stock) when it’s high i.e. z > 1 and calculate PnL of these trades.

I find the strategy to be working profitably.
