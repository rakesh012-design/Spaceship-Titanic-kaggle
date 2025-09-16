# 🛸 Spaceship Titanic – Kaggle Competition

This project predicts whether passengers were transported to an alternate dimension in the Spaceship Titanic [dataset](https://www.kaggle.com/competitions/spaceship-titanic/data)

## Key Steps

Performed exploratory data analysis (EDA) and handled missing values.

Encoded categorical features

OneHot / Ordinal encoding inside a ColumnTransformer

Applied Label Encoding on the target variable.

### Built and compared multiple models:

Tuned a Random Forest Classifier using GridSearchCV.

Implemented an XGBoost Classifier inside a pipeline along with preprocessing.

Selected the best estimator based on cross-validated accuracy.

Prepared predictions in the required Kaggle submission.csv format.

### Highlights

End-to-end pipeline ensured no data leakage and reproducible training.

Hyperparameter tuning significantly improved accuracy over baseline models.
### Hyper Parameter Tuning using GridSearchCV
![grid_search](/grid_search_results.png)

### PipeLine-Image
![pipeline](/pipe_line.png)
