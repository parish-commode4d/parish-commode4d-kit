# parish-commode4d-kit

Count lines, words and characters, with totals.

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m parish_commode4d_kit.cli --help
```

```python
from parish_commode4d_kit.core import ParishCommode4dTool

tool = ParishCommode4dTool()
print(tool)
```

## Layout

```
parish_commode4d_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 parish-commode4d
