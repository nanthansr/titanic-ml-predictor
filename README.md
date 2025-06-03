# Titanic Survival Predictor 🚢

A simple logistic regression model that predicts passenger survival using the Titanic dataset.

## Features Used
- Pclass
- Sex
- Age
- SibSp (number of siblings/spouses aboard)
- Fare

## Accuracy
Achieved ~75.5% accuracy using logistic regression.

## Tools & Libraries
- Python
- pandas
- matplotlib & seaborn
- scikit-learn

## Files
- `Titanic_Model.ipynb` — main notebook

## 🔍 Model Comparison

| Model                | Accuracy | Precision (Survived) | Recall (Survived) | F1-Score (Survived) |
|----------------------|----------|------------------------|--------------------|----------------------|
| Logistic Regression  | 75.5%    | 0.70                   | 0.66               | 0.68                 |
| Decision Tree        | 74.1%    | 0.69                   | 0.61               | 0.65                 |
| Random Forest        | **76.9%**| **0.70**               | **0.71**           | **0.71**             |

### 🎯 Conclusion
Random Forest outperformed the other models in both accuracy and survivor recall. This ensemble method improved the balance between correctly identifying both survivors and non-survivors.

### 📈 Next Steps
- Tune hyperparameters (e.g., `max_depth`, `n_estimators`)
- Explore more features (e.g., `Embarked`, `Cabin`, `Title`)
- Try GridSearchCV for model optimization

