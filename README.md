# Heart Disease Prediction Project 🧑‍⚕️🫀

This project focuses on predicting the likelihood of heart disease in patients using machine learning techniques. The goal is to build a model that can assist healthcare professionals in identifying high-risk individuals.

---

## Project Overview
- Objective: Predict whether a patient has heart disease based on clinical data.
- Dataset: The dataset contains clinical attributes such as age, sex, blood pressure, cholesterol levels, and more. All data is stored in the `data/` folder.  
- Approach: Data preprocessing → Model training → Hyperparameter Tuning → Evaluation → Prediction

---

## 🚀 Getting Started  

### 1. Clone the repository  
git clone https://github.com/YR-raj/Heart-disease_project.git

### 2. Go to project folder
cd Heart-disease_project

### 3. Create a virtual environment
conda create --name Heart_env python=3.9 -y

### 3. Activate environment
conda activate Heart_env

### 4. Install dependencies
conda env update --file environment.yml --prune

### 5. Run the notebook
jupyter notebook notebook.ipynb

---

## ⚙️ Tech Stack
- **Python**
- **Pandas, NumPy** (Data processing)
- **Matplotlib, Seaborn** (Visualization)
- **Scikit-learn** (Machine Learning)
- **Jupyter Notebook**

---

## 🚀 Steps in the Project
1. Data cleaning and preprocessing  
2. Model training using **LogisticRegression** (and other ML algorithms)  
3. Hyperparameter tuning for improved performance  
4. Model evaluation with different metrics including Cross-validation  

---

## 🔮 Results
- Best model achieved: **0.89 f1_score**
- Insights: Certain features like `sex`, `cp` and `thal` have high importance in predicting target variable.

---

## 📈 Future Work
- Making complete pipeline
- Deployment

---

## 🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.  

