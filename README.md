# 💼 Salary Prediction using Linear Regression

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/your-repo-name/blob/main/salary_prediction_project.ipynb)

## 🧠 Project Overview
This project builds a **machine learning model** that predicts employee salaries based on factors such as **job title, experience, education, and location**.  
The dataset is taken from **Kaggle**, and the base model uses **Linear Regression**.  
To improve accuracy, ensemble methods such as **Random Forest**, **Gradient Boosting**, and **Voting Classifiers** are also implemented and compared.

---

## 🧩 Project Details

| Category | Details |
|-----------|----------|
| **Technology** | Machine Learning and Artificial Intelligence |
| **Platform** | Google Colab |
| **Difficulty Level** | Beginner |
| **Programming Language** | Python |
| **Libraries Used** | pandas, numpy, scikit-learn, matplotlib, seaborn, pickle |

---

## 📂 Files in the Repository

- **`salary_prediction_project.ipynb`** → Google Colab notebook containing all the code for training, evaluation, and saving the model.  
- **`dataset.csv`** → Dataset containing employee features and salary data.  
- **`model.pkl`** → Trained Linear Regression model saved for predictions.  

---

## ⚙️ How to Run the Project in Google Colab

### 1. Open the Notebook
- Upload the notebook file **`salary_prediction_project.ipynb`** to your Google Drive.  
- Open it in **Google Colab** (right-click → *Open with → Google Colab*).  

### 2. Upload the Dataset
In the Colab notebook, upload the dataset using this code cell:
```python
from google.colab import files
uploaded = files.upload()

