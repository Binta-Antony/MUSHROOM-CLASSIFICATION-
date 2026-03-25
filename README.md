# 🍄 Mushroom Classification - Edible vs Poisonous (Machine Learning)

## 📊 Project Overview
This project builds a **Machine Learning model** to classify mushrooms as **edible or poisonous** based on their physical characteristics.

The objective is to create a reliable classification system that can assist in **food safety, risk detection, and decision support**, reducing the chances of consuming toxic mushrooms.

---

## 🎯 Objectives
- Classify mushrooms into edible or poisonous categories  
- Build a complete ML pipeline from preprocessing to evaluation  
- Compare multiple machine learning models  
- Improve performance using hyperparameter tuning  
- Identify the most important features influencing predictions  

---

## 🧾 Dataset
The dataset contains categorical features describing mushroom characteristics such as:

- Cap shape, color, and surface  
- Odor  
- Gill size and color  
- Stalk shape and root  
- Habitat  

📌 *Target Variable:*  
- **0 → Edible**  
- **1 → Poisonous**

📌 *Dataset Source:* Kaggle Mushroom Dataset  

---

## 🛠️ Tools & Technologies
- Python  
- Pandas & NumPy  
- Scikit-learn  
- Matplotlib & Seaborn  
- Jupyter Notebook  

---

## 🔍 Machine Learning Workflow

### 1. Data Preprocessing
- Checked missing values and duplicates  
- Encoded categorical variables using **One-Hot Encoding**  
- Split data into training and testing sets  

### 2. Feature Engineering
- Transformed categorical features into numerical format  
- Ensured no data leakage using pipelines  

### 3. Model Training & Hyperparameter Tuning
The following models were trained and tuned using **GridSearchCV**:

- Logistic Regression  
- Random Forest  
- Gradient Boosting  

Cross-validation was used to ensure robust model performance.

---

## 📈 Model Evaluation
Models were evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC-AUC  

📌 Special focus was given to **Recall**, since misclassifying a poisonous mushroom as edible is highly dangerous.

---

## 🧠 Key Insights
- Odor is one of the most important features in classification  
- Tree-based models performed better than linear models  
- Hyperparameter tuning significantly improved performance  
- The dataset shows strong separability between classes  

---

## 📊 Visualizations
- Confusion Matrix  
- ROC Curve  
- Feature Importance plots  
- Correlation analysis  

---

## 💡 Business / Real-World Implications
- Helps prevent food poisoning risks  
- Can assist in agricultural and food safety systems  
- Useful as a decision-support tool for mushroom identification  

---

## 🚀 Future Improvements
- Use advanced models like XGBoost  
- Deploy as a web app (Streamlit)  
- Integrate with image-based mushroom recognition  

---

## 📌 Conclusion
This project demonstrates how machine learning can be effectively applied to **classification problems in safety-critical domains**, providing accurate and interpretable predictions.

---

## 👩‍💻 Author
**Binta Antony**  
MSc Data Science, AI & Digital Business  
