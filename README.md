# Diabetes_Prediction
This project builds a Supervised Machine Learning model to predict diabetes risk based on patient health parameters. The model uses Support Vector Machines (SVM) for classification and is trained on a structured medical dataset.
Features & Methodology
✅ Dataset: Includes patient data such as Glucose Level, Blood Pressure, BMI, Insulin, Age, etc. <br>
✅ Standardization: Applied StandardScaler to normalize feature values, ensuring the model performs optimally on different scales of data. <br>
✅ Model Used: SVM (Support Vector Machine) for binary classification (Diabetic / Non-Diabetic). <br>
✅ Evaluation Metrics: Accuracy <br>
Results & Insights <br>
The SVM model achieved an accuracy of 77.27% on the test dataset. Feature importance analysis showed that Glucose Level and BMI were strong predictors of diabetes risk. The model effectively differentiates between diabetic and non-diabetic patients, making it a promising tool for early diagnosis. <br>
Future Enhancements <br>
To improve the accuracy (currently 77.27%), the following techniques can be implemented: <br>

🔹 Feature Engineering – Identify and add more relevant features (e.g., lifestyle factors, diet, genetic history) to improve predictions. <br>
🔹 Hyperparameter Tuning – Optimize SVM parameters (kernel type, C value, gamma) using GridSearchCV or RandomizedSearchCV. <br>
🔹 Data Augmentation – Use synthetic data generation techniques like SMOTE to handle class imbalances. <br>
🔹 Ensemble Learning – Combine SVM with Random Forest, XGBoost, or Neural Networks for better predictive power. <br>
🔹 Deep Learning Integration – Implement ANN (Artificial Neural Networks) for capturing complex patterns in medical data. <br>
🔹 Larger & More Diverse Dataset – Train the model on a bigger dataset with more diverse patient demographics for better generalization. <br>
🔹 Flask-Based Web App – Deploy the model as an interactive web application for real-time diabetes prediction. <br>

