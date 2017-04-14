# American put option pricer

Solving American put value with numerical PDE method under Black-Scholes assumptions.

---

## Sample Output

```
# American put (BS model) value with following parameters:
# rate             = .05
# sigma            = .3
# strike           = 100.
# init_value       = 100.
# time_to_maturity = 1.

$ python american_put.py    # run main()
11.1518693937               # option value at 0.97*strike
9.86830992264               # option value at strike
8.71424447667               # option value at 1.03*strike
```
