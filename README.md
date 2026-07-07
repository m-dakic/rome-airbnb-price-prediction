# 🧠 Rome Airbnb Price Prediction & Spatial Analysis

A complete end-to-end machine learning project that covers data exploration, preprocessing, feature engineering, model development, hyperparameter tuning, and performance evaluation. The objective is to build a reliable predictive model while following a reproducible machine learning workflow.

---

## 📌 Project Overview
This project demonstrates the complete machine learning pipeline:

* Data exploration and visualization of 37,652 Airbnb listings and 79 spatial/structural features.
* Data cleaning and preprocessing, including addressing severe right-skewness in the target variable.
* Feature engineering and regex-based column sanitization.
* Model training using linear and gradient boosting architectures.
* Hyperparameter optimization via Bayesian techniques.
* Model evaluation and comparison across log-transformed and original dollar scales.
* Final model selection to handle extreme price variance.

The project emphasizes reproducibility, clean code organization, and best practices commonly used in real-world machine learning projects.

---

## 📂 Project Structure

```
├── data/  # Directory for all raw, processed, and parquet datasets (Ignored via .gitignore)
│
├── notebooks/
│   ├── Rome_AirBnb_Analysis.ipynb
│   └── Rome_AirBnB_Model_Training.ipynb
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 📊 Exploratory Data Analysis

The exploratory analysis includes:

* Dataset overview
* Missing value analysis
* Distribution analysis
* Correlation analysis
* Feature relationships
* Outlier detection
* Data visualization

---

## ⚙️ Data Preprocessing

The preprocessing pipeline includes:

* Missing value handling
* Categorical feature encoding
* Feature scaling
* Feature selection
* Train/Validation/Test split

---

## 🤖 Models

The following machine learning models were evaluated:

* Ridge Regression (Baseline)
* LightGBM Regressor
* XGBoost Regressor

---

## 🎯 Hyperparameter Tuning

Model optimization was performed using:

* Bayesian Optimization via Optuna
* Cross Validation

---

## 📈 Evaluation Metrics

Evaluation Metrics included:

### Regression

* MAE
* RMSE
* R² Score
* R² Score (Log Scale)

---

## 🚀 Installation

Clone the repository:

```bash
git clone [https://github.com/m-dakic/rome-airbnb-prediction.git](https://github.com/m-dakic/rome-airbnb-prediction.git)
cd rome-airbnb-prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Execution:
Run the notebooks sequentially to reproduce the pipeline:

* Rome_AirBnb_Analysis.ipynb
* Rome_AirBnB_Model_Training.ipynb

Download the Pre-Trained Model:
Due to file size constraints, the final trained XGBoost model (.pkl) is hosted in the GitHub Releases section.

Navigate to the Releases tab on the right side of this repository.

Download the final_xgboost_model file from the latest release.

---

## 📌 Results

|      Metric       |  Score |
| ----------------- | -----: |
| MAE               |  62.69 |
| R² (Log Scale)    |  0.667 |

---

## 🛠️ Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* LightGBM
* XGBoost
* Optuna
* CatBoost
* Jupyter Notebook

---

## 📖 Future Improvements

* Additional feature engineering
* More advanced ensemble methods
* Automated feature selection
* Pipeline automation

---

## 📜 License

This project is licensed under the MIT License.

---

## 👤 Author

Marta Dakic
