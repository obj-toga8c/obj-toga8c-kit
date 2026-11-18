# obj-toga8c-kit

Validate JSON files and print a normalized form.

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m obj_toga8c_kit.cli --help
```

```python
from obj_toga8c_kit.core import ObjToga8cTool

tool = ObjToga8cTool()
print(tool)
```

## Layout

```
obj_toga8c_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 obj-toga8c
