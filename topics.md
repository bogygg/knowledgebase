# Python
## Python Standard Library
* `math`

_get pi number from the math module_
```python
from math import pi

radius = float(input("Enter the radius: "))
print("The area is", pi * radius ** 2)
```

_get the square root function from the math module_
```python
from math import sqrt

number = float(input("Enter the number: "))
print("The suare root is", sqrt(number))
```
* `random`
```python
from random import randint
number = randint(1, 10)
print(number)
```
* `datetime`

The full list of format codes:

[Official Python Documentation](https://docs.python.org/3/library/datetime.html#strftime-and-strptime-format-codes)
```python
from datetime import datetime
now = datetime.now()
# now.year
# now.month
# now.hour

print("Current date and time:", now.strftime("%d.%m.%y %H:%M"))
```
