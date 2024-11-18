# Credit_Card_Anomaly_Detection_by_Michae14

![image](https://github.com/user-attachments/assets/8c07c1cd-07c6-4c05-9cc7-80f5d5b55a26)

## Summary
This project develops a machine learning pipeline for detecting anomalies in credit card transactions. It emphasizes feature engineering techniques tailored to improve model accuracy for identifying fraudulent or suspicious activities. Key steps include data preprocessing, handling missing values, feature scaling, and encoding. The pipeline leverages various transformations and feature selection methods to enhance the data quality, which supports a robust anomaly detection model.

## Dataset Overview
![Screenshot 2024-11-18 at 16 21 58](https://github.com/user-attachments/assets/3d91af55-d668-4fe6-b70b-cb6217ee0dbb)

This dataset contains information on purchases made through the purchase card programs administered by the state and higher ed institutions at the Oklahoma state. The purchase card information will be updated monthly after the end of the month. For example, July information will be added in August. Here is the link to the dataset: https://data.ok.gov/dataset/purchase-card-pcard-fiscal-year-2014.

In the credit card dataset, there is a total of 442,458 rows and 11 columns of the data in the dataset, including columns that indicates the purchase time, cardholder, vendor, and purchase amount throught a specific time range. Take the first row as the example, a cardholde called Mason who work in the OKlahoma State University make a general purchase in charitable and social service organizations named NACAS in July 2013. 

![Screenshot 2024-11-18 at 16 25 50](https://github.com/user-attachments/assets/ea00abf7-dbaf-4aa5-a81d-3de6f6d10706)

The bar chart above displays the total number of purchases made through the purchase card program by various agencies and institutions in Oklahoma. The University of Oklahoma leads with the highest number of transactions, totaling 76,143. It is followed by the University of Oklahoma Health Sciences Center with 58,247 purchases. Other notable agencies include the Department of Corrections and the Department of Tourism and Recreation, indicating their high volume of expenditures through the program. The data highlights that educational institutions, health centers, and government departments are among the primary users of the purchase card system, reflecting their extensive procurement needs and frequent purchasing activities for operational and service needs.

## Feature Engineering

![Screenshot 2024-11-18 at 16 35 17](https://github.com/user-attachments/assets/87feb9a9-0748-4f14-99c0-67b687930939)

The first important feature engineering step before developing the anomaly detection model is to create specific date column to indicate the purchase year, month, week number, and day of the week. By creating those new columns, the 

## Project Structure
- **Data Preprocessing**: Handling missing values, scaling, and encoding.
- **Feature Engineering**: Applying transformations, selecting important features, and enhancing data for better model training.
- **Anomaly Detection Model**: Training a machine learning model specifically designed to detect anomalies in transaction data.

## Features
- **Data Cleaning**: Imputation of missing values, removal of outliers.
- **Feature Scaling**: Ensures numerical stability for model training.
- **Encoding**: Categorical encoding techniques tailored for anomaly detection.
