# Rain Calculator

This Python script provides a function to calculate how much rainwater can be retained after it rains given the heights of walls.

## Usage

To use this script, follow these steps:

1. Ensure you have Python 3 installed on your system.
2. Copy the code into a Python file.
3. Use the `rain` function, passing a list of wall heights as an argument.

Example:

```python
from rain_calculator import rain

walls = [3, 0, 0, 2, 0, 4]
water_retained = rain(walls)
print("Water retained after rain:", water_retained)

