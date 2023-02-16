# EOPricer Model

This simple Python package calculates the price of some barrier and exotic options.
This consists on an adptation of the Black and Scholes Model to the Bjerksund e Stensland Studies.

## Install
```bash
pip install exotic-options
```
## Import
```python
from exotic_options import EOPricer
```
## Create an instance of EOPricer Class
```python
pricer = EOPricer(S=None, K=None, r=None, T=None, H=None, option_type='call')
pricer.call_down_and_out(sigma=None)
```