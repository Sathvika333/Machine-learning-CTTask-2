*COMPANY* : CODTECH IT SOLUTIONS  
*NAME* : R Sathvika teja 
*INTERN ID* : CT12WVZF 
*DOMAIN* : Data Analytics  
*DURATION* : 12 weeks  
*MENTOR* : Neela Santhosh Kumar 

# Machine-learning-CTTask-2

Task Description:

The objective of this machine learning task is to develop a classification model to predict employee performance, specifically determining whether an employee is likely to meet more than 80% of their Key Performance Indicators (KPIs). The analysis is centered on identifying performance patterns and factors contributing to high or low productivity, thereby enabling organizations to make data-driven decisions in workforce planning, training, and performance management.

The dataset comprises several features capturing employee details and performance-related metrics. These include categorical attributes such as department, region, and education level, as well as numerical features like age, length of service, previous year’s rating, and average training scores. The target variable is binary, indicating whether an employee meets more than 80% of the KPIs.

The analysis begins with a thorough data preprocessing phase. Missing values are handled appropriately to maintain data integrity. Categorical variables such as department and region are transformed using one-hot encoding to ensure compatibility with machine learning algorithms. Additionally, new features are engineered to improve the model’s predictive capability—for example, a derived metric termed training effectiveness, calculated using training scores and length of service, to capture the impact of training on performance.

Following preprocessing, the dataset is split into training and testing sets in an 80:20 ratio. A Random Forest Classifier is then implemented due to its robustness, ability to handle both categorical and numerical data, and effectiveness in capturing nonlinear relationships. Hyperparameter tuning is performed using GridSearchCV to optimize model performance. Various combinations of parameters such as the number of estimators, maximum depth, and minimum samples per split are explored to identify the best model configuration.

Model performance is evaluated using multiple classification metrics, including accuracy, precision, recall, and F1-score, to provide a comprehensive assessment. These metrics help balance the trade-off between false positives and false negatives, which is critical in performance prediction scenarios.

Key insights drawn from the model include the most influential features in predicting high-performing employees, such as previous year ratings, training scores, and length of service. This information is crucial for HR departments aiming to tailor interventions like additional training, mentorship programs, or revised appraisal processes.

The analysis also identifies potential limitations and next steps for improvement. These include testing alternative classification algorithms such as XGBoost, which may offer enhanced performance through gradient boosting. Addressing class imbalance in the dataset—if present—through techniques like SMOTE (Synthetic Minority Oversampling Technique) or class weighting is also considered essential for improving the model’s generalizability. Furthermore, interpretability tools such as SHAP (SHapley Additive exPlanations) values can be integrated to better understand feature contributions and support transparent decision-making.


outputs:
![Image](https://github.com/user-attachments/assets/10f95f82-f1ef-449a-b356-b12f79eea687)
![Image](https://github.com/user-attachments/assets/745623df-99b4-4336-b82d-447b1e4e6355)
![Image](https://github.com/user-attachments/assets/3b833876-ac47-478c-8611-7c3f6ac8abe8)
![Image](https://github.com/user-attachments/assets/56b980cf-eea6-42f5-a891-098adbe8d611)
