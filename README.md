# Performance-Evaluation-of-Machine-Learning-Models-for-House-Price-Prediction
Developed ML models on a dataset of 414 entries and 7 features. Linear Regression achieved 53% accuracy  (9% error), Random Forest 51% (9%), Gradient Boosting 48% (10%), and Decision Tree 20% (12%)  showed the worst performance. Analysis highlighted overfitting issues and improved prediction strategies.

Project Overview
This project demonstrates a comprehensive evaluation of multiple machine learning models to predict house prices, with the goal of identifying the most suitable model based on accuracy, interpretability, and computational efficiency.

By applying consistent preprocessing, training, and evaluation steps, we systematically compare several algorithms including Linear Regression, Decision Tree, Random Forest, and Gradient Boosting to determine which performs best for a structured housing dataset.

🔍 Key Highlights
✅ Data Preprocessing

Handled missing values, corrected errors, and removed duplicates

Feature-target split with an 80-20 train-test division

🧠 Models Compared

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

📈 Evaluation Metrics

Mean Absolute Error (MAE)

R-squared (R²)

📊 Results Summary
Model	MAE	R² Score
Linear Regression	9.75	0.53
Random Forest Regressor	9.89	0.51
Gradient Boosting	10.00	0.48
Decision Tree Regressor	11.76	0.20

🏆 Linear Regression outperformed all other models, offering the best trade-off between simplicity and predictive power.

🌳 Decision Tree overfit the training data, leading to the worst test performance.

🛠 Tech Stack
Python (pandas, numpy, scikit-learn, matplotlib)

Jupyter Notebook for analysis

Version-controlled with Git

🎯 Conclusion
This project highlights the importance of model evaluation and comparison in applied machine learning. Despite its simplicity, Linear Regression proved to be the most effective for this dataset, outperforming more complex ensemble methods in both MAE and R².
