# Capstone Project Report: Predictive Modeling for Artifacts Classification

## Problem Statement

The Metropolitan Museum of Art possesses a vast collection of artifacts, and classifying them into categories such as whether they are in the public domain or not can be a daunting task. The goal of this project is to build a predictive classification model that can accurately classify artifacts based on various features.

## Approach

### Data Preprocessing:
- Loaded the cleaned dataset 'metdata_cleaned.csv' into a DataFrame.
- Processed categorical variables for dummy encoding.
- Standardized numeric features to have a mean of 0 and a standard deviation of 1.
- Split the dataset into training and testing sets.

### Model Training and Evaluation:
- Trained a Logistic Regression model and a Random Forest classifier.
- Evaluated the models using various performance metrics such as accuracy, precision, recall, F1 score, and ROC-AUC score.
- Compared the performance of both models to determine the best approach.

## Findings

- The Random Forest model outperformed the Logistic Regression model across most performance metrics.
- Random Forest achieved higher accuracy, precision, and F1 score compared to Logistic Regression.
- Logistic Regression had higher recall, suggesting it was better at capturing true positives.

## Ideas for Further Research

- Feature Engineering: Explore additional features or combinations of features that may improve model performance.
- Model Tuning: Experiment with hyperparameter tuning techniques to optimize the models further.
- Ensemble Methods: Investigate ensemble learning techniques such as stacking or boosting to enhance classification performance.

## Recommendations

1. **Deployment of Random Forest Model**: Implement the trained Random Forest model for artifact classification in the Metropolitan Museum of Art's systems to assist with categorization tasks.
2. **Continuous Monitoring and Evaluation**: Regularly monitor the model's performance and update it as new data becomes available to ensure its accuracy and relevance.
3. **Collaboration with Domain Experts**: Collaborate with domain experts within the museum to refine features and improve the model's interpretability and effectiveness in classifying artifacts accurately.

## Conclusion

In conclusion, the predictive modeling approach using Random Forest demonstrates promising results for artifact classification. By deploying this model and following the recommendations outlined above, the Metropolitan Museum of Art can streamline its artifact categorization process and enhance its efficiency in managing its extensive collection.


