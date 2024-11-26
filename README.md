# pyBADA

<a href="https://github.com/eurocontrol/pybada/blob/main/LICENCE.txt"><img alt="License: EUPL" src="https://img.shields.io/badge/license-EUPL-3785D1.svg"></a>
<a href="https://pypi.org/project/pyBADA"><img alt="Released on PyPi" src="https://img.shields.io/pypi/v/pyBADA.svg"></a>
![Python 3.12](https://img.shields.io/badge/Python-3.12-3776AB.svg?logo=python&logoColor=white)
<a href="https://github.com/eurocontrol/pybada"><img alt="Code style: black" src="https://img.shields.io/badge/code%20style-black-000000.svg"></a>
[![Run unit tests](https://github.com/eurocontrol/pybada/actions/workflows/pytest.yml/badge.svg)](https://github.com/eurocontrol/pybada/actions/workflows/pytest.yml)

This package provides aircraft performance modelling, trajectory prediction and optimisation, and visualisation with [BADA](https://www.eurocontrol.int/model/bada) in Python.

To get started

```bash
pip install pyBADA
```

Examples, the user manual and the API reference can be found at the [pyBADA documentation website](https://eurocontrol.github.io/pybada/index.html).

## Development

```bash
# Clone the repository
git clonehttps://github.com/eurocontrol/pybada

# Optionally, set up a virtual env and activate it
python3 -m venv env
source env/bin/activate

# Install package 
pip install .
# Install a couple of packages for formatting, linting and building the docs
pip install .[dev]

# Run unit tests
python3 -m pytest tests/
# Build the docs
cd docs
make html
```


### Running on unsupported environements

You won't receive support for it, but you can pass the flag `--ignore-requires-python` to install pyBADA on an unsupported Python version.


## License

BADA and pyBADA are developed and maintained by [EUROCONTROL](https://www.eurocontrol.int/).

This project is released under the European Union Public License v1.2 - see the [LICENSE](https://joinup.ec.europa.eu/collection/eupl/eupl-text-eupl-12) file for details.
