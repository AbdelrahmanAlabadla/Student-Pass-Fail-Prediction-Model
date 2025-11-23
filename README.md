# Student Pass/Fail Prediction Model

This project predicts whether a student will **pass or fail an exam** based on two key features: study hours and previous exam scores, using a **Logistic Regression** model. It demonstrates a full workflow from data preprocessing, model training, evaluation, to real-time prediction for new inputs.

## How it Works

1. **Data Processing**  
   - The model is trained on a dataset containing students’ study hours, previous exam scores, and their pass/fail outcomes.  
   - Features are scaled using **StandardScaler** to normalize the data, which improves model performance.  
   - The target variable `Pass/Fail` is binary (0 = Fail, 1 = Pass).

2. **Model Training**  
   - The data is split into **training** and **testing** sets.  
   - A **Logistic Regression** model is trained to predict pass/fail outcomes.  
   - Model performance is evaluated using metrics such as **accuracy**, **confusion matrix**, and the number of students passing or failing.

3. **User Input Prediction**  
   - Users can enter their **study hours** and **previous exam score**.  
   - Inputs are scaled the same way as the training data.  
   - The model predicts whether the student is likely to **pass ✅** or **fail ❌**.

4. **Visualization**  
   - The relationship between combined features and outcomes is visualized using **scatter plots**.  
   - Actual vs. predicted outcomes are plotted to illustrate the model's predictive capability.

## Features

- Takes **real-time user input** for study hours and previous scores.  
- Provides **pass/fail prediction** based on logistic regression.  
- Includes **evaluation metrics** for transparency.  
- Visualizes the model’s predictions alongside actual outcomes.  

This project is ideal for educational insights, helping students understand how study habits and previous performance can influence exam outcomes. It also serves as a **simple, interactive machine learning demo** for beginners.
