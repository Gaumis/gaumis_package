# Gaumis Package

[![PyPI Version](https://img.shields.io/pypi/v/gaumis-package)](https://pypi.org/project/gaumis-package/)
[![Python Versions](https://img.shields.io/pypi/pyversions/gaumis-package)](https://pypi.org/project/gaumis-package/)
[![License](https://img.shields.io/pypi/l/gaumis-package)](https://pypi.org/project/gaumis-package/)

A simple Python package that does something cool.

## Installation

You can install this package using `pip`:

```bash
pip install gaumis-package

## **Requirements**

You need to install the below libraries order to create your own package and get it deployed to PyPI
1. setuptools
2. wheel
3. twine

Twine is used to upload your package to PyPI, if you have activated 2 factor authentication for PyPI account then you need to API token to authenticate. You need to create one file with name as
.pypirc and this should be in your home directory. and while upload your package file to PyPI you can use below line
 twine upload --config-file /path/to/your/.pypirc dist/*

OR

If 2 factor authentication is not activated you can use twine upload dist/* and then enter prompted username and password.

