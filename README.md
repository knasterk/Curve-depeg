# Curve-depeg
Predictive modelling of depegging on Cuve.fi.

# Curve and the virtual price

![The curve](https://github.com/knasterk/Curve-depeg/blob/main/fig/single_curve.png "The curve and the virtual price")

![Token ratio and A](https://github.com/knasterk/Curve-depeg/blob/main/fig/curves_A-tokRatio.png "The effect of token ratio and the A parameter")

![The region of stable price](https://github.com/knasterk/Curve-depeg/blob/main/fig/A-tokRatio_vprice.png "Higher A leads to a wider region of stable prices but a sharper drop-off")

## Use
Paths are relative to the working directory.

Search for the best predictive model:
```python
from model import search_cls
best, results = search_cls()
```

Fit, predict and plot:
```python
from model import fit_predict
fit_predict()
```
