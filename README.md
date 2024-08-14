# Bank_Customer_Churn_Prediction_Model
### **project link**: https://colab.research.google.com/drive/1I5J00yrFRovxaJZ0Ilp4q2Lqb3Evk3E4?usp=sharing

## Project Overview
This project focuses on predicting customer churn in the banking sector using machine learning techniques. The objective is to develop a model that can accurately identify customers who are likely to churn, helping the bank to implement targeted retention strategies.
Internship Integration: This project was a pivotal part of my internship, allowing me to apply theoretical knowledge in a practical setting, collaborate with industry professionals, and gain hands-on experience in building and optimizing predictive models.

## Learning Objectives
1. **Data Encoding:** Transform categorical data into numerical format using techniques like one-hot encoding and label encoding.
2. **Feature Scaling:** Normalize data to ensure that all features contribute equally to the model.
3. **Handling Imbalanced Data:**
   - **Random Undersampling**
   - **Random Oversampling**
4. **Support Vector Machine (SVM) Classifier:** Implement SVM to classify customers as churned or not churned.
5. **Grid Search for Hyperparameter Tuning:** Optimize the SVM classifier by selecting the best hyperparameters.

## Tools and Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn

## Steps Followed
1. **Data Preprocessing**
   - Encoded categorical variables.
   - Scaled features to a standard range.

2. **Imbalanced Data Handling**
   - Applied both random undersampling and oversampling techniques to balance the dataset.

3. **Modeling with SVM**
   - Implemented SVM classifier for churn prediction.
   - Used Grid Search for hyperparameter tuning.

4. **Evaluation**
   - Evaluated model performance using appropriate metrics such as accuracy, precision, recall, and F1-score.

## Results
- The final model achieved an
- [-Accuracy: Highest in Report 256 (0.91)
-Precision: Highest for Class 0 in Report 256 (0.96) and for Class 1 in Report 256 (0.86)
-Recall: Highest for Class 0 in Report 255 (0.99) and for Class 1 in Report 256 (0.97)
=F1-score: Highest for both classes in Report 256 (0.90 for Class 0 and 0.91 for Class 1)]
Report 256 stands out with the highest accuracy (0.91) and balanced metrics for both classes. 

## Conclusion
This project highlights the importance of proper data preprocessing and handling imbalanced datasets in developing robust machine learning models. The SVM classifier, optimized through Grid Search, provided valuable predictions that can guide customer retention efforts.


