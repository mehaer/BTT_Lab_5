# BTT_Lab_5
This project explores the Airbnb NYC listings dataset and applies logistic regression to solve a classification problem.
The focus of this lab is on the **evaluation phase** of the machine learning lifecycle — performing **model selection, hyperparameter tuning, feature selection, and performance evaluation**.

By the end of this project, a fully trained and optimized logistic regression model is built, evaluated, and made persistent for future use.

---

## Objectives
In this lab, I completed the following tasks:

1. **Data Preparation**
   - Loaded and explored the Airbnb NYC listings dataset  
   - Defined the target label (dependent variable)  
   - Identified and selected relevant features  
   - Created labeled examples for classification  

2. **Data Splitting**
   - Split the dataset into **training** and **test** sets for fair model evaluation  

3. **Model Training and Evaluation**
   - Trained a **Logistic Regression (LR)** model using **default hyperparameters**
   - Evaluated the model using key classification metrics (accuracy, precision, recall, F1-score)
   - Visualized performance with **precision-recall** and **ROC** curves
   - Computed the **Area Under the Curve (AUC)** for model comparison  

4. **Hyperparameter Tuning**
   - Performed a **Grid Search** to find the optimal value of the regularization parameter **C**
   - Re-trained and re-evaluated the model using the optimal hyperparameters

5. **Feature Selection**
   - Identified the most significant features contributing to model performance

6. **Model Persistence**
   - Saved the final trained model using **pickle** for future use

---

## Key Concepts Practiced
- Logistic Regression for Classification  
- Model Evaluation Metrics  
- Precision-Recall and ROC Curves  
- Hyperparameter Optimization with GridSearchCV  
- Feature Selection and Model Interpretation  
- Model Serialization (Persistence with Pickle)  

---

## Tools & Libraries
- **Python 3.x**
- **Jupyter Notebook**
- **pandas**, **numpy**
- **scikit-learn**
- **matplotlib**, **seaborn**
- **pickle**

---

## Example Outputs
- **Precision-Recall Curve:** compares baseline vs. tuned model  
- **ROC Curve & AUC:** evaluates discriminative ability  
- **Feature Importance:** highlights top predictors  
- **Grid Search Report:** displays optimal hyperparameter values  
