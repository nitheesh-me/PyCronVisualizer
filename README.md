# PyCronVisualizer

PyCronVisualizer is a Python package that will help you visualize the occurances of your Cron Jobs.
Inspired from [cronv](https://github.com/takumakanari/cronv)

**Note**: This package is written in _Python3_

## Instructions

### Installation of poetry (Required only once)

Poetry is a tool for dependency management and packaging in Python. It allows you to declare the libraries your project depends on and it will manage (install/update) them for you.

- [Poetry Installation](https://python-poetry.org/docs/#installation)
- [Poetry Update](https://python-poetry.org/docs/#updating-poetry)

```console
$ curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python

$ poetry --version
Poetry version 1.0.0

$ poetry self update
You are using the latest version

$ poetry update

```

### Build the package

```console
$ poetry build
Building pycronvis (<version>)
 - Building sdist
 - Built pycronvis-<version>.tar.gz

 - Building wheel
 - Built pycronvis-<version>-py3-none-any.whl
```
