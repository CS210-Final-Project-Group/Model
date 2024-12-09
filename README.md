# Model

## Project Proposal

### NAME = "Ewan Jee, Rushi Patel"

### Project Proposal
### PARTICIPANTS
    - Ewan Jee (netId: ej307)
    - Rushi Patel(netId: rpp138)
### PURPOSE
    - We aim to develop a predictive model that estimates the insurance coverage amount
    for customers based on demographic and socioeconomic factors such as income,
    occupation, and gender. The problem we are addressing is the inefficiency in
    personalized insurance offerings due to inadequate customer segmentation and risk
    assessment. By accurately predicting coverage amounts, insurance companies can
    tailor their products to meet individual needs, optimize pricing strategies, and improve
    customer satisfaction.
### OVERVIEW
    - Define Project:
    - Accurately forecasting premium and coverage amounts is essential in the
    insurance industry to offer tailored products and competitive pricing. This project
    aims to build predictive models using customer data to enhance segmentation
    and optimize policy pricing. By aligning premiums and coverage with individual
    profiles, the approach seeks to improve customer satisfaction and retention. This
    predictive model integrates key data management principles like data
    preprocessing, feature engineering, and machine learning.
    - NOVELTY & IMPORTANCE
    - Accurate predictions of premium and coverage amounts enable better pricing
    decisions, helping insurers avoid underpricing or overpricing. This approach also
    supports competitive, dynamic pricing tailored to specific risks and customer
    behaviors. The project leverages data science to transform customer behavior,
    demographics, and policy trends into actionable insights for practical business
    impact.
    - Traditional insurance data practices rely on generic segmentation, often
    overlooking individualized behavioral and socioeconomic data. Research shows
    that precise segmentation can boost profitability and customer satisfaction
    ("Exploring the Power of Data Analytics in the Insurance Industry," Innowise).
    This project proposes an innovative approach, using predictive analytics and
    personalized segmentation through detailed customer insights to enhance
    traditional models.
### PLAN
    - Data:
    - Source: The Kaggle dataset(CSV) includes customer demographics,
    socioeconomic details, behavioral data, and policy information.
    - Data Preparation: Missing values will be handled in data preprocessing, also
    encoding categorical variables and scaling numerical features. Feature
    engineering will generate insights such as income-to-coverage ratios and
    engagement metrics from customer service interactions.
    - Models and Techniques:
    - Linear Regression: This project uses linear regression to predict Premium and
    Coverage Amounts, chosen for its simplicity and interpretability, allowing clear
    insights into how customer characteristics relate to these targets.
    - Data Processing Methods
    - One-Hot Encoding: For categorical data and Scaling of numeric data for
    consistency.
    - Feature Engineering: For insights like engagement scores and
    income-to-coverage ratios.
    - Normalization: normalize numeric values to ensure consistency in feature
    values.
    - Implementation Steps
    - Data Preprocessing: Clean and preprocess the dataset, focusing on handling
    missing values and encoding categorical data.
    - Model Training: Train the linear regression model, optimizing for the best
    performance.
    - Validation and Testing: Split data into training and test sets, using metrics like
    Mean Absolute Error and R-squared(r2) to evaluate predictive accuracy of the
    model.
    - Evaluation and Success Metrics
    - Predictive Accuracy: Achieving a low Mean Absolute Error and R-squared(r2)
    for both Premium Amount and Coverage Amount predictions.
    - Interpretability: Ensuring the model provides actionable insights that can be
    explained in non-technical terms.
### CITATION:
    - Innowise. "Exploring the Power of Data Analytics in the Insurance Industry." Innowise, 11
    Jan. 2024, innowise.com/blog/data-analytics-for-insurance/.