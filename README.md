# Titanic Survival Predictor 🚢

A machine learning project that predicts passenger survival using the Titanic dataset.  
This project includes multiple models with performance comparisons to explore model accuracy and feature influence.

---

## 📊 Features Used
- `Pclass`: Passenger class
- `Sex`: Gender (encoded as 0 = male, 1 = female)
- `Age`: Age of passenger
- `SibSp`: Number of siblings/spouses aboard
- `Fare`: Ticket fare

---

## 🛠️ Tools & Libraries
- Python (Jupyter Notebook)
- pandas, numpy
- seaborn, matplotlib
- scikit-learn

---

## 📂 Project Files

| File                       | Description                            |
|----------------------------|----------------------------------------|
| `Titanic_Model.ipynb`      | Logistic Regression implementation     |
| `Titanic_Model_Tree.ipynb` | Decision Tree & Random Forest models   |

---

## ✅ Model Performance Comparison

| Model                | Accuracy | Precision (Survived) | Recall (Survived) | F1-Score (Survived) |
|----------------------|----------|------------------------|--------------------|----------------------|
| Logistic Regression  | 75.5%    | 0.70                   | 0.66               | 0.68                 |
| Decision Tree        | 74.1%    | 0.69                   | 0.61               | 0.65                 |
| Random Forest        | **76.9%**| **0.70**               | **0.71**           | **0.71**             |

---

## 🎯 Conclusion

- **Random Forest** performed the best across all key metrics.
- It provided a better balance in predicting both survivors and non-survivors.
- Logistic Regression remained competitive and interpretable.
- Decision Tree offers simplicity but underperformed slightly.

---

## 🚀 Next Steps
- 🔧 Tune hyperparameters using `GridSearchCV`
- 📊 Add more features (e.g., `Embarked`, `Cabin`, `Title` from Name)
- 🌐 Build a Streamlit app to deploy the model
- 📦 Save models with `joblib` for reuse
