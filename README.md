# Credit-card_Fraud-detection

<details>
<summary>Table of Contents</summary>

- [Description](#description)
- [Installations](#installations)
- [Dataset](#data-set)
- [Features](#features)
- [Applications](#applications)
- [Project setup](#project-setup)
- [Results](#results)
- [Visualization](#visualization)
- [Conclusion](#conclusion)

</details>

## 📝Description

-This project aims to detect fraudulent credit card transactions using a Random Forest Classifier. The dataset used for this project is sourced from Kaggle and contains transactions made by credit cards in September 2013 by European cardholders.

## 🔗Installations

>To run this project, you'll need to have the following libraries installed:

pandas
numpy
matplotlib
seaborn
scikit-learn

You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 💻Dataset

-The dataset used in this project contains transactions made by credit cards in September 2013 by European cardholders. It includes only numerical input variables which are the result of a PCA transformation. Due to confidentiality issues, the original features are not provided.

>Time: Number of seconds elapsed between this transaction and the first transaction in the dataset
>V1 to V28: Principal components obtained with PCA
>Amount: Transaction amount
>Class: Target variable (1 for fraudulent transactions, 0 for non-fraudulent transactions)

## 🤖Features

>Data Preprocessing: Handled missing values, scaled features, and split the data into training and testing sets.

>Model Development: Implemented a Random Forest Classifier to predict fraudulent transactions.

>Evaluation Metrics: Calculated accuracy, precision, recall, F1-score, and ROC AUC to evaluate model performance.

>Visualization: Visualized class distribution, correlation matrix, transaction amount distribution, model evaluation metrics, feature importance, and pairplot of 
 selected features.

## 💸Applications

>1. Financial Institutions
Banks: To monitor and detect fraudulent activities in credit card transactions, preventing financial losses.
Credit Unions: To safeguard members' accounts from unauthorized transactions.

>2. E-commerce Platforms
Online Retailers: To protect customers and the platform from fraudulent purchases, chargebacks, and associated fees.
Payment Gateways: To offer secure transaction services to merchants and reduce fraud-related disputes.

>3. Payment Processors
Digital Wallets: To ensure the integrity and security of digital payment transactions.
Mobile Payment Apps: To detect and prevent fraudulent transactions in mobile-based payment systems.

>4. Insurance Companies
Claims Processing: To identify and prevent fraudulent insurance claims, reducing the financial burden on insurance providers.

>5. Telecommunication Companies
Billing Systems: To detect anomalies in billing and prevent fraudulent usage of telecom services.

>6. Online Services and Subscriptions
Streaming Services: To prevent fraudulent account access and subscription misuse.
Software-as-a-Service (SaaS): To secure transactions and account activities on subscription-based platforms.

>7. Government and Regulatory Bodies
Anti-Fraud Agencies: To enhance the detection and investigation of fraudulent financial activities.
Law Enforcement: To assist in tracking and prosecuting financial fraud cases.

>8. Fraud Prevention Services
Consultancy Firms: To offer fraud detection solutions to clients across different industries.
Cybersecurity Firms: To integrate fraud detection systems into broader security solutions for protecting financial data.

## 👨‍💻Project Setup

Clone the repository:
```bash
git clone https://github.com/Chanchal1010/Credit-card_Fraud-detection
```

Navigate to the project directory:
```bash
cd credit-card-fraud-detection
```

Run the Jupyter Notebook to execute the code and visualize the results.

## 🔮Results

-The Random Forest Classifier achieved the following evaluation metrics:

>Accuracy
>Precision
>Recall
>F1-score
>ROC AUC



## 📱Visualization

-The project includes the following visualizations:

>Class Distribution: Bar graph showing the distribution of fraudulent and non-fraudulent transactions.

>Correlation Matrix Heatmap: Heatmap showing the correlation between different features.

>Distribution of Transaction Amounts: Histogram showing the distribution of transaction amounts.

>Model Evaluation Metrics: Bar graph showing the values of different evaluation metrics.

>Feature Importance: Bar graph showing the importance of different features in the Random Forest model.

>Pairplot of Selected Features: Pairplot showing the relationships between selected features.


## 👨‍🏫Conclusion

-This project demonstrates the use of a Random Forest Classifier to detect fraudulent credit card transactions. The model is evaluated using various metrics and visualizations, providing a comprehensive analysis of its performance.




