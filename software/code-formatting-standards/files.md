# Files

Each file should start with a docstring describing the purpose of the file, followed by its classes and functions, listing only the highest-level members. E.g. you would not list the methods inside a class, merely the class itself.

```python
"""Configuration classes for controller inputs.

Classes:
    AxisConfig:
        Describes the configuration of an axis on a controller.
    ButtonConfig:
        Describes the configuration of a button on a controller.
    ControllerConfig:
        Maps axes and button numbers to specific configurations.
    InputFunction:
        Describes a function and the arguments to be called with it.
        
Functions:
    example_function:
        Example function description sentence.
"""
```

Immediately after the docstring, with up to one blank newline, should be all imports in the file. Externally-sources and custom file imports should be separated by a newline. Avoid \* imports.

<pre class="language-python"><code class="lang-python"><strong>import math
</strong>
from config import ThrusterPWMConfig
from config.enums import ThrusterPositions, ThrusterOrientations
</code></pre>

