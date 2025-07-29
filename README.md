# 🔍 Fraud Detection for Financial Transactions

![Python](https://img.shields.io/badge/Python-Used-blue?logo=python)
![Sklearn](https://img.shields.io/badge/Sklearn-RandomForest-orange?logo=scikit-learn)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Used-purple?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Used-blue?logo=matplotlib)
![License](https://img.shields.io/badge/License-MIT-blueviolet)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-ff69b4)
![Last Updated](https://img.shields.io/badge/Updated-July%202025-red)

> Built a Random Forest model on 6M+ transactions to identify and analyze fraudulent financial activity using Python.

---

## 🚀 About the Project

This project tackles the critical issue of **financial fraud detection** using machine learning:

- 📊 Applied Random Forest Classifier on a 6M+ row transaction dataset  
- 🧪 Balanced the dataset and optimized model training  
- 🔎 Extracted top fraud-driving features for insights  
- ✅ Achieved 99% F1-score on imbalanced data  

---

## 🎯 Key Features

- 🧼 Data cleaning and preprocessing  
- ⚖️ Class imbalance handling with `class_weight='balanced'`  
- 🌲 Random Forest model with hyperparameter tuning  
- 📈 Evaluation using precision, recall, F1-score  
- 🔍 Feature importance analysis (`deltaOrig`, `deltaDest`)  

---

## 📂 Project Structure
```bash
Fraud-Detection/
├── fraud.ipynb            # Full notebook with EDA, modeling, evaluation
├── Fraud.csv              # Original dataset (6M+ rows)
└── README.md              # Project documentation
```
---

## 💻 Installation

1. **Clone the Repository**
```bash
git clone https://github.com/rds-124/Fraud-Detection.git
cd Fraud-Detection
```

2. **Install Required Libraries**
```bash
pip install pandas matplotlib seaborn scikit-learn
```

3. **Run the Notebook**
```bash
jupyter notebook Fraud_Detection_Model.ipynb
```
---

## 📊 Model Results

- ✅ **F1 Score**: 99%  
- 📉 **False Positive Rate**: Very low due to class-weighting  
- 🔍 **Top Fraud Indicators**:  
  - `deltaOrig`: Drop in origin balance  
  - `isFlaggedFraud`: Rule-based tagging  
  - `step`: Transaction time frame  

---

## 📈 Potential Improvements

- 🧠 Try ensemble models like XGBoost or LightGBM  
- 🧪 Cross-validation and grid search tuning  
- 🌐 Real-time fraud flagging with streaming data  
- 💾 Integrate with alerting systems  

---

## 🙏 Acknowledgements

- [Scikit-Learn](https://scikit-learn.org/)
- [Jupyter Notebook](https://jupyter.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)


---

## 📚 Learnings
- Dealt with severe class imbalance
- Improved model interpretability with feature engineering
- Gained experience using Random Forest for classification

---

## 📅 License

This project is licensed under the **MIT License**.

---

## 📧 Contact

**Rohith D**  
[LinkedIn](https://www.linkedin.com/in/rohith124) | [GitHub](https://github.com/rds-124)







