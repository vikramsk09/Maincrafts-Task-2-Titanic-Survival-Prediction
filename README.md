# 🚢 Titanic Survival Prediction using Machine Learning

## 📌 Project Overview
The **Titanic Survival Prediction** project is a Data Science and Machine Learning project built using **Python**.  
The objective of this project is to predict whether a passenger survived the Titanic disaster based on different passenger features such as age, gender, passenger class, fare, etc.

This project includes:
- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Model Training
- Prediction using Machine Learning

---

# 🎯 Objective
The main goal of this project is to build a Machine Learning model that can accurately predict passenger survival on the Titanic dataset.

---

# 🛠️ Technologies Used
- Python
- VS Code
- Machine Learning
- Data Science

---

# 📚 Libraries Used

## 🔹 Data Handling & Numerical Operations
```python
import numpy as np
import pandas as pd
```

## 🔹 Data Visualization
```python
import matplotlib.pyplot as plt
import seaborn as sns
```

## 🔹 Machine Learning
```python
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import accuracy_score
```

---

# 📂 Dataset Information
The dataset contains passenger details such as:
- Passenger Class
- Name
- Gender
- Age
- Fare
- Embarked Location
- Survival Status

---

# 🔍 Project Workflow

## 1️⃣ Importing Libraries
All required libraries were imported for data processing, visualization, and Machine Learning.

---

## 2️⃣ Data Collection & Loading
The Titanic dataset was loaded into a Pandas DataFrame for analysis.

```python
df = pd.read_csv("Titanic-Dataset.csv")
```

---

## 3️⃣ Data Preprocessing
The dataset was cleaned and prepared by:
- Handling missing values
- Removing unnecessary columns
- Encoding categorical values
- Preparing data for training

---

## 4️⃣ Exploratory Data Analysis (EDA)
Data visualization techniques were used to understand:
- Survival distribution
- Gender-wise survival
- Passenger class analysis
- Age distribution
- Correlation between features

Visualization libraries used:
- Matplotlib
- Seaborn

---

# 📊 Sample Visualizations

## Survival Count Plot
```python
sns.countplot(x='Survived', data=df)
```

## Gender-wise Survival
```python
sns.countplot(x='Sex', hue='Survived', data=df)
```

---

# 🤖 Machine Learning Model

## 🔹 Logistic Regression
A **Logistic Regression** model was used to train the dataset and predict survival outcomes.

```python
model = LogisticRegression()
```

---

# ✂️ Train-Test Split
The dataset was divided into training and testing data using:

```python
train_test_split()
```

---

# 📈 Model Accuracy
The model achieved an accuracy score of:

# ✅ Accuracy Score: 78%

---

# 🎯 Prediction
The trained model predicts whether a passenger would:
- Survive
- Not Survive

based on input passenger information.

---

# ▶️ How to Run the Project

## Step 1: Clone the Repository
```bash
git clone https://github.com/vikramsk09/titanic-survival-prediction.git
```

---

## Step 2: Navigate to the Project Folder
```bash
cd titanic-survival-prediction
```

---

## Step 3: Install Required Libraries
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

---

## Step 4: Run the Python File
```bash
python titanic_survival_prediction.py
```

---

# 📁 Project Structure

```bash
Titanic-Survival-Prediction/
│
├── Titanic-Dataset.csv
├── titanic_survival_prediction.py
├── README.md
└── requirements.txt
```

---

# 📌 Features of the Project
✅ Data Cleaning & Preprocessing  
✅ Exploratory Data Analysis  
✅ Data Visualization  
✅ Machine Learning Model Training  
✅ Survival Prediction  
✅ Accuracy Evaluation  

---

# 💡 Learning Outcomes
Through this project, I learned:
- Data preprocessing techniques
- Data visualization
- Machine Learning workflow
- Logistic Regression algorithm
- Model evaluation
- Working with real-world datasets

---

# 🚀 Future Improvements
- Improve model accuracy using advanced algorithms
- Deploy as a web application
- Add Streamlit interface
- Use multiple Machine Learning models for comparison

---

# 🤝 Contributing
Contributions are welcome!

If you would like to improve this project:
1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a Pull Request

---

# 📜 License
This project is open-source and available under the **MIT License**.

---

# 👨‍💻 Author
## Vikram Singh Kushwaha

GitHub: [@vikramsk09](https://github.com/vikramsk09)

---

# ⭐ Support
If you like this project, please consider giving it a ⭐ on GitHub!

---
