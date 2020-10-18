# financial_plan_api_cryp_bond_stocks
## Table of Contents

* General Information
     * Personal financial planner - Assess current portfolio health
     * Long-term retirement planning
     * Short-terms alternatives (5 year and 10 year)

* Libraries and tools
* Folder structure

## Personal financial planner

* The financial health of a given portfolio was prepared with the assumption of a crypto portfolio composed of 1.2 Bitcoin and 5.3 ethereum and an equity portfolio composed of 50 shares of the ETF (SPY) and 200 shares of the bond ETF (AGG).
* The daily close price for the cryptocurrencies were obtained via API url from alternative.me, while the equity daily close were obtained via Alpaca SDK API.
*  

## Libraries and tools

* To complete the Monte Carlo iterations, the MCForecastTools.py was used
* the libraries imported to the analysis: os, requests, pandas, dotenv and alpaca_trade_api  