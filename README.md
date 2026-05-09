# Explainable AI for Hiring

## Project Objective
The objective of this project is to predict whether a candidate will be selected based on their qualifications and performance using Machine Learning algorithms.

This project also focuses on Explainable AI (XAI), which helps users understand how the model makes predictions.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- SHAP
- LIME

---

## Machine Learning Algorithms
- Logistic Regression
- Random Forest Classifier

---

## Explainability Tools

### SHAP
SHAP is used to identify which features have the highest impact on model predictions.

### LIME
LIME is used to explain individual predictions made by the model.

---

## Input Features
- Experience
- Test Score
- Interview Score

---

## Output
- Selected
- Not Selected

---

## Workflow
1. Load and preprocess the dataset
2. Split data into training and testing sets
3. Train Logistic Regression and Random Forest models
4. Evaluate model performance using accuracy and confusion matrix
5. Compare model performance
6. Explain predictions using SHAP and LIME
7. Predict candidate selection status

---

## Project Outcome
The Random Forest model achieved better performance compared to Logistic Regression and was used for final prediction and explanation.

---

## Future Improvements
- Add larger datasets
- Build a web interface using Flask or Streamlit
- Deploy the model online
- Improve prediction accuracy using advanced algorithms
