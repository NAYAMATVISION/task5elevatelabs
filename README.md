📌 Task 5: Decision Trees & Random Forests
🎯 Objective:
To implement and understand Decision Tree and Random Forest classifiers using a medical dataset (Heart Disease).
We aimed to visualize the decision process, avoid overfitting, and interpret feature importance.

🧠 What We Learned:
Working of Decision Trees & Random Forests
Concepts like entropy, information gain, bagging, overfitting, and feature importance
Evaluation of model using accuracy, precision, recall, f1-score, and cross-validation

🧪 Libraries Used:
pandas, numpy, matplotlib, seaborn, sklearn

📊 Exploratory Data Analysis:
Checked for nulls, feature types, distributions
Created a correlation heatmap to understand relationships

✅ Step-by-Step Process:
Load and clean data

Exploratory Data Analysis using seaborn plots
![image](https://github.com/user-attachments/assets/7f39152e-c17b-4290-a92a-424d0a0a61af)
![image](https://github.com/user-attachments/assets/2a1244d4-2b3d-4a3f-9fde-defead7bdc8b)

Split dataset into training and test sets (80/20)

Train Decision Tree Classifier

Visualize tree structure
![image](https://github.com/user-attachments/assets/719f1205-09dc-4c41-a7d2-0ba0d94c97a4)

Evaluate model with classification report & accuracy
![image](https://github.com/user-attachments/assets/6b4bf433-7b0d-4b31-9fcb-e8690a6fe7b7)

Control overfitting by limiting tree depth

Train Random Forest Classifier

Check feature importance

Cross-validate the model for robustness

🌳 Decision Tree Accuracy:
Accuracy: 98.5%
F1-score: 0.99

🔥 Random Forest Accuracy:
Accuracy: 98.5%
F1-score: 0.99

📌 Conclusion:
Decision Trees are easy to interpret but prone to overfitting.

Random Forests overcome this by combining multiple trees (bagging).

Feature importance highlights key medical indicators.

Cross-validation ensures model generalization.




