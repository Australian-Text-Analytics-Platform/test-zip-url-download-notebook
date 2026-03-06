### Test notebook for Simon Musgrave

[![Binder](https://binderhub.rc.nectar.org.au/badge_logo.svg)](https://binderhub.rc.nectar.org.au/v2/gh/Australian-Text-Analytics-Platform/test-zip-url-download-notebook/HEAD?labpath=test.ipynb)


## run locally

To run the notebook locally, run `uv run --with jupyter jupyter lab` in your terminal. 


## Changing the notebook

To add a dependency, run `uv add libraryname`; be sure to update `requirements.txt` by running `uv export --format requirements.txt --no-hashes > requirements.txt` (this copies the output of the export command into requirements.txt, where binder can read them)# test-zip-url-download-notebook-
