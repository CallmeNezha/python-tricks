﻿# python-tricks

This repo contains every tricks I have learned.

## Interpreter
1. Test sys.modules to detect interpreter shutdown.
```python
if sys.modules is None:
  print("The interpreter is shutting down...")
```
