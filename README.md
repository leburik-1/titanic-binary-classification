# 🚢 Titanic Survival Prediction with Decision Trees & Bayesian Optimization

A robust machine learning pipeline built to predict survival on the Titanic using a **Decision Tree Classifier**, enhanced with **Bayesian Optimization** for hyperparameter tuning. This project follows best practices in exploratory data analysis, feature engineering, model development, and tuning—targeting elite research and industry standards.

---

## 📌 Project Highlights

- 📊 **Dataset**: Titanic dataset from [Kaggle](https://www.kaggle.com/c/titanic)
- 🌲 **Model**: `sklearn.tree.DecisionTreeClassifier`
- 🔍 **Tuning Strategy**: `Bayesian Optimization` using `scikit-optimize (skopt)`
- 🧼 Full preprocessing pipeline (imputation, encoding, feature selection)
- 📈 Cross-validation with metrics logging
- 🧪 Jupyter notebooks and modular Python scripts
- 🎯 Structured for reproducibility and scalability

---

## ⚙️ Tech Stack

- Python 3.9+
- Pandas, NumPy
- Scikit-learn
- Scikit-optimize (`skopt`)
- Matplotlib, Seaborn
- Jupyter

---

## 🧠 Model Details

We use a `DecisionTreeClassifier` for its interpretability and fast performance. The tree is tuned via **Bayesian Optimization**, which models the objective function as a probabilistic surrogate and selects hyperparameters in a sample-efficient way.

### 📈 Hyperparameters Tuned

- `max_depth`
- `min_samples_split`
- `min_samples_leaf`
- `criterion` (`gini` vs `entropy`)

MIT License © 2025 Kirubel Awoke
For inquiries or collaborations:
Email: leburikplc@gmail.com
