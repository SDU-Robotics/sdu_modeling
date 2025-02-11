# Welcome to sdu_modeling

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/SDU-Robotics/sdu_modeling/ci.yml?branch=main)](https://github.com/SDU-Robotics/sdu_modeling/actions/workflows/ci.yml)
[![Documentation Status](https://readthedocs.org/projects/sdu_modeling/badge/)](https://sdu_modeling.readthedocs.io/)
[![codecov](https://codecov.io/gh/SDU-Robotics/sdu_modeling/branch/main/graph/badge.svg)](https://codecov.io/gh/SDU-Robotics/sdu_modeling)

## Installation

The Python package `sdu_modeling` can be installed from PyPI:

```
python -m pip install sdu_modeling
```

## Development installation

If you want to contribute to the development of `sdu_modeling`, we recommend
the following editable installation from this repository:

```
git clone git@github.com:SDU-Robotics/sdu_modeling.git
cd sdu_modeling
python -m pip install --editable .[tests]
```

Having done so, the test suite can be run using `pytest`:

```
python -m pytest
```

## Acknowledgments

This repository was set up using the [SSC Cookiecutter for Python Packages](https://github.com/ssciwr/cookiecutter-python-package).
