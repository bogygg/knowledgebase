# Pandas

Reading file `olympics.csv` , skipping 4 first rows

```python
import pandas as pd
df = pd.read_csv("olympics.csv", skiprows=4)
```