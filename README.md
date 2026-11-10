# Stock Portfolio Analysis — High School Project

My first finance + programming project, built in my **second year of high school** (2023) as a group project.

We picked 5 stocks (Coca-Cola Consolidated, Nestlé, Ferrari, Ralph Lauren, Juventus), downloaded their historical prices with `yfinance`, and:

- plotted price history
- found max closing prices over a 420-day window
- simulated a portfolio with a custom budget and allocation
- computed basic statistics (mean, mode, standard deviation)

Originally written in Google Colab, later cleaned up to run locally in Jupyter.

> `dati.xlsx` contains **simulated** prices for offline use; the notebook can also fetch real data via yfinance.

## Run

```bash
pip install -r requirements.txt
jupyter lab portfolio_analysis.ipynb
```
