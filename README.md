# Forest_cover_type_classification
 Project Overview
This project tackles the Forest Cover Type Classification problem using the Covertype dataset (UCI).
The goal is to predict the type of forest cover (7 classes) based on cartographic and environmental features.
We explore multiple tree-based machine learning models, compare their performance, and tune hyperparameters for the best results.

Dataset
Name: Covertype Dataset
Format: CSV
Target Variable: Cover_Type (7 forest cover types labeled as 1–7)
Features: Elevation, Aspect, Slope, Horizontal/Vertical Distances, Soil and Wilderness Area indicators, etc.

Tasks Performed
✅ Data Loading and Cleaning
✅ Preprocessing (categorical handling, scaling if needed)
✅ Train-Test Split
✅ Model Training:
Random Forest
XGBoost
✅ Model Evaluation:
Accuracy, Classification Report
Confusion Matrix Visualization
✅ Feature Importance Analysis
✅ Hyperparameter Tuning with GridSearchCV for XGBoost
✅ Comparison of Random Forest vs. XGBoost

Tech Stack
Language: Python
Libraries:
pandas, numpy → Data manipulation
scikit-learn → ML models & evaluation
xgboost → Gradient boosting model
matplotlib, seaborn → Visualization

Results
Random Forest: Provides strong baseline accuracy.
XGBoost: Outperforms Random Forest after hyperparameter tuning.
Feature Importance: Elevation, Soil Type, and Wilderness Area play key roles in classification.

Visualizations
Confusion Matrix for both models
Feature Importance plots (Random Forest & XGBoost)

Bonus Work
Hyperparameter tuning for XGBoost (GridSearchCV)
Model comparison table (Random Forest vs. XGBoost)

Conclusion
This project demonstrates multi-class classification with tree-based models.
It highlights how XGBoost combined with hyperparameter tuning can significantly boost performance compared to traditional models like Random Forest.
