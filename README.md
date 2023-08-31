# Analyzing_trading_cost / implementation shortfall
Evaluate trading strategies based on quoted spreads, effective spreads and realized spreads to calculate the trading cost
We will always assume that our random order is an order to buy stock 
  i.e  Implementation Shortfall (buy) = (Actual Price - Theory Price)/Theory Price
        Realized Spreads = price(t) - Midquote(t+n)
        Quoted Spread = Ask price - Bid Price
        Effective spread = 2|trade_price -((ask + bid)/2)|
