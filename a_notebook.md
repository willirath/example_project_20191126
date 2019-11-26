---
jupyter:
  jupytext:
    text_representation:
      extension: .md
      format_name: markdown
      format_version: '1.2'
      jupytext_version: 1.3.0
  kernelspec:
    display_name: Python [conda env:climnum]
    language: python
    name: conda-env-climnum-py
---

# Plot random numbers

First, import relevant modules.

```python
%matplotlib inline
import numpy as np
from matplotlib import pyplot as plt
```

Then, plot 1000 pairs of random numbers in the x-y plane.

```python
plt.scatter(
    np.random.normal(size=(1000, )),
    np.random.normal(size=(1000, )),
    alpha=0.2
);
```
