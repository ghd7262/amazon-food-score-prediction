# Predict Amazon food scores based on review data

## Objective
This project aims to build models to predict the Amazon food scores based on the customer's reviews. 

### Methods Used
- Data Visualization
- Machine Learning: Logistic Regression, Multinomial Naive Bayes Classifier

### Technologies
- Python
- Numpy, Pandas
- Matplotlib, Seaborn
- Sklearn
- NLTK

## Dataset 
Data is from the Kaggle's 'Amazon Fine Food Reviews' Dataset (https://www.kaggle.com/snap/amazon-fine-food-reviews).
- 9 columns: `UserId`, `ProductId`, `ProfileName`, `HelpfulnessNumerator`, `HelpfulnessDenominator`, `Score`, `Time`, `Summary`, `Text`
- 568454 entries


## Project Description
This proejct aims to build models to predict Amazon food scores based on customer's reviews. Food score ranges from 1 to 5, but food scores or 1 and 5 are considered as bad and good accordingly. We will compare how the models perform based on the Bag of Words model and the TF-IDF model.
