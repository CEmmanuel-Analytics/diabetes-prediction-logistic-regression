# diabetes-prediction-logistic-regression
 Machine Learning model to predict diabetes using logistic regression,,I performed data cleaning, exploratory analysis, and applied logistic regression to predict diabetes from medical records. I evaluated the model using accuracy, ROC curve, and confusion matrix, and visualized key patterns using seaborn and matplotlib
#  Diabetes Prediction using Logistic Regression

This is a machine learning project where I built a model to **predict whether a patient has diabetes** based on their medical details such as glucose level, age, BMI, and more.

i created this as part of my data analytics learning journey, and it's one of my first fully documented projects on GitHub.

##  Problem Statement

Early diagnosis of diabetes can help patients get the right treatment and manage their condition. This project uses a dataset of medical measurements to **predict whether a person is diabetic or not**.


##  Dataset Overview

I used the **Pima Indians Diabetes Dataset**, which contains records of female patients, including:

| Feature | Description |
|---------|-------------|
| Pregnancies | Number of times pregnant |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure |
| SkinThickness | Triceps skinfold thickness |
| Insulin | 2-Hour serum insulin |
| BMI | Body mass index |
| DiabetesPedigreeFunction | Family history of diabetes |
| Age | Age in years |
| Outcome | Target variable (1 = diabetic, 0 = not diabetic) |

Dataset source: [Kaggle - Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)


##  What I Did

### 1. Data Cleaning
- Replaced **zero values** in columns like Glucose and BMI with the **mean** of each column (because 0 isn't a realistic value for these measurements).

### 2. Exploratory Data Analysis (EDA)
- I Used charts like **histograms**, **boxplots**, and **correlation heatmaps** to understand relationships in the data.
- I Found that **Glucose, BMI, and Age** had the strongest influence on diabetes diagnosis.

### 3. Model Building
- I Chose **Logistic Regression** because it's a simple but effective model for binary classification (diabetes or not).
- I Split the data into **training (80%) and test (20%)** sets.
- I Trained the model on the training data.

### 4. Evaluation
- I Measured model performance using:
  - **Accuracy**
  - **Confusion Matrix**
  - **Classification Report**
  - **ROC Curve**
- Also Visualized results for better understanding.

---

##  Tools & Technologies

- Python
- Jupyter Notebook
- Libraries:
  - `pandas`, `numpy` for data handling
  - `seaborn`, `matplotlib` for visualizations
  - `scikit-learn` for model building and evaluation

##  Key Results

- The model gave  **0.7532467532467533**.
- Features like **Glucose**, **BMI**, and **Age** were the strongest indicators of diabetes.
- ROC curve showed the model had decent classification power of AUC = 0.82.
- which indicates that the trade-off between sensitivity and specificity. Auc was close to 1 meaning that the model is good at distinguishing between classes [Screenshot 2025-06-20 114043](https://github.com/user-attachments/assets/13a7b7ac-855e-4176-acc0-91fea20c3e4d)                               

##  Files in This Repository!


- `diabetes_prediction.ipynb`: The main notebook with all steps explained and code executed
- `README.md`: Project explanation and documentation


## ✍️ About Me

I'm **Chibueze Emmanuel Chukwuma**, a growing data analyst passionate about solving real-world problems with data.  
This is one of my first machine learning projects, and I plan to build many more!


## Feedback

Feel free to check out the notebook, try it out, and message me with any suggestions or questions! 
