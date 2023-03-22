# Calculator

Calculator is a package containing two main moduls:
- **calculate** - function able to calculate simple, well-formed mathematical expressions.
    >Expression passed as argument must be of string type. Function returns result of given expression or error message
in case its format was validated as faulty.
- **cli** - allows use of "calculator" from CLI.
    >After package installation should be available as executable.
## How to run

#### Installation

    $ pip install .

#### calculator CLI

    $ calculator

##### calculate function
    >>> from calculator import calculate
    >>> calculate('(2 + 2) * 2')
    8

## How to test

#### Installation

    $ pip install .[test]

#### Run tests

    $ pytest

## Requirements

All packages required to run calculator module are specified in pyproject.toml file.