# pyproject

Example python project

## Getting Started

- [rtx install](https://github.com/jdxcode/rtx#installation)
- `rtx install python@3.11`
- `pip install pre-commit poetry python-dotenv`
- `pre-commit install`
- `dotenv run poetry install`
- `dotenv run poetry shell`

## .env

Configuration file that lets you customize your individual working environment variables.
Use [dotenv](https://github.com/theskumar/python-dotenv) tool to pool them into your shell

## .editorconfig

[EditorConfig](https://editorconfig.org/) helps maintain consistent coding styles for multiple developers working on the same project across various editors and IDEs.
In order for it to work, you need to install your IDE plugin: https://editorconfig.org/#pre-installed

## .pre-commit-config.yaml

Configuration file for `pre-commit` tool, that is used to run useful git hook scripts before git commits.
In order for it to work, you need `pre-commit` to be installed: https://pre-commit.com/#install

## .tool-versions

When you `cd` into a directory containing a `.tool-versions` file, `rtx` will automatically set the appropriate tool versions in PATH.

In order for it to work, you need [rtx] to be installed: https://github.com/jdxcode/rtx#installation

## pyproject.toml

Configuration file that contains build system requirements and information, which are used by pip to build the package: https://pip.pypa.io/en/stable/reference/build-system/pyproject-toml/

This project is using `pyproject.toml` to primarily manage dependencies using `poetry` tool: https://python-poetry.org/docs/
