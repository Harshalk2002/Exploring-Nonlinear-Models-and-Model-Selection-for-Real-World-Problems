Exploring Nonlinear Models and Model Selection for Real-World Problems



📚 Project Overview
This project focuses on exploring various linear and nonlinear regression models to predict the Heating Load (Y1) of buildings, using the Energy Efficiency Dataset (ENB2012).
The objective is to understand how different models handle real-world data and identify trade-offs between accuracy, interpretability, and computational efficiency.

📝 Problem Statement
Efficient energy modeling is critical in sustainable building design. This project aims to develop models that can accurately predict the Heating Load (Y1) of buildings based on their architectural features.

🗂️ Contents
bash
Copy
Edit
├── Exploring_Nonlinear_Models_and_Model_Selection.ipynb   # Jupyter Notebook with full workflow
├── screenshots/                                           # Visualizations (optional but recommended)
├── report.pdf                                             # Detailed report (optional)
└── README.md                                              # This file

📦 Dataset
Source: UCI Machine Learning Repository
Dataset: Energy Efficiency Dataset (ENB2012)
Feature	Description
X1	Relative Compactness
X2	Surface Area
X3	Wall Area
X4	Roof Area
X5	Overall Height
X6	Orientation
X7	Glazing Area
X8	Glazing Area Distribution
Y1	Heating Load (Target Variable)
Y2	Cooling Load (Not used here)
🧰 Tools & Technologies
Language: Python 3.9+
Libraries:
pandas, numpy
matplotlib, seaborn
scikit-learn
🔥 Models Implemented
Model	Highlights
Linear Regression	Baseline, residual analysis
Polynomial Regression	Degree=2, cross-validation, captures non-linearity
Ridge Regression	Regularized linear model with hyperparameter tuning
Decision Tree Regressor	Pruned, interpretable, feature importance, visualization
✅ Results Summary
Model	MSE	RMSE	R²
Linear Regression	8.25	2.87	0.92
Polynomial Regression (d=2)	0.33	0.57	1.00
Ridge Regression (α=0.1)	8.27	2.88	0.92
Decision Tree (pruned)	0.36	0.60	1.00
Polynomial Regression (degree=2) delivered the best performance in terms of accuracy, while the Decision Tree Regressor provided interpretability and efficient predictions.
📈 Visualizations
✅ Correlation Heatmap
✅ Residual Plots (Linear and Polynomial Regression)
✅ Residual Histogram
✅ Predicted vs Actual (Polynomial Regression)
✅ Feature Importances (Decision Tree)
✅ Decision Tree Structure Visualization
Screenshots are located in the /screenshots folder
Example:

💡 Interpretability & Trade-offs
Polynomial Regression captures complex relationships but increases computational cost.
Decision Trees are intuitive and provide clear decision rules, although they can be prone to overfitting (pruning applied here).
Runtime and model complexity were considered in selecting the best approach for different scenarios.

📋 Project Structure
Copy
Edit
Exploring_Nonlinear_Models_and_Model_Selection/
├── Exploring_Nonlinear_Models_and_Model_Selection.ipynb
├── screenshots/
│   ├── correlation_heatmap.png
│   ├── residual_plot_linear.png
│   ├── feature_importance_tree.png
│   └── decision_tree_structure.png
├── report.pdf
└── README.md
✨ Author
Harshal Kamble

[LinkedIn](https://www.linkedin.com/in/harshalka/)

⚖️ License
This project is licensed under the MIT License.

📚 Acknowledgments
UCI Machine Learning Repository for providing the dataset.
scikit-learn for model implementations and documentation.
Matplotlib and Seaborn for visualizations.
⭐️ If you like this project, please give it a star!
✅ Next Steps (Optional Enhancements)
Implementing ensemble models (Random Forest, Gradient Boosting).
Hyperparameter tuning with more exhaustive grid search.
Exploring model deployment strategies.
How To Customize:
Replace yourusername with your GitHub username.
Add any screenshots to a folder /screenshots and link them in the README.
You can include your PDF report if you like.
Create a requirements.txt if you don't have one (I can help you with that!).
