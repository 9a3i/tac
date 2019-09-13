# TAC

Course material for "Traitement automatique de corpus" (STIC-B545) taught at [ULB](https://ulb.be)

It is recommended to run this code in a virtual environment: 

```
pip install virtualenv
virtualenv tac_venv --python=python3
cd tac_venv
source bin/activate
git clone git@github.com:madewild/tac.git
```

Then install Python dependencies with `pip install -r requirements.txt`

## Module 1

Scraping the AVB to retrieve 2833 PDF bulletins

Usage: `python scrape.py`

Caution: Python 3.6 or higher required to handle [f-strings](https://www.python.org/dev/peps/pep-0498/)
