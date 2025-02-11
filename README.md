# Commodity and Financial Strategies Analysis

This project aims to explore the relationship between commodity markets (such as Gold, Crude Oil, and Copper) and major financial markets (such as the S&P 500) using data analysis techniques. It demonstrates the interplay between international affairs, raw materials, and financial strategies.

## Project Background

In the current global economic environment, commodity prices are closely linked to financial markets. This project allows you to:
- Retrieve historical price data for various assets.
- Calculate daily returns for each asset.
- Analyze the correlations between different assets.
- Visualize price trends and correlation heatmaps.

## Features

- **Data Retrieval:** Uses [yfinance](https://pypi.org/project/yfinance/) to download historical data from Yahoo Finance.
- **Data Processing:** Utilizes [pandas](https://pandas.pydata.org/) and [numpy](https://numpy.org/) for data manipulation and calculating daily returns.
- **Data Visualization:** Employs [matplotlib](https://matplotlib.org/) to plot historical price charts and [seaborn](https://seaborn.pydata.org/) to generate a correlation heatmap of daily returns.

## Installation

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/your-username/Commodity-and-Financial-Strategies-Analysis.git
    cd Commodity-and-Financial-Strategies-Analysis
    ```

2. **Install Required Dependencies:**  
   It is recommended to use a virtual environment.
    ```bash
    pip install yfinance pandas numpy matplotlib seaborn
    ```

   Alternatively, if you have a `requirements.txt` file, install the dependencies by running:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Run the main script from the terminal:
```bash
python analysis.py
