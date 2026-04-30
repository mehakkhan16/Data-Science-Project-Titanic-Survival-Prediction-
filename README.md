# 🚢 Titanic Survival Prediction using Machine Learning

## 📌 Overview
This project aims to predict whether a passenger survived the Titanic disaster using machine learning techniques. The analysis is based on passenger features such as age, gender, class, fare, and family relationships.

## 🎯 Problem Statement
The goal is to build a classification model that can accurately predict passenger survival using historical Titanic dataset features.

## 📊 Dataset
- Source: Kaggle Titanic Dataset  
- Total Records: 891 passengers  
- Features include: Age, Sex, Passenger Class (Pclass), Fare, SibSp, Parch, Embarked  

## ⚙️ Data Preprocessing
- Removed irrelevant columns: Name, Ticket, Cabin, PassengerId  
- Handled missing values:
  - Age filled using mean  
  - Embarked filled using mode  
- Converted categorical variables using one-hot encoding  
- Performed feature scaling on Age and Fare  

## 📉 Outlier Handling
- Outliers in Fare column were detected and removed using the IQR method to improve data quality.

## 📊 Exploratory Data Analysis (EDA)
- Survival distribution analysis  
- Age and Fare distribution visualization  
- Correlation heatmap  
- Scatter plots and count plots for insights  

## 🧠 Feature Engineering
- Created a new feature **FamilySize** by combining SibSp and Parch  

## 🤖 Models Used
- Logistic Regression  
- Decision Tree Classifier  

## 📈 Model Performance
| Model                | Accuracy |
|---------------------|---------|
| Logistic Regression | 74.8%   |
| Decision Tree       | 77.4%   |

🏆 **Best Model: Decision Tree**

## 📊 Evaluation Metrics
- Accuracy Score  
- Confusion Matrix  
- Classification Report  

## 🔍 Key Insights
- Gender (Sex) has a strong impact on survival  
- Fare shows a positive correlation with survival  
- Pclass and Age also influence survival probability  

## ⚠️ Limitations
- Dataset size is relatively small  
- Some important real-world features are missing  
- Model performance can improve with more data and advanced techniques  

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  

## ▶️ How to Run
1. Clone the repository  
2. Open the notebook (`.ipynb`)  
3. Run all cells

## 📎 Project Structure
├── notebook.ipynb
├── README.md
├── report.pdf (to be added)

## 📬 Contact
Feel free to connect with me for feedback 
Email: mk0882716@gmail.com

