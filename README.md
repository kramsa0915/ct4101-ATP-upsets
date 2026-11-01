# Predicting upsets against ATP top-20 players

CT4101 Machine Learning project, University of Galway. Anna Kramska, 26100706

## Question
When a top-20 player plays someone ranked at least 20 places below them, can the result be predicted before the match?

## Data
"ATP Tennis 2000-2026 Daily update" (version 1209) from Kaggle, which pulls its data from tennis-data.co.uk. License: CC0 Public Domain.

https://www.kaggle.com/datasets/dissfya/atp-tennis-2000-2023daily-pull

The CSV isn't included in the repo. 
Download it from the link above and save it in the `data` folder as `atp_tennis.csv`.

## Files
- `data/` - where the CSV goes
- `notebooks/1_data_exploration.ipynb` - data audit, the preprocessing and the baseline model
- `requirements.txt` - packages used


## How to run
Python 3.14.4. In Terminal, from this folder:

```
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
jupyter lab
```

Then open `notebooks/1_data_exploration.ipynb` and click Kernel > Restart Kernel and Run All Cells.


## Assistance
I used Claude during my work for Milestone 2 to understand what the milestone required, set up my environment, and check that I met each requirement. I mainly relied on CT4101 lecture slides from Weeks 1 to 3 to write and structure the code. I also used the official pandas and scikit-learn docs linked in the slides as resources for writing the code. I verified all my work by running everything myself and checking all the outputs.