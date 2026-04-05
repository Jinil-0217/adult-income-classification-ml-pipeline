# 📊 Adult Income Prediction

## 📌 Overview
This project predicts whether an individual earns more than $50K per year using demographic and financial data. It is a binary classification problem with class imbalance.

---

## ⚙️ Tech Stack
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib    

---

## 🧠 Approach
- Data cleaning and preprocessing  
- Feature engineering  
- One-hot encoding for categorical variables  
- Random Forest Classifier  
- Hyperparameter tuning using RandomizedSearchCV  
- Threshold tuning using Precision-Recall curve  

---

## 📊 Results
- Accuracy: **86%**  
- F1-score (>50K): **0.72**  
- Balanced precision and recall achieved  

---

## 🔥 Key Highlights
- Handled imbalanced dataset using class weights  
- Improved model performance using threshold tuning  
- Built an end-to-end machine learning pipeline  

---

## 📂 Project Structure

adult_income_prediction.ipynb  
README.md  
requirements.txt  

---

## ▶️ How to Run

1. Install dependencies  
   pip install -r requirements.txt  

2. Launch Jupyter Notebook  
   jupyter notebook  

3. Open  
   adult_income_prediction.ipynb  

---

## 🚀 Future Improvements
- Try XGBoost or LightGBM  
- Add SHAP for interpretability  
- Deploy using Streamlit or Flask  

---

## ✅ Conclusion
The model achieves a strong balance between precision and recall and is suitable for real-world applications like income prediction, credit risk analysis, and customer segmentation.