# py-stars #

[![Lint Code Base](https://github.com/Leogiciel/py-starter/actions/workflows/linter.yml/badge.svg?branch=dev)](https://github.com/Leogiciel/py-starter/actions/workflows/linter.yml)
[![Unit tests](https://github.com/Leogiciel/py-starter/actions/workflows/ci.yml/badge.svg?branch=dev)](https://github.com/Leogiciel/py-starter/actions/workflows/ci.yml)

## Description ##

Starter python library project for VSCode with built-in features:
- Preconfigured venv with linters and formatters
- Unit tests to run in tests.py
- README.md template (this one)
- Preconfigured lint.yml for GitHub Workflow
- Preconfigured ci.yml for Github Workflow (runs test.py unit tests)
- Preconfigured .gitignore file

*Example :*

**Input**
````lang-txt

````

**Output**
````lang-txt

````

## Usage ##

### Installation ###

- Clone this repo
- Open a terminal in local folder
- Create virtual environment :
````lang-txt
   py -3 -m venv .venv
   .venv\scripts\activate
````
- Install dependencies :
````lang-txt
   python -m pip install --upgrade pip
   pip install -r requirements.txt
````
- Enjoy !

### tests.py ###

This file can be run :
 - in debugger using the preconfigured "Launch current file" debug config
 - in Tests explorer tab
 - via Terminal with :
````lang-txt
python -m unittest tests.py
````

## Changelog ##

Initial release.

## TODO ##

- PyPI generation in CI step 
- Autogenerated doc
- Preconfigured logger
- Main template ?
- Module template ?
- Architecture hierarchy ?
