# IDS706-DE-Wk1
IDS706 python template

[![Python Template for IDS706](https://github.com/Parautilitarian/IDS706-DE-Wk1/actions/workflows/main.yml/badge.svg)](https://github.com/Parautilitarian/IDS706-DE-Wk1/actions/workflows/main.yml)


# IDS-706 Week 1 Python Template

Starter template for **IDS 706 Data Engineering Systems** projects. Includes Python setup, Makefile automation, unit tests, and CI with GitHub Actions.

---

## Setup

## Local

git clone <repo-url>
cd IDS-706-week-1-template
python3 -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt


## dev container
Create a repo from this template.
Open in VS Code → “Reopen in Container”.
Dev environment builds automatically.

## Usage
Common Makefile commands:
```bash
make install   # install deps
make format    # format with Black
make lint      # lint with flake8
make test      # run pytest
make all       # run all steps
```
Example:
```bash
make all
```
Example
```python
from hello import say_hello, add
print(say_hello("Annie"))  # "Hello, Annie, welcome to Data Engineering Systems (IDS 706)!"
print(add(2, 3))           # 5
Run tests:
make test
```
## CI
GitHub Actions runs linting and tests automatically on each push.


