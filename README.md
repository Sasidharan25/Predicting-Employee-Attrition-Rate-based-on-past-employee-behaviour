# Analytics-Vidhya-Jobathon---Predicting Employee Attrition Rate based on past employee behaviour

![50662High-employee-turnover](https://user-images.githubusercontent.com/91523309/196420733-b317d554-a82d-4da3-9410-026ed8e6dd48.jpg)

# Problem Statement

In recent years, attention has increasingly been paid to human resources (HR), since worker quality and skills represent a growth factor and a real competitive advantage for companies. After proving its mettle in sales and marketing, artificial intelligence is also becoming central to employee-related decisions within HR management. Organizational growth largely depends on staff retention. Losing employees frequently impacts the morale of the organization and hiring new employees is more expensive than retaining existing ones. You are working as a data scientist with HR Department of a large insurance company focused on sales team attrition. Insurance sales teams help insurance companies generate new business by contacting potential customers and selling one or more types of insurance. The department generally sees high attrition and thus staffing becomes a crucial aspect. To aid staffing, you are provided with the monthly information for a segment of employees for 2016 and 2017 and tasked to predict whether a current employee will be leaving the organization in the upcoming two quarters (01 Jan 2018 - 01 July 2018) or not, given:

1. Demographics of the employee (city, age, gender etc.)
2. Tenure information (joining date, Last Date)
3. Historical data regarding the performance of the employee (Quarterly rating, Monthly business acquired, designation, salary)

# Contents

1. Data Preprocessing
2. Exploratory Analysis
3. Feature Creation
4. Target Label Creation
5. Model Building and Predictions

# Results

The metric used to evaluate the model (xgboost classifier) is f1-score (harmonic mean of precision and recall). Precision represents how accurate the model is in it's predictions (how many of the employees that are predicted to leave the company, will actually leave the company) . Recall represents the ability of the model to correctly capture all the relevant cases (correctly identify all the employees that will actually leave the company). A false negative in this project, is when the model falsely predicts an employee to stay at the company. A false positive, is when the model predicts falsely that an employee will leave the company. Since, both cases can cause staffing & resource allotment issues for the company, it is important to have a baalnce between the two metrics (recall and precison), hence the utilization of F1-Score. The model performance on  train dataset is 0.97 and on unseen test dataset in 0.90.
