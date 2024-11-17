# Classes

Each class should be named in PascalCase and have a basic docstring describing it along with listing its implemented classes, properties, and methods. If one of the categories would be empty, omit it.

```python
class Range(Numbers):
    """A class representing a range of float values.
    
    Implements:
        Numbers
    
    Properties:
        min_val (float):
            The minimum float value of the range.
        max_val (float):
            The maximum float value of the range.
            
    Methods:
        normalize(val: float) -> float:
            Places the value on a 0-1 range between the class's min and max values, inclusive.
        contains(val: float) -> bool:
            Checks if the value is within the range.
        clip(val: float) -> float:
            Clips the value to the range. If the value is less than the minimum, the minimum is returned. If the value
            is greater than the maximum, the maximum is returned.
        interpolate(scalar: float) -> float:
            Interpolates a value from 0-1 between the min and max values of the range.
    """
```

