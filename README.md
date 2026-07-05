# Real-world Data Wrangling

Udacity data wrangling project: gather, assess, clean, store, and explore two
related real-world datasets, then answer a research question with visualizations.

## Project steps

1. **Gather** two related datasets using two different gathering methods.
2. **Assess** the data for quality and tidiness issues (2 each).
3. **Clean** the data to resolve the identified issues and combine the datasets.
4. **Store** raw and cleaned data in the local data store.
5. **Explore (EDA)** and answer a research question with at least two visualizations.

## Requirements

- Python 3.14 (see `.python-version`)

## Setup (local)

Create and activate the virtual environment (Python 3.14), then install dependencies:

```powershell
py -3.14 -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

## Project structure

```
Data_Wrangling_Project_Starter.ipynb   # main notebook
data/raw/                               # raw datasets (git-ignored)
data/cleaned/                           # cleaned datasets
requirements.txt                        # Python dependencies
.python-version                         # pinned Python version (3.14)
```

## Notes

- Raw data files are intentionally git-ignored; only cleaned data is tracked.
- Do not commit credentials (e.g. `kaggle.json`).
