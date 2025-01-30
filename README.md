# Stock Market & Cryptocurrency Analysis

## Overview  
This project analyzes the relationship between the stock market and cryptocurrency markets, focusing on how they interact and influence each other. Specifically, it explores whether cryptocurrency returns (**Bitcoin and Ethereum**) correlate with the returns of a widely used stock market benchmark, the **SPY ETF**, which tracks the **S&P 500 index**.

If you want to open this file for viewing, a **PDF version** is available. If you'd like to work on it, the **QMD file** can be loaded in **RStudio** for further research.

## Dataset  
The dataset consists of **daily data from 2017-11-09 to 2024-12-10**, covering key variables such as:
- **Daily closing prices**
- **High and low prices**
- **Trading volumes**
- **Smoothed prices** (average of high and low prices)

This timeframe was chosen because it captures significant cryptocurrency adoption milestones while ensuring consistent data availability for all assets.

## Key Variables  
The main outcome variable of interest is the **daily return of Bitcoin (BTC)**, which represents the percentage change in Bitcoin’s value from one day to the next.  

### Predictors & Variables Include:
- **Returns of Bitcoin and Ethereum** (numeric variables)
- **Prices of Bitcoin, Ethereum, and SPY** (numeric variables)
- **Day of the week** (categorical variable) to examine potential weekday effects
- **Trading volumes** for Bitcoin, Ethereum, and SPY to explore correlations (numeric variables)

---

## Personal Motivations & Interest  
I conducted this analysis for two main reasons:

1. **Personal Experience**  
   I actively participate in both the stock and cryptocurrency markets. Naturally, many questions arise about the potential connections between these two markets, and I want to explore those relationships.

2. **Helping Others Transition**  
   Many people are interested in getting started with trading in either the stock or cryptocurrency markets. Some are more familiar with one market than the other—most people are generally more accustomed to the stock market, as it is more established.  
   This analysis serves as a **helpful resource** for anyone looking to transition from one market to the other.  
   Since my target audience includes **beginners or those with little technical experience**, I provide thorough explanations to ensure clarity.

---

## Important Terms to Know  
If you’re unfamiliar with stock or cryptocurrency markets, here are some essential terms:

### 1. Market Capitalization  
**Market capitalization**, or **"market cap"**, is the total market value of an asset or company.  
It is calculated as:  
`Market Cap = Current Price × Total Number of Outstanding Shares/Coins`

Market cap is a **key measure** of an asset’s size and perceived stability in comparison to others.

### 2. Volume  
Volume measures the **total amount of an asset traded** over a given period.  
- **High volume** indicates strong investor interest or market activity.  
- **Low volume** may signal indecision or a lack of engagement.  

In this analysis, **volume helps explore relationships** between market activity in SPY, Bitcoin, and Ethereum.

### 3. Daily Return  
The **daily return** is the percentage change in an asset’s price from one day to the next.

### 4. ETF (Exchange-Traded Fund)  
An **ETF** is a pooled investment security that tracks an index, sector, commodity, or asset. ETFs can be traded on an exchange like a stock.  

- **SPY** is an ETF that mirrors the performance of the **S&P 500 Index**, making it a common benchmark for the U.S. stock market.

---

## How to Use This Project  
- **To view the analysis**, open the **PDF file**.  
- **To modify or conduct further research**, load the **QMD file** into **RStudio**.  

This project aims to offer insights into the intersection between **traditional finance** and **cryptocurrency markets**, providing valuable information for traders, investors, and researchers.

---

- ## Areas for Improvement / Further Development  
(Based on feedback from Professor Linero at **UT Austin**)

The following aspects are **missing, need revision and/or can be improved**:

- **State the number of observations per group** (for binary/categorical variables).
- **Correctly interpret categorical coefficients**
- **Use transformations to improve model fit** (or provide justification if not necessary).
- **Analyze interactions** between variables and their effects (for example, on returns).
- **Further test Hypotheses 2 & 3** with additional statistical measures.

**📌 Author:** Mauricio Garcia 
**📅 Last Updated:** 01/30/2025 
