
# Real Time Bidding (RTB)

This is analyses that applies real time bidding concepts to mobile datasets. 
Rtb can be divided into 8 parts. 

1. RTB System - an introduction to RTB system and what it does. 
2. Auction mechanisms
3. User response estimation
4. Learning to Bid
5. Conversion attribution
6. Pacing Control
7. Targeting and audience expansion
8. Reserve price optimization



# 1. RTB System

Real-Time Bidding is about advertisers buying users directly instead of buying keywords or bundle of ad views. 

# 2. Auction Mechanisms

## Modeling
The auction scheme works as follows. Each bidder $i$ has a private value $v_i$ known only to the bidder. $v_i$ is a bidding value that they will not exceed. If bidder $i$ wins and pays $p_i$, their utility is $v_i - p_i$. The utility is 0 when the bidder loses. Note that the bidders prefer losing than paying more than their value. 

## Strategy 

A strategy for each bidder is a function, a plan for the game. This can be modeled as a normal form game, where these strategies are pure strategies. 

## Strategies and Equilibrium

An equilibrium in auction is profile of strategies $B_1, B_2, . . . , B_n$ such that: 
Dominant strategy equilibrium: each strategy is optimal regardless of what the other strategies are. 
Nash Equilibrium: each strategy is best response to other strategies. 

## 1st Price Auctions
All bidders bid at the same time. The bidder with the highest bid wins and will pay that value

## 2nd Price Auctions
All bidders bid at the same time. The bidder with the highest bid wins and will pay the value of the second highest bid. 



# 3. User Response Estimation

Click Through Rate is a way to predict how many users will click on a specific ad. This is useful for bidders in real time bidding because this is a way to choose which ads to enter bidding process for. 

# Linear Models

Pros: 
1) highly efficient and scalable
2) explore larger feature space and training data

Cons: 
1) Modelling limit: feature independence assumption
2) cannot capture feature interactions unless defining high order combination features

# Non-linear Models

Factorisation machines, gradient boosting decision trees, combined models, deep neural networks. 

# 4. Learning to Bid 

Linear Models and Non Linear Models can be used to learn to bid. Each have their own trade-offs. 

# 5. Conversion Attribution 

Looks at conversions by comparing results from display, search, social, email, affiliate, and offline channels. Still need to understand how this is important for Real Time Bidding

# 6. Pacing Control

Bidders need to know how to bid to stay within their budget. Pacing control can help bidders know when it is optimal to continue bidding, change bidding strategy, or altogether stop bidding. 

# 7. Targeting and Audience Expansion

We can use user segmentation to do targeting. Segment on Long-term Page-view, Short-term Page-view, Long-term Query, or Short-term Query. However, the issue is that different user segmentation algorithms may have different results. Namely, Cluto, K-means, and MinHash can have different results. 

# 8. Reserve Price Optimization 

Reserve price is a dollar amount created by the auctioner that is the minimum that any bidder can bid. This is truly a powerful topic to study in RTB for auctioner because if the reserve price is too high and no one will bid and if the reserve price is too low, the auctioner may not get as high of a profit as the auctioner could have. 


```python

```
