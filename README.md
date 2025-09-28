# Flipkart-Customer-Experience-Analytics
Analyzed Flipkart’s customer service data to predict customer satisfaction (CSAT) and uncover actionable insights. Built predictive models and identified key factors impacting satisfaction to help proactively improve service quality and customer experience.
<img width="929" height="675" alt="Screenshot 2025-09-28 211459" src="https://github.com/user-attachments/assets/ea36bc21-9342-4f74-a0dc-a16ced32a0b7" />

# Problem Statement
The core challenge addressed in this project is to accurately predict customer satisfaction by integrating both structured operational data (such as the type of issue, time taken for resolution, communication channel used, and agent details) and unstructured textual data (specifically, customer remarks). By framing CSAT prediction as a classification problem, the project aims to uncover the key drivers behind both positive and negative customer experiences. Furthermore, the project explores the factors impacting issue resolution times through regression analysis and utilizes Natural Language Processing (NLP) techniques, such as sentiment analysis on customer remarks, to extract deeper, more nuanced insights into customer sentiment and overall experience. This integrated approach provides a holistic perspective on service performance. The actionable outcomes derived from this project are intended to empower e-commerce platforms to:

# What Was Done:
* Started with 85,907 records and 20 columns.
* Cleaned data: Handled up to 80% missing values in some columns and removed about 19% of rows as outliers.
* Created new features like response_time_mins and resolution_days.
* Explored data to find key insights through charts and statistics.
* Confirmed findings with hypothesis tests (e.g., significant CSAT differences across channels with p-values like 2.32e-43).
* Built ML models (Logistic Regression, Random Forest, XGBoost) to classify CSAT (High/Low).
* Used SMOTE to handle the imbalanced dataset.
# Key Insights:
* Most customers are satisfied (CSAT 4 and 5 are most common).
* "Returns" and "Order Related" are the most frequent issues.
* Faster response times (e.g., 0-5 mins) lead to higher average CSAT (~4.4).
* Average CSAT varies slightly by channel (e.g., Inbound ~4.2, Outcall ~4.3).
* Agent experience also influences CSAT.
* Model Performance:
* Models (especially XGBoost with ~84% accuracy) are good at predicting satisfied customers (High CSAT recall up to 0.98).
* Models struggle to accurately predict dissatisfied customers (Low CSAT recall as low as 0.05), which needs improvement for proactive action.

# What's Next:
* Use customer remarks (text data) for more insights into dissatisfaction.
* Improve models to better identify dissatisfied customers (Low CSAT).
*Use these findings to improve service operations and increase overall satisfaction.
