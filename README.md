# Trading Bot Challenge

## Introduction
This challenge involves writing a bot to trade securities on a mock exchange. The goal is to maximize profit and minimize losses by providing liquidity to marketplace bots. The marketplace includes market-making bots like yours, as well as liquidity demanders.


## Risk Limits and Profit/Loss
- Position Limits: Each security has a position limit (e.g., 100 shares for BOND). Your position in any security must remain within these limits.
- Profit and Loss (PnL): Your PnL is the value of your portfolio. The goal is to maximize PnL across all rounds without performing poorly in any round.

## Available Symbols and Conversion
- BOND: A stock with a fixed fair value of 1000.
- VALBZ/VALE: VALE is an ADR of VALBZ, convertible at a fee of 10.
- GS, MS, WFC: Regular stocks.
- XLF: An ETF convertible into a basket of 3 BOND, 2 GS, 3 MS, and 2 WFC at a fee of 100.
