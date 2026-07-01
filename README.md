# HR Attrition & Compensation Predictive Modeling

**Objective**
This project analyzes historical HR data of 1470 IBM employees to predict employee attrition (classification) and optimal monthly income (regression). 
The goal is to provide data-driven and actionable insights for talent retention and optimized compensation using statistical learning algorithms.

**Methodology & Tech Stack**
* **Language:** R
* **Classification (Attrition):** Tuned Support Vector Machines (SVM) with radial kernels (`e1071`).
* **Regression (Income):** Random Forest and Gradient Boosting Machines (`randomForest`, `gbm`).
* **Unsupervised Learning:** K-Means clustering and Principal Component Analysis (PCA) for latent structure identification.
* **Validation:** 10-Fold Cross-Validation for hyperparameter tuning and MSE minimization.

**Key Findings**
* **Income Prediction:** The optimized Gradient Boosting Machine predicted monthly income with a highly accurate test Mean Squared Error (MSE) of
* 0.01, outperforming standard linear models.
* **Attrition Classification:** The radial Support Vector Machine (Cost: 10, Gamma: 0.1) successfully identified
* complex, non-linear boundaries between employees who stay and those who quit.
* **Feature Importance:** Random Forest variable importance analysis revealed that Job Role, the number of previous companies worked at,
* and total years working at IBM are the most critical predictors of an employee's salary and likelihood of leaving.
