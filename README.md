# *Risk Return Analysis*
---
We will analyze data of four portfolios along with the S&P 500 to determine the best portfolio to invest into.
This repository contains a Jupyter notebook that contains data preparation, analysis, and visualizations for key risk and return metrics.  
Quantitative analysis will use daily returns, standard deviations, Sharpe ratios, and betas to determine each portfolio's:
 * Performance - do any of the portfolios outperform the broader stock market, the S&P 500?
 * Volatility - box plots will show the volatility of each portfolio and the S&P 500.
 * Risk - analysis using standard deviation and the beta.
 * Risk-return profile - comparison of the potential risk versus return using Sharpe ratios for each portfolio.
 * Portfolio diversification - evaluate how the portfolios react relative to the broader market.  Using rolling betas we will see which investment portfolio to recommend.

---
## Technologies:

The Jupyter file utilizes python 3.7 along with the following libraries:

pandas

numpy

Path

matplotlib

```python
  import pandas as pd
  import numpy as np  
  from pathlib import Path
  %matplotlib inline
```

## Data:

We will analyze a CSV file stored in the Resources folder: whale_navs.csv

The CSV file contain historical market data of four portfolios and the S&P 500 from October 1st, 2014 through September 11th, 2020.

---

## Contributors

kevin-mau

---

## License

MIT