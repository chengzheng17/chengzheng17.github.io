---
layout:     post
title:      Carry and Relative Value Trades
subtitle:   Interest Rate Market by Siddhartha Jha
date:       2019-06-24
author:     Zcc
header-img: img/post-bg-cook.jpg
catalog: true
tags:
    - Fixed Income
---

> * When the Fed is on hold, rates and curves may be rangebound for a long period
> * Carry trades and relative value trades are important where the main motivation is **not to** take market view  


## CARRY TRADES

The aim of a carry trade is to earn income from holding an asset. The profit and loss (P/L) of an asset equals: 

> P/L = cash carry (from holding) + MTM P/L (pricing movement)

We try to minimize the threat of negative MTM P/L that offsets gains from the asset's net income. So that the carry trades work best during the periods when Fed anchored short-term Interest Rate or market volatility is low.  

P/L to volatility (risk) is a relevant metric for attractiveness of a trade. For example in carry trade, a simple metric is carry-to-volatility (carry-to-risk). Risk can be measures by long-term standard deviation of yield changes for fixed income instruments (matche the carry period or short-term period).  

For carry trades involving bonds, it's common that: 
> carry = cash carry + rolldown 
But carry trades may involve no actual income inflow, like when constructing carry trades using futures or forward starting trades. So the entire carry becomes the **rolldown**. The motivation is that: 
> We want asset to age and give us gain. We want to minimize price changes stemming from other factors.  

Pure carry can be fixed using a term repo rate. No certain machanism can lock the rolldown (unstable). 

## CARRY TRADE SETUP AND EVALUATION

> In late 2009, the Fed's target rate near zero and the 2-year yield near 0.9%. Term-structure is upward sloping.

Buying a Treasury bond or reveiving fix in a swap is positive carry. For example 2-year Treasury bond, the carry and rolldown combined over 3M period was about 20bps quarterly (80bps per annum). The annualized daily volatility of 2-year yield is 84bps.  

Eurodollar futures is common for a carry trade, attempting to exploit rolldown rather than pure income carry. Often the annualized carry-to-volatility ratio is used for a quick comparison between different carry trades.  

Carry trades don't have to be outright trades because of significant volatility which at times erase all the embedded carry from negative MTM P/L. For example: 
> Consider the EDM1/EDZ2 curve trade from the Eurodollar contract  

The carry for EDM1 and EDZ2 are 10.5bps and 18.5 bps repectively. We can short EDM1 and long EDZ2 to get carry and reduce volatility. Sell 0.94 risk weight on EDM1 and buy 1 risk weight on EDZ2. 

> * carry = 1 * 18.5 - 0.95 * 10.5 = 8.6bps
> * volatility of EDZ2-0.94EDM1 is 2.7bps/day
> * annualized carry-to-volatility ratio is 0.82, higher than outright  

## PITFALL OF THE CARRY TRADE

One advantage of carry trade is that, the trade needs a certain threshold of adverse price movement before investors actually start losing money on the trade. But the apparant cushion can be misleading and cause bad result.  

When market is rangebounded, investors may crowd into the same carry trades with high carry and low volatility (market's favorite carry trade). It's from investors' search for returns since rangebound markets don't offer many profit opportunity from directional movements.  

A small spark from perhaps an unfavorable piece of news or a hedger compelled to initiate the opposite trade in the market can provide just the impetus needed to scare carry traders. The carry trade escape will press the market lower, until a large number of investors have abandoned it.  

> For example in Jan 2009, Fed targeted to near zero and 2-year Treasury was nearly 1%. Rate was expected to remain there for an extended period of time due to structural weaknesses in the economy.

The key point is that, carry trade risk metric is almost always backward-looking. We should keep an eye on the market situation. Two clues can be used to better judge how crowded a trade is: 
1. Position data where it's available. For U.S. market, the futures exchanges release weekly the positioning data;
2. When correlations between these seemingly unrelated trades increase rapidly, it is a sign of the same global flows chasing the same carry trades.  

Crowded trades tend to display muted moves with regard to favorable news or favorable movements in other markets but oversize moves in the face of negative news. This will tend to happen because there are already too many long positions in the market and there is little appetite to add more on the back of favorable news; unfavorable news, however, leads investors to the exits.  

Although it may seem obvious, often such signs are more subtle but can be helpful in judging how long to hold carry trades and, one hopes, exit out of them before others try to.

## CARRY-EFFICIENT DIRECTIONAL TRADES

> * At times, a trading take advantage of market view could have negative carry
> * "Carry-Efficient Trades" refers to trades with reduced negative carry

Take Jan 2009 2-year Treasury for example, if a trader wanted to do the mirror trade, he would loss 20bps quarterly without market even moving. So trader wanted a trade: having exposure to 2-year Treasury yield rising, but reducing the negative carry.  

In general, a criterion is to measure a trade's correlation with our market view. For example, instead of short outright 2-year Treasury, trade can be done by betting 2s/5s flatten.  
> selling 2-year Treasury + buying 30% risk weight on the 5-year Treasury

## RELATIVE VALUE TRADES

> Relative value trades intend to exploit dislocated market relationships

Ideally, relative value trades are placed without taking views on the markets. It's statistical/fundamental driven. The goal is to find a relationship between two or more market variables that is away from its long-run average.  
> * bond A @5% yield, bond B @4.5 yield, the spread is 50bps
> * Average spread is 20bps and historical spread volatility is very low
> * long bond A and short bond B

As for pitfalls, it's similar to carry trades. If the trade is crowded, a rapid exit by investors may only cause the dislocation to get worse. If dislocated relationship do not revert back for long periods of time, it indicates the changes of underlying fundamentals, causing a failed relative value trades. 

## SETTING UP RELATIVE VALUE TRADES

> **Pure relative value**: trades with little broad market exposure

Investors should weight the different instruments by ensuring that weights reflect the relative volatility and sensitivity of each instrument, in such way that there's minimal exposure to the broader market.  

The important point here is the thought process behind selection of the relative value trade, calculating appropriate weights for the legs, and backtesting the relative value strategies. Regression can be used to determine market variable exposures (beta). 

> For a common example, the U.S. Treasury butterfly trades  
> long 5-year, short 2-year & 5-year or short 5-year, long 2-year & 5-year  
> 5-year is **body**, 2-year & 5-year are **wings**

Many techniques are used to weight body and wings, in order to protect trades from unwanted market exposure. 

## TREASURY BOND RELATIVE VALUE-PAR CURVE

## OTHER TREASURY RELATIVE VALUE TRADES

## SUMMARY




