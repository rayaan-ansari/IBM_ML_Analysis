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
* **Income Prediction:** The optimized Gradient Boosting Machine predicted monthly income with a highly accurate test Mean Squared Error (MSE) of 0.01, outperforming standard linear models.
* **Attrition Classification:** The radial Support Vector Machine (Cost: 10, Gamma: 0.1) successfully identified
* complex, non-linear boundaries between employees who stay and those who quit.
* **Feature Importance:** Random Forest variable importance analysis revealed that Job Role, the number of previous companies worked at, and total years working at IBM are the most critical predictors of an employee's salary and likelihood of leaving.

# Some Images
<img width="411" height="753" alt="image" src="https://github.com/user-attachments/assets/01aaec46-c6f0-45a3-9478-b5ec6b65793c" />
<img width="400" height="358" alt="image" src="https://github.com/user-attachments/assets/868c89cd-cf43-42fe-8f54-5acb46629d97" />
<img width="400" height="766" alt="image" src="https://github.com/user-attachments/assets/058d1db7-d1df-43c0-8f18-7f9e5111bc97" />
<img width="400" height="389" alt="image" src="https://github.com/user-attachments/assets/4a7de397-6393-4cea-bfc3-8df961cd2035" />

