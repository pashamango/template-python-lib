# template-python-lib

Fleet template: Python library / service. Created via **Use this template**.

**When instantiating:** rename the package in `pyproject.toml` and `src/`,
rewrite this README, replace the placeholder in `.well-known/agent-card.json`.

## Purpose

_One paragraph: what this library/service does and why it exists._

## Install

```sh
pip install -e '.[dev]'
```

## Usage

```python
from mylib import hello
print(hello("fleet"))
```

## Tests

```sh
pytest
```

## Layout

```
src/mylib/    library code (rename the package on instantiation)
tests/        pytest suites
.well-known/agent-card.json   agent-readable repo card
```

## Secrets

Never commit secrets. Copy `.env.example` to `.env` (git-ignored).

## License

MIT — see [LICENSE](LICENSE).
