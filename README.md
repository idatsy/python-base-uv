# `uv` Python Template

An alternative to the `poetry` template found [here](https://github.com/idatsy/python-base), with minimal defaults:

* Test suite using `pytest` with `pytest-asyncio` and `pytest-watcher` for TDD
* `loguru` as the default logging solution
* `ruff` and `pyright` configurations for formatting, with strict rules enabled by default to enforce strict typing and correctness
* Default GitHub Actions requiring formatting, linting, and passing tests before merges into `main`
* Makefile with shorthand commands for common tasks

> Run `make help` for a list of available commands.

## Usage

Clone the repo as a template, then find and replace `python-base-uv`, and you're good to go!

