🧪 Solubility Prediction: Linear Regression vs Random Forest
This project explores a machine learning approach to predicting the aqueous solubility of chemical compounds. Using molecular descriptor data, two models — Linear Regression and Random Forest Regressor — are trained and evaluated to determine their predictive performance.

📁 Project Structure
Dataset: A CSV file containing molecular descriptors and the target solubility values.

Data Preprocessing: Null value checks, basic EDA (distribution plots, feature correlation heatmap).

Feature Scaling: StandardScaler applied before training linear models.

Model Training:

Linear Regression

Random Forest Regressor

Model Evaluation: Metrics used include R² Score, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

Visualization:

Actual vs Predicted values plot

Error distribution

📊 Results Summary
Model	R² Score	MAE	RMSE
Linear Regression	Lower	Higher	Higher
Random Forest	Higher	Lower	Lower

Conclusion: The Random Forest Regressor significantly outperformed Linear Regression in predicting solubility, showcasing its ability to model nonlinear relationships and interactions between features.

🛠️ Tech Stack
Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

🚀 How to Run
Clone this repository.

Ensure you have the required libraries installed.

Open the notebook Solubility_Prediction_Linear_Regression_vs_Random_Forest.ipynb in Jupyter Notebook or Google Colab.

Run all cells to view results and visualizations.

📌 Author
Ruba Hassnain
AI/ML Intern
