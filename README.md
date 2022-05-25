# Gold-Signal
A just for fun project to remind me with python


## Strategy
1. Use 21, 50, and 200 moving average in 5-min timeframe
2. Use RSI 14 to look for any divergence.
3. Enter if: Price do not smoosh to all MAs, MA signals (buy or sell), No RSI divergence, and there is an engulfing candle
4. Exit if: RSI divergence and price is over/under MA21.
5. Use MACD to also determine if SMAs are not overlaps.

## Buy When:
1. Enter at green triangle when all SMA lines are not smoosh together.
2. TP at nearish resistance zone.
3. SL 5 pips below SMA 50 line.
4. Consider exit at black dot (it represent RSI divergence)

## Sell When:
1. Enter at red triangle when all SMA lines are not smoosh together.
2. TP at nearish support zone.
3. SL 5 pips above SMA 50 line.
4. Consider exit at black dot (it represent RSI divergence)
