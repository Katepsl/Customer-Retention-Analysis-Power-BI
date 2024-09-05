# Customer-Retention-Analysis-Power-BI

# Overview

This project analyzes customer retention for PhoneNow, a telecommunications company. The dataset includes demographic, service usage, and contract-related information, aimed at understanding the factors that contribute to customer churn. By identifying key trends, the analysis offers insights into improving customer retention strategies.

# Dataset Description

The dataset consists of the following columns:

customerID: Unique identifier for each customer.

Demographics:

gender: Male or Female.
Age range: Categorized into "Old" and "Young."
SeniorCitizen: Whether the customer is a senior citizen (1 for yes, 0 for no).
Partner: Whether the customer has a partner (Yes/No).
Dependents: Whether the customer has dependents (Yes/No).

Service Information:

tenure: Number of months the customer has stayed with the company.
PhoneService: Whether the customer has a phone service (Yes/No).
MultipleLines: Whether the customer has multiple phone lines (Yes/No).
InternetService: Type of internet service (Fiber optic, DSL, or No).
OnlineSecurity: Whether the customer has online security services (Yes/No).
OnlineBackup: Whether the customer has online backup services (Yes/No).
DeviceProtection: Whether the customer has device protection (Yes/No).
TechSupport: Whether the customer has technical support services (Yes/No).
StreamingTV: Whether the customer has streaming TV service (Yes/No).
StreamingMovies: Whether the customer has streaming movies service (Yes/No).

Contract Information:

Contract: Type of contract (Month-to-month, One-year, or Two-year).
PaperlessBilling: Whether the customer uses paperless billing (Yes/No).
PaymentMethod: Payment method used by the customer (Bank transfer, Credit card, Electronic check).
Charges:
MonthlyCharges: The monthly charges for the customer.
TotalCharges: The total charges incurred by the customer.

Support Tickets:

numAdminTickets: Number of administrative tickets raised by the customer.
numTechTickets: Number of technical tickets raised by the customer.
Churn: Whether the customer has left the service (Yes/No).

# Key Metrics

Churn Analysis: The number of customers who have left the service.

Demographic Trends: Analysis based on gender, age, senior citizen status, partner, and dependents.

Service Utilization: Insight into services subscribed by customers, including phone, internet, security, backup, and streaming.

Contract & Payment: Analysis of the distribution of contract types and payment methods.

Charges & Tickets: Breakdown of monthly and total charges, as well as the number of administrative and technical tickets raised.

# Visualizations

This analysis includes several visualizations to illustrate the data:

Customer Demographics: Bar charts showing the distribution of customers by gender, age range, senior citizen status, partner, and dependents.

Service Subscriptions: Visual breakdown of customers' service usage (e.g., internet, security, backup, streaming).

Contract & Payment Analysis: Charts showing the type of contracts and payment methods used by customers.

Ticket Analysis: Scatter plots comparing the number of administrative and technical tickets raised.

Churn Trends: Graphs highlighting the relationship between customer tenure, charges, and churn rates.

# Conclusion

The analysis provides critical insights for PhoneNow to understand the factors contributing to customer churn. The data reveals correlations between service usage, contract type, payment method, and churn, allowing the company to identify at-risk customers and improve retention strategies.

# Future Work

To enhance the analysis, future work may include:

Predictive modeling to forecast customer churn.
Clustering customers based on their service usage and demographic data.
Further segmentation of customers based on ticket activity and contract preferences.
