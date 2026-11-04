# GOLD INSIGHT INDIA
### Interactive Gold Price Analysis Dashboard

## Project Overview
GOLD INSIGHT INDIA is an interactive Python dashboard for exploring historical international gold prices. It allows users to select a year range, convert prices into an approximate INR-per-10-grams value, choose a moving-average period, and display selected visualizations.

The project is designed to run in **Google Colab**.

## Project Team
Add the GitHub usernames of all four team members below:

- **Team member 1:** @your-github-username
- **Team member 2:** @teammate-username
- **Team member 3:** @teammate-username
- **Team member 4:** @teammate-username

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- ipywidgets
- Google Colab

## Dataset
The dashboard loads monthly gold-price data from:

<https://datahub.io/core/gold-prices/r/monthly.csv>

The source data represents international gold prices in **US dollars per troy ounce**.

## Dashboard Features
- Select the start year and end year.
- Enter an editable USD-to-INR exchange rate.
- Select no moving average or a 3-, 6-, 12-, or 24-month moving average.
- Select or hide individual graphs, or select all graphs.
- View summary statistics for the selected period.

## Visualizations
1. **Gold Price Trend (Line Graph):** Displays the converted gold price over time and, when selected, its moving average.
2. **Average Gold Price by Month (Bar Graph):** Compares average prices for January through December over the selected period.
3. **Gold Price Distribution Over Time (Scatter Graph):** Displays individual monthly price observations over time.
4. **Correlation Analysis (Heatmap):** Displays correlations between gold price and derived features such as monthly returns, moving averages, and rolling volatility.

## Summary Metrics
- Latest price in the selected period
- Average price
- Maximum price
- Percentage change from the first to the last observation in the selected period

## How to Run
1. Download `Gold_Insight_India.ipynb` from this repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Upload the notebook to Colab.
4. Run the notebook cells from top to bottom.
5. Use the dashboard controls to explore the data.

## Install Dependencies
If running in a local Python environment, install the packages listed in `requirements.txt`:

```bash
pip install -r requirements.txt
```

For Google Colab, the listed libraries are generally available already. If a package is missing, install it in a notebook cell.

## Important Notes and Limitations
- The dashboard applies one user-entered USD-to-INR exchange rate uniformly to the selected historical period. It does not use historical exchange rates.
- The INR-per-10-grams figure is an approximate mathematical conversion from international gold prices. It is **not** the actual historical Indian retail gold price.
- The conversion does not include Indian import duties, GST, local premiums, or jewellery making charges.
- Correlation indicates statistical association, not causation.
- The dashboard visualizes historical data; it does not train a machine-learning model or forecast future gold prices.

---
**Project Title:** GOLD INSIGHT INDIA — Interactive Gold Price Analysis Dashboard
