# IS218 Test 1 – Python Calculator

**Author:** Thomas Moylan

This project builds a tested Python calculator package using a GitHub issue, branch, and merge workflow.

## Environment

The `.venv` folder is ignored because it contains machine-specific installed packages that anyone can recreate locally. `requirements.txt` is committed so every developer and the CI runner install the exact same dependency versions.


## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
```

## Running Tests

```bash
python -m pytest
```

## Branches

- `setup` — created the virtual environment and installed dependencies
- `addition` — implemented `add(a, b)` and its tests
- `subtraction` — implemented `subtract(a, b)` and its tests
- `delivery` — finalized documentation and verified the full suite

## Example Test

`test_add` in `tests/operations/test_add.py`:
Inputs `2, 3` are passed to `add(a, b)`. The test asserts the returned value equals `5`.