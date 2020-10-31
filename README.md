# Court Scraping utilities

A python library for scraping case information from court systems.



## Development Install

1. Create and activate a Python 3.7.3 virtual env
1. `git clone git@github.com:codefortulsa/courtbot-library.git`
1. `cd courtbot-library`
1. `pip install -e .`

## Usage

Install with `pip install courtbot`


## Adding a court


## Run test scripts

- `pytest tests/`

or with ipdb:

    - `pytest -s tests/`

specify a test:

   - `pytest -s tests/test_parse.py -k 'test_events'`

## Deployment steps

1. `python3 setup.py sdist bdist_wheel`
1. `twine upload dist/*`