# Summary

Basically, a repository with hooks pre-commit using:

- `Black`: A Python code formatter
- `Flake8`: A code checker for your Python code
- `isort`: A Python library for sorting imports

## Config files

- `.pre-commit-config.yaml`: Used to configure pre-commit hooks. There are much more [hooks](https://pre-commit.com/hooks.html)
 that can be added.
 - `pyproject.toml`: Settings for black and isort parameters.
 - `.flake8`: Settings for flake8.

## Notes

The settings made here are not 100% in compliance with PEP8. I personally think that 79 characters for a line length are not enough  and rather use 100 instead. 