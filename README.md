# Bitcoin Market Correlation Analysis

This group project explores the changing relationships between Bitcoin and traditional financial markets, including the S&P 500, NASDAQ, gold, and oil. It combines an ETL pipeline, statistical analysis, and animated interactive visualizations.

**Academic context:** Python Bootcamp group project for the MSc 2 Data Analytics for Business programme at KEDGE Business School (2025–2026).

## Highlights

- Dynamic correlations between Bitcoin and traditional markets
- Bitcoin dominance within the total cryptocurrency market
- Animated linear regressions over time
- Analysis of macroeconomic and cryptocurrency events
- Five interactive Plotly visualizations

## Project structure

```text
.
├── FINAL.ipynb
├── DATASETS/
│   ├── btc_cap_price.csv
│   └── global_crypto_cap.csv
├── OUTPUTS/
│   ├── CSV/Merged_df.csv
│   └── HTML/
│       ├── 1_correlation_matrix.html
│       ├── 2_btc_spx_rolling_corr_dynamic.html
│       ├── 3_btc_dominance_price_animated.html
│       ├── 4_regression_btc_sp500_animated.html
│       └── 5_regression_btc_gold_animated.html
└── requirements.txt
```

## Installation

Prerequisites: Python 3.12 or later, Jupyter Notebook or JupyterLab, and an internet connection for Yahoo Finance data downloads.

```bash
git clone https://github.com/mohitbahukhandi2-ux/Bitcoin-Market-Correlation-analysis.git
cd Bitcoin-Market-Correlation-analysis
pip install -r requirements.txt
```

## Usage

1. Ensure the CSV files are in `DATASETS/`.
2. Start Jupyter with `jupyter notebook FINAL.ipynb`.
3. Run all notebook cells.
4. Open the generated interactive charts in `OUTPUTS/HTML/`.

## Data sources

- **Yahoo Finance (yfinance):** daily asset closing prices
- **Provided CSV files:** Bitcoin price and market-cap history, plus total cryptocurrency market capitalization

## Technologies

`pandas`, `numpy`, `yfinance`, `plotly`, `scipy`, `jupyter`, and `pathlib`.

## Attribution

This work was completed as a group project. The original group repository is [AymaneAshrk/crypto_msc_dab](https://github.com/AymaneAshrk/crypto_msc_dab). This repository preserves the project files for the contributor account.
