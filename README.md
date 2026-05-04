# finance-data-science

Demonstrations of standard data-science techniques applied to financial data.
The point is the demonstration: methods that textbooks usually present on
non-financial examples, here applied to series I actually use.

Each notebook is self-contained and uses a unified visual style.

## Contents

| File | Topic | Data |
|---|---|---|
| `01_eda_conditional_probabilities.ipynb` | EDA + conditional distributions: SPX returns conditional on the VIX regime | `^GSPC`, `^VIX` (yfinance, 10y daily) |

## Running

```bash
pip install yfinance pandas numpy matplotlib seaborn
jupyter lab
```
