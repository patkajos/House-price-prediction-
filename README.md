# Modeling house price prediction

# data description

The project consistes in building models susceptible to predict house sale prices with better accuracy with data imported from kaggo. 2 dataset with asymetric size gathered for train and test in csv format were downloaded from kaggo wich is a open source for data. The train dataset makes up 2258 rows and 81 coluumns while the test dataset makes up 661 columns , 81 rows

# data cleaning and wranging

corrupted Data were suject to subtantial cleaning meaning removing missing values and fixing inconsistent data type each columns.
defining the proportion of missing value and plot them using missingno.
deleting missing values using the function dropna
checking missing values and data type in every signle cloumns. once Data cleaned and desinffected, new dataframe is inplaced and combined from train and test dataset

# data exploration & visualization

Since we are working on building a model prediction for our sale price for house , finding optimal features to fit our model require clear features visualization in correlation with target(sale price).
visualizing the correlation and defining the coefficient of correlation using sns heatmap for a better feature identification
ploting sale price data and specifying its mean for a better understanding of our target.
Given the fact that , the train and the test dataset contain numeric data and categorical, get_dummies usage turns categorical data into boolean for a better modeling processing

# Model used : linear regression and logistic regression

Due to linearity of selected features from data ,linear regression best fits to predict the sale price using train/split method.
predicting the train dataset and using model on test dataset
defining the metrics for the model
evaluate the modelel using R2, cross validation, MSE
determining the predictive probality of a random house to be sold in jun given its sale price using logistic - regression.
