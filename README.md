# Sharp Stock


A simple Python library to calculate the Sharpe Ratio of a stock.

## How to use

```
pip install sharpstock
```

```python
from sharpstock.sharpe_ratio import calculate_sharpe_ratio
df = pd.read_csv('data.csv')
calculate_sharpe_ratio(df)
```



## Features

- [x] Sharpe Ratio Calculation
- [ ] Calculate Sharpe Ratio for multiple stocks
