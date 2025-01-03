# Customer Sentiment Analysis and Predictive Modeling
This project focuses on analyzing customer feedback data through sentiment analysis and predictive modeling. The goal is to understand customer sentiment and identify factors influencing product scores, using both text-based and structured data for a comprehensive analysis.

## Project Overview
This project uses customer reviews and related product data to:
  •Perform sentiment analysis on customer reviews.
  •Extract key features from both the text data and structured product data.
  •Build predictive models to predict product scores and assess the sentiment of reviews.
  •Derive insights from the models and suggest strategies for improving product offerings.

## Methodology
1. Data Preprocessing:
•Clean and preprocess the text data from customer reviews.
•Handle missing values and scale numerical features.
•Extract key features such as sentiment scores, text length, and helpfulness ratio.

2. Sentiment Analysis:
•Analyze the sentiment of customer reviews using a pre-trained model to classify sentiment as positive, negative, or neutral.
•Convert sentiment into a numerical score to be used in predictive models.

3. Feature Engineering:
•Extract relevant features from text (e.g., sentiment scores, key phrases).
•Calculate structured features (e.g., helpfulness ratio, text length) to complement the analysis.

4. Predictive Modeling:
•Train multiple machine learning models including XGBoost, Gradient Boosting, and Neural Networks.
•Evaluate the models using appropriate metrics and assess feature importance.

## Features
•Sentiment analysis of customer reviews using text-based models.
•Extraction of key features from text (e.g., sentiment scores, key phrases).
•Predictive models for product scores based on customer sentiment and review characteristics.
•Visualizations for data exploration and feature relationships.
•Insights into improving customer satisfaction and product strategies.

## Model Training and Evaluation
Models Used:
•XGBoost: A gradient boosting framework used for classification and regression tasks, known for its performance and efficiency.
•Gradient Boosting: A powerful ensemble method for both classification and regression tasks, optimized for predictive accuracy.
•Neural Networks: A deep learning model used to capture complex relationships in the data, particularly useful for large datasets with intricate patterns.

### Model Evaluation:
•RMSE (Root Mean Squared Error) (for regression tasks).
•Feature Importance (for XGBoost and Gradient Boosting models).

## Results and Insights
•Sentiment and Product Scores:

    •Positive sentiment is strongly correlated with higher product scores, while negative sentiment correlates with lower scores.
    •Reviews with positive sentiment tend to have higher predictive scores from the models, indicating the importance of customer satisfaction.
    
•Helpfulness Ratio:

    •The helpfulness ratio, which measures the proportion of people finding a review useful, is a key factor. Reviews with a higher helpfulness ratio are more likely to provide valuable insights and have higher predictive scores.
    •This feature showed significant weight in the model, helping differentiate between informative and less helpful reviews.

•Text Length:

    •Longer reviews tend to be more detailed and may provide more context about a product, leading to higher product scores.
    •Reviews with greater text length are also correlated with higher model prediction accuracy, as they often contain more relevant information.

•Feature Importance:

    •The analysis revealed that sentiment scores and helpfulness ratios are among the most significant features for predicting product scores.
    •Sentiment analysis features (both sentiment labels and sentiment scores) played a central role in driving model predictions.

### Model Performance:
•The XGBoost model [XGBoost MSE: 1.43  XGBoost R2: 0.14] outperformed other models, delivering high accuracy in predicting product scores based on customer reviews.
•The Neural Network model performed poorly, especially due to size of data [Neural Network MSE: 1.75  Neural Network R2: -0.06]
•These insights can be used to improve product strategies, focusing on customer satisfaction, optimizing product features, and prioritizing helpful customer reviews.
