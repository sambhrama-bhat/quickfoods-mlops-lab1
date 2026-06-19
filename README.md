# quickfoods-mlops-lab1
# QuickFoods MLOps Lab 1

## Objective
Build a reproducible machine learning project to predict food delivery time.

## Features
- distance_km
- items_count
- is_peak_hour
- traffic_level

## Target
- delivery_time_min

## Model Used
- Linear Regression

## Project Structure

```
quickfoods-mlops-lab1/
├── data/
│   └── delivery_times.csv
├── models/
│   └── delivery_time_model.pkl
├── src/
│   ├── __init__.py
│   └── train.py
├── .gitignore
├── requirements.txt
├── README.md
└── view_pkl.py
```

## Installation

```bash
pip install -r requirements.txt
```

## Run Training

```bash
python src/train.py
```

## Output

- Trained model artifact:
  `models/delivery_time_model.pkl`

