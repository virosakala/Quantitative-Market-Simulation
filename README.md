# Quantitative Market Simulation: Stochastic Volatility Model

## Objective
This project models the stochastic nature of asset pricing utilising random walk theory. The objective is to demonstrate the application of standard normal distribution in simulating market volatility and predicting theoretical asset price paths over a 100-day trading period.

## Methodology & Technical Stack
The simulation bypasses emotional market narratives to construct a purely mathematical baseline for asset variance.
* **Language:** Python 3
* **Data Structuring:** `pandas` (DataFrame construction and statistical extraction)
* **Mathematical Operations:** `numpy` (Random seed generation, normal distribution scaling, cumulative sums)
* **Visualisation:** `matplotlib` (Time-series rendering)

## Key Execution Steps
1. **Data Generation:** Simulated daily percentage changes using `numpy.random.normal` (mean = 0, standard deviation = 1).
2. **Path Calculation:** Applied cumulative sum functions to track the continuous price evolution from the baseline.
3. **Statistical Extraction:** Generated a foundational summary of variance (mean, min, max, std) via Pandas.
4. **Visualisation:** Plotted the 100-day trajectory to visually isolate the stochastic drift.

## Market Application
This foundational architecture is utilised in quantitative finance to pressure-test risk models, price derivatives, and forecast theoretical drawdowns without risking live capital.
