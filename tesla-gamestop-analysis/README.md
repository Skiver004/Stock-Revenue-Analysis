# Tesla and GameStop Stock vs Revenue Analysis

A Jupyter Notebook that extracts historical stock price data using **yfinance** and quarterly revenue via web scraping, then visualises both using **Plotly** interactive charts.

## Contents

| File | Description |
|---|---|
| `analysis.ipynb` | Main notebook with all 6 questions |
| `requirements.txt` | Python dependencies |

## Questions Covered

1. **Q1** — Extract Tesla (TSLA) historical stock data with `yfinance`
2. **Q2** — Scrape Tesla quarterly revenue from Macrotrends
3. **Q3** — Extract GameStop (GME) historical stock data with `yfinance`
4. **Q4** — Scrape GameStop quarterly revenue from Macrotrends
5. **Q5** — Plot Tesla stock price vs revenue dashboard (up to mid-2021)
6. **Q6** — Plot GameStop stock price vs revenue dashboard (up to mid-2021)

## Setup

```bash
pip install -r requirements.txt
jupyter notebook analysis.ipynb
```

## Notes

- Revenue scraping targets [Macrotrends](https://www.macrotrends.net/). If the HTML structure changes, the scraper automatically falls back to `pd.read_html`.
- All charts are interactive Plotly figures rendered inline in the notebook.
