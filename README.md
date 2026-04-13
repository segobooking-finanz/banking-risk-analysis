# US Banking Risk & Liquidity Analysis 🏦

## Overview
Comprehensive credit risk and liquidity analysis of **255 US banks** 
using real regulatory data from the **FDIC (Federal Deposit Insurance 
Corporation)**. This project applies the same analytical frameworks used 
by financial regulators to assess bank health, capital adequacy and 
risk exposure across 26 US states (2022–2023).

## Business Questions Answered
1. How healthy is the US banking system on key risk indicators?
2. Which banks and states show the highest credit risk?
3. How does bank size affect profitability and risk profile?
4. What percentage of banks are at critical risk of failure?
5. How do ROA, NIM and Tier 1 Capital correlate with each other?

## Dataset
- **Source:** FDIC API (banks.data.fdic.gov) — official US regulatory data
- **Size:** 2,000 records | 255 unique banks | 26 states | 2022–2023
- **Key Metrics:** ROA, NIM, Tier 1 Capital Ratio, Loan Loss Reserves,
  Efficiency Ratio, Coverage Ratio

## Regulatory Framework Applied
This analysis applies **Basel III** standards for capital adequacy:
- **Tier 1 Capital Ratio minimum:** 6% (well-capitalized: >8%)
- **ROA benchmark:** >1% (healthy), 0-1% (adequate), <0% (distressed)
- **NIM benchmark:** 2-4% (typical US bank range)
- **Efficiency Ratio:** <60% (efficient), >80% (inefficient)

## Tools Used
- **Python:** pandas, matplotlib, seaborn, numpy
- **Data Source:** FDIC REST API (real-time regulatory data)
- **Analysis:** Risk scoring, distribution analysis, state comparison
- **Version Control:** Git & GitHub

## Project Structure
