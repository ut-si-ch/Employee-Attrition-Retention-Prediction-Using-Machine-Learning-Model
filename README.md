# Employee Attrition & Retention Prediction Using Machine Learning Model
Employee attrition &amp; retention prediction using different Machine Learning Models.

# Overview
The project is focused on Employee Retention and Attrition Prediction using machine learning, applied to an ITES company. It aims to identify key factors that contribute to employee turnover and retention, using machine learning models for prediction. This is essential for companies to retain valuable talent and reduce operational disruptions caused by high attrition rates.

# Business Understanding
Employee retention is crucial for maintaining productivity and avoiding the costs associated with hiring and training new employees. High turnover rates can lead to decreased employee morale, increased expenses, and reduced innovation. In the ITES sector, a target turnover rate of less than 10% is desired, while the company studied had an attrition rate of around 15-16%. The goal of this project is to analyze the factors influencing employee satisfaction and to develop a predictive model for identifying potential attrition cases.

# Dataset Overview
The dataset used for this analysis is the IBM HR Analytics Employee Attrition & Performance dataset from Kaggle. It contains data on employee demographics, job satisfaction, income, performance ratings, and other factors that can influence employee behavior. Key variables include:
- Education
- Monthly Income
- Percent Salary Hike
- Performance Rating
- Years in Current Role

The dataset was processed for exploratory data analysis (EDA) and used to build various machine learning models.

# Modeling and Evaluation
Several machine learning models were applied to the dataset, including:

- Decision Trees: For capturing non-linear relationships.
- Logistic Regression: For binary classification of whether an employee is likely to leave or stay.
- Random Forest: For improved accuracy through ensemble learning.
- Support Vector Machines (SVM): For handling complex, multidimensional datasets.

The K-Means clustering algorithm was also used to verify the authenticity of employee job satisfaction ratings by grouping employees into clusters. The final models were evaluated based on accuracy, with Logistic Regression and SVM providing the highest accuracy at 86.73%.

# Conclusion
This project provides valuable insights into the factors contributing to employee attrition. The use of machine learning techniques allowed the identification of key factors and accurate predictions of employee turnover. By implementing this predictive model, companies can take preemptive actions such as improving salary policies, offering promotions, and focusing on employee engagement to improve retention rates.
This approach also highlights the potential for future improvement by incorporating a more diverse dataset and psychological factors in the analysis.
