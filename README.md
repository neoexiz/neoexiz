# n

[![Docs](https://github.com/neoexiz/n/actions/workflows/docs.yml/badge.svg)](https://github.com/neoexiz/n/actions/workflows/docs.yml)
[![Documentation Status](https://readthedocs.org/projects/n/badge/?version=latest)](https://n.readthedocs.io/en/latest/)

A personal knowledge management project built with [Sphinx](https://www.sphinx-doc.org/) and hosted on [Read the Docs](https://readthedocs.org/).

## Build docs locally

```bash
pip install -r docs/requirements.txt
cd docs && make html
# open docs/_build/html/index.html
```

## Format code

Install [pre-commit](https://pre-commit.com/) and run all formatters before committing:

```bash
pip install pre-commit
pre-commit install        # register git hook
pre-commit run --all-files  # run manually
```

Tools configured: **Black**, **isort**, **flake8**, and standard pre-commit hooks.