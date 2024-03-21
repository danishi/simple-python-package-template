# Simple Python package template

## Setup

```shell
python -m venv venv
. venv/bin/activate
```

## Install
```shell
pip install -e .[dev]
pip list | grep mypackage
python
>>> import mypackage
>>> print(str(mypackage.main.add_one(1)))
2
```

## Uninstall
```shell
pip uninstall mypackage
```

## Test
```shell
pytest
```

## Remote install
```shell
pip install git+https://github.com/danishi/simple-python-package-template.git@v0.0.1
```

