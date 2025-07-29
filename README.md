# Future Sales Prediction Project

## Description of the project (Updated July 29, 2025)

![Illustration photo of sales growth](*github_link* "Source: Pixabay")

_Source: [Pixabay](https://pixabay.com/illustrations/statistics-finance-trading-8787079/)_

An ongoing data and machine learning project in Python, using the [Predict Future Sales Dataset](https://www.kaggle.com/competitions/competitive-data-science-predict-future-sales/) from Kaggle. Since the dataset was also used for a past Kaggle data science competition, an additional goal of this project is crafting a model that could maximize prediction performance, using the metric Root Mean Squared Error (RMSE).

The project involved daily historical sales data of 1C Company, a Rusian software firm. The ```sales_train.csv``` file contained the majority of the data, including shop ID, item ID, item price, and sales of the item at different days. Other data files contained additional information about the items and the shops, which I mainly used for data analysis and visualization.

Given the daily historical sales data from January 2013 to October 2015, I needed to predict sales for each combination of a shop and an item for the next month, November 2015.

I used popular Python libraries such as NumPy, Pandas, Matplotlib, and Seaborn to analyze the data, so that I could get an overall view of . For the predictions part, I tested different regression models, including linear-based models (such as Linear Regression, Ridge, Lasso, and ElasticNet) as well as tree-based ensemble learning algorithms in order to maximize performance.

The set of data files, directly downloaded from Kaggle in July 2025, is stored in the [data](https://github.com/thaianle/future-sales-prediction/tree/main/data) folder.

The analysis can be found in the [prediction_code.ipynb](https://github.com/thaianle/future-sales-prediction/blob/main/prediction_code.ipynb) file, and my submission on Kaggle is frequently updated in the [thai_an_le_submission.csv](https://github.com/thaianle/future-sales-prediction/blob/main/thai_an_le_submission.csv) file.

This project also outlined my approach to some of the data challenges, including but not limited to: re-formatting and encoding recurring datetime data, encoding categorical variables with high cardinality (containing many different categories), joining DataFrames with pandas, and tuning hyperparameters.

_Reference:_

Alexander Guschin, Dmitry Ulyanov, inversion, Mikhail Trofimov, utility, and Μαριος Μιχαηλιδης KazAnova. Predict Future Sales. https://kaggle.com/competitions/competitive-data-science-predict-future-sales, 2018. Kaggle.