---
layout:     post
title:      Interest Rate Futures
subtitle:   Interest Rate Market by Siddhartha Jha
date:       2019-06-30
author:     Zcc
header-img: img/post-bg-cook.jpg
catalog: true
tags:
    - Fixed Income
---

> Forward and futures help to reduce **exposure to volatility**

## BASICS OF FUTURES TRANSACTIONS

An attractive feature of the futures markets is the ability for a buyer or seller to get large exposure to the market with little up-front cash. The leverage can also be achieved by using **repo market**, to buy bonds on margin.

The arbitrage in bond futures market: For the buyer of a futures contract to be indifferent between owning a forward contract or the underlying asset, the price of this forward contract should be the current price of the asset minus the net cost of holding the asset (coupon - repo) between today and the forward date. But reality is not always perfect. 

In the U.S. fixed income space, there're two majot futures contracts: ***Eurodollar futures*** and ***Treasury futures***, both of which are traded on the Chicago Mercantile Exchange (CME). See the symbols system below. 
> 10-year Treasury futures contract expiring in June 2010: YTM0  
> contract + month + last digit of the year

## EURODOLLAR FUTURES

## CONVEXITY (OR FINANCING) BIAS

## CREATING LONGER-DATES ASSETS USING EURODOLLAR FUTURES

## TREASURY FUTURES

> one of the largest futures markets in the world  
> physically settled contracts, using a basket of bonds as deliverable  

When trading Treasury futures, no up-front real Treasury is needed. In order to mitigate the effect of a bottleneck if all sellers tried to deliver the same bond at the same time, CME designed the machanism to allow to delivery a basket of bonds as followed: 

> Deliverable basket of ulter-long contract is a subset of 30-year's  
> Notional: <span>$</span>100,000 for each, with 2y contract having <span>$</span>200,000  
> Quoted in 32nds, e.g. 110-16+ = <span>$</span>100 + <span>$</span>16.5/32  

In the fixed income space, investors are seldom talking about notional and price increments, although they're useful to know for determining contract sizes. What investors care about is whether the yield can exceed NPV, how the profit will be eroded due to yield changes (duration/ convexity).
> To accurately position trades in futures, the metric needs to be **risk exposure to rates**, not notional.  

> Delivery process: 
> * For the 10-year, 30-year, and ultra-long contracts, first and last business day of the delivery month
> * For the 2-year and 5-year contracts, first business day of the delivery month, three business days into to next month, allow newly auctioned bonds at the end of the month to be eligible for the delivery basket. 

Since using a basket of bonds, but futures contract only has one price, conversion factor is required for each deliverable bonds, to convert price between each bonds and standard bonds (6% yield). So **coupon differences** are no longer relevant. 
> * futures invoice price = futures price $\times$ conversion factor + accrued interest
> * It indicates buyer how much to pay *in case* this bond is delivered
> * min(forward price of bond in the basket $\div$ conversion factor) is the **"fair" futures price**

The ***cheapest to deliver bond ("CTD")*** in the basket will be delivered into the contract, which means the futures price will track the bond with the lowest
forward price, after adjusting for conversion factor. 

Based on this assertion, we could get implied yield of the CTD, with the forward start date as the first delivery date of the contract and the maturity date as the CTD's maturity
> * ***implied forward price*** = futures price $\times$ conversion factor + accrued interest
> * forward yield can be calculated using the price/yield formula




