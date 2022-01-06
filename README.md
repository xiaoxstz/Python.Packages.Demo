
<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [1. Reference](#1-reference)
- [2. installation](#2-installation)
  - [2.1. install with this folder](#21-install-with-this-folder)
  - [2.2. Install with wheel file](#22-install-with-wheel-file)
    - [2.2.1. build the wheel file](#221-build-the-wheel-file)
    - [2.2.2. install the wheel file](#222-install-the-wheel-file)
- [3. Usage](#3-usage)

<!-- /code_chunk_output -->

# 1. Reference
* the code is from https://www.tutorialsteacher.com/python/python-package
* the document refers to https://packaging.python.org/en/latest/tutorials/packaging-projects/
* usage of setup.py, setup.cfg, pyproject.toml:
  * [setuptools](https://setuptools.pypa.io/en/latest/setuptools.html)
  * [setuptools user guide](https://setuptools.pypa.io/en/latest/userguide/index.html)

# 2. installation
## 2.1. install with this folder
Open a command ternimal, and then switch to the project directory(where `setup.py` is). Then use the command below to install
```bash
pip install mypackage
```
## 2.2. Install with wheel file
### 2.2.1. build the wheel file
```bash
py -m build
```
then it will create a folder `dist` and a folder `mypackage.egg-info`
* there are `*.tar.gz` and `*.whl` in the folder `dist`
### 2.2.2. install the wheel file
```bash
pip install wheel_name.whl
```

# 3. Usage
There is a demo:
* `test.py` in this folder
