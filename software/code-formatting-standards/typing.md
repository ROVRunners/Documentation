# Typing

When creating variables or functions, you should add typing to it.

You should be as specific as possible. simply writing "dict" would be valid, but including the key and value types is by far preferred, as shown in the below example.

```python
# Variable creation:
frame_thrusters: FrameThrusters = FrameThrusters()

# Function declaration:
def example_function(dictionary_1: dict[str, FrameThrusters],
                     dictionary_2: dict[int, dict[str, list[bool]]]
                     ) -> list[list[list[list[float]]]]
```

Types should be separated by the vertical bar ( | ) if the type could be one of two or three different types.

```python
def example_function(value: int | float = 0.0) -> float | None:
```
