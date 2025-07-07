# Table Extraction from a PDF and then evaluation of checks in extracted table

## Activate Virtual Environment
python -m venv env

## Installing Requirements (see requirements.txt)
pip install -r requirements.txt

table-extraction.py is the final script ready to use in a project
pdf-test.ipynb is the notebook used for testing during development
Other .ipynb files were initial blueprints of the final pdf-test.py

Modify the script according to your usecase:
1. Changing indirect image input (PDF -> IMG) to direct image input
2. Changing detection of ticks to something else
and so on  .
