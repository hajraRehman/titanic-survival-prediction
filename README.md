# Titanic Survival Prediction

This project predicts passenger survival on the Titanic using machine learning. It covers data loading, cleaning, exploratory analysis, feature engineering, model training, hyperparameter tuning, and model interpretation.

## Project Overview

- Downloaded and loaded Titanic datasets from Kaggle.
- Handled missing values in Age, Embarked, Fare, and Cabin columns.
- Extracted and simplified passenger titles from names.
- Performed exploratory data analysis (EDA) with visualizations.
- Created new features like FamilySize and interaction features combining categories.
- Applied log transformation to fare and scaled numerical features.
- Tested multiple models: Logistic Regression, Random Forest, and XGBoost.
- Tuned XGBoost hyperparameters to improve accuracy.
- Used SHAP for model explainability and feature importance analysis.
- Generated predictions for the test set and prepared submission file.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- shap
- missingno

Install dependencies via:

```bash
pip install -r requirements.txt
```

## How to Run

- Download data using the Kaggle API or manually place \`train.csv\` and \`test.csv\` in the \`data/\` folder.  
- Run the notebook or script \`titanic_project.ipynb\` step-by-step to follow data loading, cleaning, analysis, modeling, and evaluation.  
- Inspect outputs such as exploratory analysis visualizations, model training metrics, and validation results.  
- The final survival predictions are saved in \`titanic_final_submission.csv\` ready for submission.

---

## Results

The best XGBoost model achieved approximately **83% accuracy** on the validation set. Important features driving survival predictions included passenger **gender**, **class**, **fare paid**, **family size**, and **title** extracted from names.

---

## License

This project is **open-source** and free to use for learning and research purposes.


