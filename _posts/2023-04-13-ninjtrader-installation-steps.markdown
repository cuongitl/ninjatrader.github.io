---
layout: post
title: "NinjaTrader Desktop Installation Guide"
date:   2023-04-13 17:07:16 +1100
categories: ninjatrader
description: NinjaTrader Desktop Installation Guide
img: order-filter.jpeg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [ninjatrader, setup]
redirect_from:
  - /ninjatrader/2023/04/13/ninjatrader-setup.html
---
One of the issues that many traders come across is the limits on exchanges especially [Binance][binance].

If you have run across a Filter failure whether it be PRICE_FILTER, LOT_SIZE, MIN_NOTIONAL, MARKET_LOT_SIZE
you know what I mean.

If you haven't seen any of these before then you are bound to sooner or later! When you start running strategies and
calculating percentages, or adding fees you will end up with some prices or quantities with greater precision
than is allowed.

Another complication is that these filters can interact with each other, while you may satisfy the PRICE_FILTER
you may not satisfy the MIN_NOTIONAL etc.

There are a number of other filters, for this post I'm going to focus on the filters related to the Spot market.

### Installation Steps

1/ [Register an account](https://support.ninjatrader.com/s/article/How-Can-I-Get-a-Free-Trial-of-NinjaTrader?language=en_US)

2/ [Register an account](https://support.ninjatrader.com/s/article/How-Can-I-Get-a-Free-Trial-of-NinjaTrader?language=en_US)


### Next Steps

Hopefully this has helped demystify some of the terminology that you will see when interacting with the 
exchange, and you now have some tools to handle price and quantity parameters when trading.


