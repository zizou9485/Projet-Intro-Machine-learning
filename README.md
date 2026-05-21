# UFC Fight Winner Prediction

Me and my teammates decided to work on UFC data because we're all fans of the sport and thought it would be interesting to see if machine learning could actually predict fight outcomes. Turns out, it kind of can.

## What we did

We took a dataset of UFC fights from 1993 to 2021 (around 6000 fights, 144 columns) and tried to predict whether the Red corner or Blue corner fighter would win.

The data was messy lots of missing values, imbalanced classes, mixed types. We cleaned it up, balanced it with SMOTE, and trained two models to compare them.

## Models

- Random Forest 78.14% accuracy after tuning
- Logistic Regression 72.42% accuracy after tuning

Random Forest won.

## How to run it

```bash
git clone https://github.com/yourusername/UFC-Fight-Prediction-ML.git
cd UFC-Fight-Prediction-ML
pip install -r requirements.txt
jupyter notebook ufc_analysis.ipynb
```

## Dataset

From Kaggle: https://www.kaggle.com/datasets/rajeevw/ufcdata

## Files

- `ufc_analysis.ipynb` — the notebook with all the code
- `data.csv` — the raw dataset
- `requirements.txt` — dependencies

## Authors

Zied, Amine, Ryan — APU 2026
