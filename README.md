# Challenge3


# Crypto Arbitrage

This is a python command-line interface application that allows users to import, clean, and analyze data from two bitcoin exchange platform Bitstamp and Coinbase for arbitrage opportunities. The application works by taking in DataFrames from 'bitstamp.csv' and 'coinbase.csv'. It then filters out any null values, visualizes results in a line and box plots, and then calculates the potential profit minus the cost, and makes decisions on buying and selling bitcoins almost simultaneously between the two platforms. This particular CLI app focus on three individual days from the 'early', 'middle' and 'late' part of Timestamp to zoom in on the results for a more close-up data analysis. 

---

## Technologies

This project leverages Python 3.7 with the following packages and dependencies:

* [pandas](https://pandas.pydata.org/) - An open-source data analysis and manipulation tool.

* [pathlib](https://docs.python.org/3/library/pathlib.html) - Used to identify a file using absolute or relative path. 

* [%matplotlib inline](https://pandas.pydata.org/pandas-docs/stable/user_guide/visualization.html) - Tells Jupyter to create the plot inline with the code in the notebook.


---

## Installation Guide

Python 3.7, GitBash, and JupyterLab are required to be installed before running the application.

---

## Usage

To use the loan qualifier application simply clone the repository and run the **crypto_arbitrage.ipynb** with:

```python
python crypto_arbitrage.ipynb
```

Attached screenshots below show the data analysis process using 'early' data as an example.

![Plot Overlay For January 2018](images/jan_2018_overlay.PNG)

![Box Plot for Arbitrage Spread Middle](images/box_plot_middle.PNG)


---

## Contributors

Brought to you by Trilogy and Christine Guo (www.linkedin.com/in/christine-guo)

---

## License

NoNe
