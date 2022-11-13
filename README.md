# Bangalore-House-Price-Prediction
Dataset is downloaded from here: https://www.kaggle.com/amitabhajoy/bengaluru-house-price-data


Notebook used for reference : https://github.com/codebasics/py/blob/master/DataScience/BangloreHomePrices/model/banglore_home_prices_final.ipynb

# Improved the cross validation score from 85% to 88%
- For dimentionality reduction techinque, any location having less than 50 data points are marked as "Other". This way number of categories can be reduced by huge amount. Later on when we do one hot encoding, it has helped us with having fewer dummy columns and reducing the size of dataframe. Cross validation score was improved because of reducing the size and complexity of dataframe.
