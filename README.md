# Risk_Return_Analysis
Data preparation, analysis, and visualizations for key risk and return metrics.

## Technologies

This project leverages python 3.7 with the following packages:<br>
**[Pandas](https://pandas.pydata.org/)** - For financial statistical calculations<br>
**[Pathlib](https://pypi.org/project/pathlib/)** - For working with CSV files within our project<br>
**[Matplotlib](https://matplotlib.org/)** - For plotting our statistical analyses<br>
**[Numpy](https://numpy.org/)** - For using the square root of trading_days in a year

## Installation Guide

Before running the application first import the following dependencies:

```python
import pandas as pd
from pathlib import Path
%matplotlib inline
import numpy as np
```

## Usage

To use the loan qualifier application simply clone the repository and run the **app.py** with:

```python
python risk_return_analysis.ipynb
```
This application provides the Sharpe Ratios for each of the four funds profiled. This metric tells us the risk-reward aspect of a fund. The higher their Sharpe Ratio, the better risk-reward profile that fund has. The following is the result for the Sharpe Ratios:

![Sharpe Ratios](Images/sharpe_ratios.png)

Finally, we also calculated the rolling beta in order to understand which fund was more conservative in terms of broader market movement. This is a risk metric for diversification. The following is the result of the 2 plots for rolling beta:

Berkshrie Hathaway:

![Berkshire Hathaway Beta](Images/berkshire_beta.png)

Tiger Global Management:

![Tiger GLobal Management Beta](Images/tiger_beta.png)

When it ia all analyzed, we use this information to select the fund portfolio to recommend for investment.