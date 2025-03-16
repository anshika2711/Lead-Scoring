# Lead Scoring
## Problem Statement
An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses.

The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos. When these people fill up a form providing their email address or phone number, they are classified to be a lead. Moreover, the company also gets leads through past referrals. Once these leads are acquired, employees from the sales team start making calls, writing emails, etc. Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X education is around 30%.

X Education has appointed you to help them select the most promising leads, i.e. the leads that are most likely to convert into paying customers.The company requires you to build a model wherein you need to assign a lead score to each of the leads such that the customers with higher lead score have a higher conversion chance and the customers with lower lead score have a lower conversion chance.The CEO, in particular, has given a ballpark of the target lead conversion rate to be around 80%.

# Data Analysis & Machine Learning Pipeline

## Overview
Implements a **data analysis and machine learning pipeline** using Python. It covers:
- Data Preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature Engineering  
- Model Training & Hyperparameter Tuning  
- Model Evaluation  

The notebook utilizes popular Python libraries like `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, and `scikit-learn` for machine learning workflows.

## Model Training & Evaluation

### Algorithms Used:
- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **Decision Tree**
- **Random Forest**
- **Gradient Boosting**

### Hyperparameter Tuning:
- Implemented using **RandomizedSearchCV**
- Uses **StratifiedKFold** for cross-validation

### Model Evaluation Metrics:
- **F1 Score**
- **ROC-AUC Score**
- **Precision & Recall**
- **Confusion Matrix**

## Observations

After running the model on the **Test Data**, we obtain:

- **Accuracy**: **80.4%**  
- **Sensitivity (Recall)**: **80.4%**  
- **Specificity**: **80.5%**

## Results

### Comparing Train & Test Performance:

#### Train Data:
- **Accuracy**: **81.0%**  
- **Sensitivity**: **81.7%**  
- **Specificity**: **80.6%**  

#### Test Data:
- **Accuracy**: **80.4%**  
- **Sensitivity**: **80.4%**  
- **Specificity**: **80.5%**  

### Conclusion:
✅ We have successfully achieved our goal of predicting the **lead conversion rate** at around **80%**.  
✅ The model performs well on both training and test data, demonstrating **good generalization**.  
✅ This model can be confidently used to support **business decisions**, enabling the CEO to make **better calls** and improve **lead conversion rates**. 


