# Module 4 Challenge - Whale Risk-Return Analysis

This is my risk-return analysis of four legendary hedge funds (whales) compared to the S&P 500 to determine the fund with the most investment potential based on their daily returns, standard deviations, Sharpe ratios, and betas. The data used is is a collection of net asset value pricing from Soros Management LLC, Paulson & Co. INC., Tiger Global Management LLC, Berkshire Hathaway INC, and the timestamp-correlated closing prices of the S&P 500:

[Whale Navs and S&P 500 Closing Prices 2015-2020](/Resources/whale_navs.csv)

The analysis begins by looking at the daily return data and calculating the cumulative returns:

![Line graph comparing whale funds and S&P 500 cumulative returns](/Resources/images/cumulative_returns.png)

Then I go on to measure the levels of risk using annualized and rolling standard deviation values:

![Calculation results of whale funds and S&P 500 annualized standard deviations](/Resources/images/annualized_std.png)
![Line graph comparing the 21-day rolling standard deviations of the four whale funds](/Resources/images/21_rolling_std.png)

And finally I draw conclusions of which funds would be a good addition to a portfolio using Sharpe ratios and 60-day rolling betas:

![Line graph comparing Berkshire Hathaway and Tiger Global Management 60-day rolling betas](/Resources/images/berkshire_v_tiger.png)

---

## Technologies

This is a Python 3.7 project ran using a JupyterLab in a conda dev environment. 

The following dependencies are used: 
1. [Jupyter](https://jupyter.org/) - Running code 
2. [Conda](https://github.com/conda/conda) (4.13.0) - Dev environment
3. [Pandas](https://github.com/pandas-dev/pandas) (1.3.5) - Data analysis
4. [Matplotlib](https://github.com/matplotlib/matplotlib) (3.5.1) - Data visualization
5. [Numpy](https://numpy.org/) (1.21.5) - Data calculations + Pandas support


---

## Installation Guide

If you would like to run the program in JupyterLab, install the [Anaconda](https://www.anaconda.com/products/distribution) distribution and run `jupyter lab` in a conda dev environment.


---

## Usage

The Jupyter notebook [risk_return_analysis.ipynb](/risk_return_analysis.ipynb) will provide all steps of the data collection, preparation, and analysis. Data visualizations are shown inline and accompanying analysis responses are provided. 

---

## Contributors

[Ethan Silvas](https://github.com/ethansilvas)

---

## License

This project uses the [GNU General Public License](https://choosealicense.com/licenses/gpl-3.0/)
