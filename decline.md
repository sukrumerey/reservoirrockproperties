# Decline Curve Analysis

```python
import numpy as np
import matplotlib.pyplot as plt

qi = 1000
Di = 0.2

t = np.linspace(0,10,100)
q = qi*np.exp(-Di*t)

plt.plot(t,q)
plt.show()
```