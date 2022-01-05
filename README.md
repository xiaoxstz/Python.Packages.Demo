
<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [1. installation](#1-installation)
  - [1.1. install with this folder](#11-install-with-this-folder)
  - [1.2. Install with wheel file](#12-install-with-wheel-file)
    - [1.2.1. build the wheel file](#121-build-the-wheel-file)
    - [1.2.2. install the wheel file](#122-install-the-wheel-file)
- [2. Usage](#2-usage)

<!-- /code_chunk_output -->

# 1. installation
## 1.1. install with this folder
Open a command ternimal, and then switch to the project directory(where `setup.py` is). Then use the command below to install
```bash
pip install mypackage
```
## 1.2. Install with wheel file
### 1.2.1. build the wheel file
```bash
py -m build
```
then it will create a folder `dist` and a folder `mypackage.egg-info`
* there are `*.tar.gz` and `*.whl` in the folder `dist`
### 1.2.2. install the wheel file
```bash
pip install wheel_name.whl
```

# 2. Usage
There is a demo:
* `test.py` in this folder