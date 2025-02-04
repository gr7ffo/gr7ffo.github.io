---
title: 'Fun with UV'
date: 2025-02-14
permalink: /posts/2025/02/04/uv/
tags:
  - uv
  - python
  - til
---

# Fun with uv

## Useful snippets for using uv

In 'normal' Python scripts you could use for example

```python
# /// script
# requires-python = ">=3.11"
# dependencies = [
#   "pandas",
# ]
# ///
import pandas as pd


print(pd.__version__)

```

This specifies a certain Python version, in this case 3.11+ and automatically imports dependencies. One could run this script using `uv run script.py` and `uv` does all the magic of setting things up.

## Useful snippts for using uvx

For using the `uvx` one could for example use the command

```bash
uvx --from jupyter-core --with pandas --with numpy --with matplotlib jupyter lab
```

to start a fresh session of [Jupyter Lab](https://jupyter.org/install) for Data Scouting a fresh directory.
