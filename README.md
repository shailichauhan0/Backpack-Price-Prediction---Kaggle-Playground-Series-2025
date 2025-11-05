# Backpack Price Prediction

This project predicts **backpack prices** using a **Linear Regression** model trained on various product attributes such as brand, material, size, compartments, and weight capacity. It demonstrates a complete machine learning workflow — from preprocessing to model training and prediction — in Python.

---

## 📂 Project Structure
```
backpack-price-prediction/
├─ data/
│  ├─ train.csv
│  └─ test.csv
├─ src/
│  ├─ data_processing.py
│  ├─ train.py
│  └─ predict.py
├─ models/
│  └─ linear_model.pkl
├─ requirements.txt
├─ .gitignore
└─ README.md
```

---

## 🧠 Overview
This repository demonstrates how to build a **regression model** to predict backpack prices. It includes:

- Data loading and exploration using **Pandas**
- Label encoding of categorical features
- Handling missing values
- Linear regression model training and validation
- Generating final predictions and creating `submission.csv`

---

## ⚙️ Installation
```bash
# Clone the repository
 git clone https://github.com/yourusername/backpack-price-prediction.git
 cd backpack-price-prediction

# Install dependencies
 pip install -r requirements.txt
```

---

## 📘 Requirements (`requirements.txt`)
```
pandas>=1.3
numpy>=1.19
scikit-learn>=1.0
joblib>=1.0
matplotlib>=3.3
```


---

## 🧮 Concept: Label Encoding
Label Encoding converts text-based categorical values into numeric form. For example:

| Color | Encoded |
|--------|----------|
| Red    | 0        |
| Blue   | 1        |
| Green  | 2        |

This is necessary because ML models can’t process string data directly.

---

## 📈 Results
- Model: **Linear Regression**
- Metrics: Printed R² and RMSE values on validation data.
- Output: `submission.csv` containing predicted prices.

---

## 🚀 Future Improvements
- Use **One-Hot Encoding** instead of Label Encoding for non-ordinal categories.
- Try **advanced models** like Random Forest, XGBoost, or Gradient Boosting.
- Perform **hyperparameter tuning**.
- Add **visualizations** for EDA.

---

## 👩‍💻 Interview-Ready Summary
> “I built a machine learning project that predicts backpack prices using product attributes. I used pandas and sklearn for preprocessing, label encoding for categorical data, and a Linear Regression model for prediction. It helped me understand the end-to-end ML workflow — from data cleaning and encoding to model training and generating final predictions.”

---

## 🪪 License
MIT License

