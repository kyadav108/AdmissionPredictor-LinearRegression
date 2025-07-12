📊  #AdmissionPredictor-LinearRegression

🧠 Project Overview
This project leverages Linear Regression and its variants (Lasso, Ridge) to predict the admission chances of Indian applicants into Ivy League universities based on academic and profile features such as CGPA, GRE score, TOEFL score, SOP, LOR, and university rating.

🏢 Business Context
Jamboree is a renowned educational institution that has guided countless students to secure admissions into prestigious colleges abroad. With its effective problem-solving methods, Jamboree has enabled students to achieve high scores on competitive exams like GMAT, GRE, and SAT.

🎯 Purpose of the Case Study
The goal of this case study is to help Jamboree enhance its feature for assessing Ivy League admission chances, specifically for Indian applicants. Through statistical modeling and exploratory analysis, we identify significant variables and offer predictive insights to improve admission forecasting.

🛠️ Steps Performed
1. 🔍 Data Exploration
Reviewed dataset structure, datatypes, and null values.

Performed summary statistics and feature inspection.

2. 📊 Non-Graphical and Graphical Analysis
Visualized distributions of GRE, TOEFL, CGPA, SOP, etc.

Analyzed correlations and patterns using heatmap, pairplot, and histograms.

3. 📈 Data Modeling
Built multiple Linear Regression models using:

Simple Linear Regression

Ridge Regression

Lasso Regression

4. 📏 Regression Assumptions & Validation
Multicollinearity Check: Used Variance Inflation Factor (VIF)

Normality of Residuals: Verified using Q-Q plots and mean of residuals.

Linearity Check: Used correlation metrics and heatmap.

Homoscedasticity Test:

Visual inspection via residual plots

Goldfeld–Quandt Test

5. 🧪 Model Evaluation
Evaluated model performance using:

R² Score

Adjusted R²

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

📌 Key Features
Predictive modeling tailored for Ivy League admissions

Deep dive into linear regression assumptions

Comparative performance analysis: Linear vs Lasso vs Ridge

Useful for educational consultancies and students planning for higher education abroad

🚀 Technologies Used
Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn, Statsmodels

SciPy
