# Analytics-Vidhya-Jobathon---Employee-Attrition-Rate-Prediction

Problem Statement

In recent years, attention has increasingly been paid to human resources (HR), since worker quality and skills represent a growth factor and a real competitive advantage for companies. After proving its mettle in sales and marketing, artificial intelligence is also becoming central to employee-related decisions within HR management. Organizational growth largely depends on staff retention. Losing employees frequently impacts the morale of the organization and hiring new employees is more expensive than retaining existing ones. You are working as a data scientist with HR Department of a large insurance company focused on sales team attrition. Insurance sales teams help insurance companies generate new business by contacting potential customers and selling one or more types of insurance. The department generally sees high attrition and thus staffing becomes a crucial aspect. To aid staffing, you are provided with the monthly information for a segment of employees for 2016 and 2017 and tasked to predict whether a current employee will be leaving the organization in the upcoming two quarters (01 Jan 2018 - 01 July 2018) or not, given:

1. Demographics of the employee (city, age, gender etc.)
2. Tenure information (joining date, Last Date)
3. Historical data regarding the performance of the employee (Quarterly rating, Monthly business acquired, designation, salary)

Approach

Created a target variable from dataset. If an employee left the company within 6 months of any monthly report date we set it as 1 and 0 otherwise. Since we want to  predict if an employees leaves in the first quarter (6 months period), we want our model to capture the characteristics of those employees who tend to leave within 6 months of monthly reporting. Since we have access to monthly reporting date of all employee, we can use the model to predict if the employee would leave within 6 months of a specific reporting date. This can help us get an idea of when an employee is likely to leave the company.

