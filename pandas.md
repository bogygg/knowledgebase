# Pandas

Reading file `olympics.csv` , skipping 4 first rows

```python
import pandas as pd
df = pd.read_csv("olympics.csv", skiprows=4)
```


Displaying amount of colums and rows
```python
df.shape
```

Adressing colums/specific column
```python
df.columns
df.column name
```

Displaying first 5 rows if empty, can also adress how many to display
```python
df.head()
df.head(10)
```
Last 5 rows if empty, can adress how many to display from end
```python
df.tail()
df.tail(7)
```
Random row if no arguement, amount of random rows can be given
```python
df.sample()
df.sample(5)
```

Creating specific conditions for display
```python
df[(df.Medal =='Gold')&(df.Gender== 'Men')]
```