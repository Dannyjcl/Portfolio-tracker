
# Portfolio Tracker

An AI-powered personal investment portfolio tracker built with Python and the Anthropic API.

## What It Does

- Fetches live prices for all stock and crypto positions using yfinance
- Automatically updates a formatted Excel portfolio tracker
- Generates a PowerPoint summary with a portfolio allocation bar chart
- Timestamps every refresh so you know exactly when data was last pulled

## Tech Stack

- Python
- Anthropic Claude API
- yfinance (live market data)
- openpyxl (Excel generation)
- python-pptx (PowerPoint generation)
- matplotlib (charts)
- Jupyter Notebooks / VS Code

## Portfolio Coverage

- Webull equity positions (NVDA, AMZN, BN, GOOGL, SGOL, BMNR, PLTR, MSTR)
- Crypto (BTC)

## How To Use

1. Clone the repo
2. Create a virtual environment and install dependencies
3. Add your Anthropic API key to a `.env` file
4. Open `portfolio_refresh.ipynb`
5. Run all cells to get an updated Excel and PowerPoint summary

## Files

- `portfolio_tracker.ipynb` — development notebook, full build history
- `portfolio_refresh.ipynb` — clean weekly refresh notebook (run this on Sundays)
