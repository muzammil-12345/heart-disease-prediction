# 💓 Heart Disease Prediction using Machine Learning

This project applies supervised machine learning to predict the presence of heart disease in patients based on various medical features.  
It uses a Random Forest Classifier with hyperparameter tuning to achieve high accuracy on a clean and preprocessed dataset.

---

## 📊 Dataset

The dataset contains health-related attributes such as age, cholesterol, resting blood pressure, chest pain type, and more.  
It is sourced from [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease) (or a variant of it).

**Key features include:**
- Age, Sex
- Chest Pain Type (cp)
- Resting Blood Pressure (trestbps)
- Serum Cholesterol (chol)
- Maximum Heart Rate Achieved (thalach)
- Exercise Induced Angina (exang)
- and more...

The target variable is:
- `target` → 1 indicates presence of heart disease, 0 indicates absence.

---

## 🧠 Model Used

- **Random Forest Classifier**  
  Ensemble method that builds multiple decision trees and averages their results for better generalization.

- **Hyperparameter Tuning**  
  - Used `RandomizedSearchCV` and `GridSearchCV`  
  - Tuned parameters: `n_estimators`, `max_depth`, `min_samples_split`, `min_samples_leaf`

---

## 📈 Results

| Metric     | Score     |
|------------|-----------|
| Accuracy   | 94.96%    |
| ROC AUC    | ~0.97     |
| Model Used | Random Forest (RSCV tuned) |

---

## 🔧 Technologies Used

- Python 3
- Pandas, NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Jupyter Notebook

---

## 📁 Project Structure
📦 heart-disease-prediction
├── heart2.csv # Dataset
├── HeartDiseasePrediction.ipynb # Jupyter Notebook
├── heart_disease_model.pkl # Trained model file
├── README.md # This file
├── .gitignore # Git ignore file
└── LICENSE # MIT License

---

## 🚀 How to Run

1. Clone this repo  
   `git clone https://github.com/muzammil-12345/heart-disease-prediction`

2. Install dependencies  
   `pip install -r requirements.txt`

3. Run the notebook  
   Open `HeartDiseasePrediction.ipynb` in Jupyter Notebook or VSCode

---

## 📌 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Muxammel**  
🔗 [LinkedIn]www.linkedin.com/in/muzammil-zulfiqar-895660375 
🐙 [GitHub]https://github.com/muzammil-12345

---

> “Prediction is very difficult, especially if it’s about the future.” – Niels Bohr
