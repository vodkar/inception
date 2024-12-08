# Inception

This is my own python general project template for my personal projects.

## Features

- Python
- Poetry
- Formatters: autopep8, ruff, isort
- Linters: flake8, pylint, wps, ruff
- Type checker: mypy
- pre-commit
- Dockerfile

## Usage

```shell
cookiecutter git@github.com:vodkar/inception.git
```

### Setup for your own

1. Revise `pyproject.toml`. Remove development dependencies, which you don't need to use
2. Revise `.pre-commit-config.yaml`, remove hooks which you don't need to use
