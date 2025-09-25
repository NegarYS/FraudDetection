
# 🚗 Fraud Detection in Car Insurance

## 📌 Overview
This project focuses on **detecting fraudulent claims in car insurance** using machine learning models.  
The dataset (`fraud_oracle.csv`) contains various features of insurance claims, and the goal is to classify whether a claim is **fraudulent or genuine**.  
Since only about **6% of claims are fraudulent**, the dataset is highly **imbalanced**, which makes the problem more challenging.

---

## ✨ Features
- Data preprocessing and cleaning (handling missing values, duplicates, scaling).  
- Exploratory Data Analysis (EDA) with statistical summaries and visualizations.  
- Analysis of class imbalance in the dataset.  
- Application of multiple ML models using **LazyClassifier** for quick benchmarking.  
- Hyperparameter tuning with **RandomizedSearchCV** (Random Forest).  
- Threshold adjustment to improve recall/precision trade-off.  

---

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Lazypredict  

---

## 📂 Files Structure
```
fraud-detection-car-insurance/
│
├── fraudDetection-Project.ipynb         # Jupyter Notebook with full implementation
├── README.md                # Project description
├── fraud_oracle.csv         # Dataset
├── FinalProject-docu.pdf/    # Project description pdf file
```

---

## 🚀 Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/fraud-detection-car-insurance.git
   cd fraud-detection-car-insurance
   ```  
2.Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn lazypredict

   ```
3.Run the notebook:
   ```bash
   jupyter notebook fraudDetection-Project.ipynb
   ```

## 📊 Results
- The dataset is highly **imbalanced** (only ~6% fraud cases).  
- Several machine learning models were tested using `LazyClassifier`.  
- The best performing model was **Ensemble** by F1-score.  
- Example metrics :  
  - **Accuracy**: ~0.85  
  - **Precision**: ~0.22
  - **Recall**: ~0.61
  - **F1-score**: ~0.32  

---

## 🎯 Conclusion
This project demonstrates the process of handling **imbalanced datasets** and applying machine learning to a **real-world fraud detection problem**.  
The insights can be extended for practical fraud detection systems in the insurance industry.
