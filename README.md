# DeepCSAT: Customer Satisfaction Prediction for E-Commerce

## Project Overview
Customer satisfaction is one of the most critical success factors for e-commerce platforms. Poor customer support experiences can lead to negative reviews, reduced customer retention, and revenue loss.

This project focuses on predicting Customer Satisfaction Score (CSAT) using machine learning techniques applied to customer support interaction data. The dataset contains approximately 85,000 customer service interactions from an e-commerce platform.

The goal of this project is to analyze patterns in customer support operations and build a predictive model that can estimate customer satisfaction levels based on service-related variables.

## Dataset
The dataset includes customer service interaction details such as:

- Communication channel
- Product category
- Issue type
- Customer city
- Item price
- Agent handling time
- Agent shift and experience
- Order timestamps
- Customer satisfaction score (CSAT)

Each row represents a single customer support interaction.

## Project Workflow

1. Data Loading and Exploration
2. Data Cleaning and Missing Value Handling
3. Feature Engineering
4. Exploratory Data Analysis (EDA)
5. Hypothesis Testing
6. Feature Encoding and Scaling
7. Train-Test Split
8. Machine Learning Model Development
9. Hyperparameter Tuning
10. Model Evaluation
11. Feature Importance Analysis
12. Model Saving for Deployment

## Machine Learning Models Used

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

## Model Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

Among the tested models, Random Forest performed best with an accuracy of approximately **69%**.

## Key Insights

- Customer handling time significantly affects satisfaction levels.
- Certain product categories generate more support interactions.
- Experienced agents tend to achieve higher satisfaction scores.
- Communication channels influence customer experience.

## Business Impact

The predictive model can help e-commerce companies:

- Identify potentially dissatisfied customers early
- Improve customer support operations
- Optimize agent training strategies
- Reduce response time and improve service quality

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Future Improvements

Future work may include:

- Using advanced models such as XGBoost or LightGBM
- Applying Natural Language Processing (NLP) on customer remarks
- Building a real-time prediction API for deployment
- Integrating the model into customer support systems

## Author

Kumari Vrishti  
B.Tech Computer Science Engineering
