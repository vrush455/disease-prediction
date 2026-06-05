# Disease Prediction from Medical Data

An internship project for CodeAlpha that predicts the possibility of diseases using machine learning classification techniques.

## Datasets
- Breast Cancer (UCI ML Repository via sklearn)
- Pima Indians Diabetes
- Heart Disease (UCI)

## Algorithms Used
- Support Vector Machine (SVM)
- Logistic Regression
- Random Forest
- XGBoost

## Results
| Model | Breast Cancer | Diabetes | Heart Disease |
|---|---|---|---|
| SVM | 98.25% | 74.68% | 86.89% |
| Logistic Regression | 97.37% | 75.32% | 85.25% |
| Random Forest | 96.49% | 73.38% | 83.61% |
| XGBoost | 95.61% | 71.43% | 81.97% |

## Setup
```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Run
Open `Disease_Prediction_CodeAlpha.ipynb` in Jupyter Notebook.
