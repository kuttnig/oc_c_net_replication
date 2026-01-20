# Setup

Having Ocpa + PM4PY installed at the same time causes problems...

Use separate venv's to run the notebooks:

```
python -m venv venv_ocpa
pip install -r requirements/requirements_ocpa.txt
# select venv within ocpa notebook

python -m venv venv_pm4py
pip install -r requirements/requirements_pm4py.txt
# select venv within pm4py notebook
```
