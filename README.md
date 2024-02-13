# Conversion Rate Challenge

## Project Description
This project addresses the challenge of predicting newsletter subscription conversion rates for the www.datascienceweekly.org website, an essential task for understanding and enhancing user engagement. By leveraging machine learning techniques, we aimed to predict whether a visitor would subscribe to the newsletter based on a set of user information. The project not only focused on building an accurate predictive model but also on identifying key factors that influence user decisions, thereby providing actionable insights to improve conversion rates.

## Data Overview
The dataset comprises user interaction data with the website, including features such as page views, time spent on the site, user demographics, and other relevant metrics that could influence a user's decision to subscribe to the newsletter. The conversion_data_train.csv file served as the basis for training and validating our models, while conversion_data_test.csv allowed us to test our model's predictive power on unseen data.

## Methodological Approach
We embarked on this challenge by exploring several machine learning models:

Initial Model Exploration:

  * Logistic Regression: Chosen for its simplicity and interpretability, serving as our baseline.
  * Random Forest: Leveraged for its robustness to overfitting and ability to handle complex interactions between features.
  * Support Vector Classifier (SVC): Selected for its effectiveness in high-dimensional space.
    
These models were rigorously evaluated using confusion matrices and the F1 score to ensure a balance between precision and recall, critical for the project's success.

## Model Improvement:

* Hyperparameter Optimization: Applied grid search to fine-tune each model's settings, enhancing their predictive capabilities.
* Ensemble Techniques: Explored bagging, boosting, and voting methods to improve accuracy and robustness, with a focus on extracting the best performance possible.
Despite these efforts, logistic regression remained the standout model, highlighting the importance of feature relevance and model suitability for the given task.

## Insights and Key Takeaways
The analysis of the logistic regression model's parameters provided deep insights into user behavior and the factors most predictive of newsletter subscription. Features indicating user engagement, such as time spent on the website and interaction with key content, were among the top predictors, suggesting that enhancing user experience and content relevance could significantly impact conversion rates.


## How to Use
* Ensure Python and Jupyter Notebook are installed.
* Install dependencies: pandas, numpy, scikit-learn, matplotlib.
* Follow the steps in conversion_rate.ipynb, from data loading and preprocessing to model evaluation and insights derivation.
## Dependencies
* pandas
* numpy
* scikit-learn
* matplotlib
