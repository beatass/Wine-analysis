# Wine analysis

The project concerns the prediction of what makes the wine taste good using Machine Learning algorithms. 

## Motivation

In this study the exploratory analysis (EDA) with visualizations of wine quality dataset as well as different ML algorithms, such as Logistic Regression, KNN, Naive Bayes, SVM, Decision Tree, XGBoost and Random Forest have been performed to make a relevant predictions.

#### The project is created with Python libraries:

 -  scikit-learn/pandas/numpy.

## Recap

After examination if our dataset has any missing values and checking the features within it and their data types, we begin with the EDA analysis. 

#### For red wine

The box and violin plots analysis of 'quality' target variable showed that very high (above 7) and very low (below 4) quality of analyzed red wine is quite rare in our data. The multivariate visualization showed existence of co-correlations between particular features after plotting a heat map of them. A relevant scatter-plots show how the values of partiular variables change with each other. One can see a positive or negative correlations between them.

We have apllied ML models to make a predictions of wine quality and our analysis showed that the best prediction is given by Random Forest model with accuracy score equal to 87 % while the poorest one is given by Naive Bayes model with the accuracy score equal to 80 %.

Model | Accuracy
------------ | ------------- 
Random Forest | 0.87
Logistic Regression | 0.83
KNN | 0.83
SVM | 0.82
Naive Bayes | 0.80


#### For white wine

The box plots analysis showed many outliers for a quite few variables. To remove them the Tukey's method has been used. This way an outlier is calculated as 1.5 times interquartile range (IQR). To get more insights we have also plotted a heat map of co-correlations between features (after outliers extraction) and we have explored them in more details. To better visualize relationships of discrete values we have used a bar plots while to visualize a continuous ones we have used a scatter plots.

We have apllied ML models to make a predictions of wine quality and our analysis showed that the best prediction is given by Random Forest model with the accuracy score equal to 86 % while the poorest one is given by Naive Bayes model with the accuracy score equal to 66 %. We have also used a GridSearch to find the best hyperparameters of Random Forest model and to check if that result can be improved. By virtue the GridSearch method we did not manage to improve the result since we got a slightly worse one, with the accuracy score equal to 83%.

Model | Accuracy
------------ | ------------- 
Random Forest | 0.86
KNN | 0.79
Decision Tree | 0.77
XGBoost Classifier | 0.76
Logistic Regression  | 0.75
SVM | 0.73
Naive Bayes | 0.66

#### Running the project:

* To run this project use Jupyter Notebook or Google Colab.

## Files in this repository

1. The red_wine_analysis.ipynb file contains all the codes, plots and relevant descriptions of conducted analysis.
2. The white_wine_analysis.ipynb file contains all the codes, plots and relevant descriptions of conducted analysis.

## The dataset origin

The dataset can be found at Kaggle but is also public available for research in the work of Cortez et al. from 2009 and contains two datasets with red and white wine samples.,

P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553. ISSN: 0167-9236.

Available at: [@Elsevier] http://dx.doi.org/10.1016/j.dss.2009.05.016 [Pre-press (pdf)] http://www3.dsi.uminho.pt/pcortez/winequality09.pdf [bib] http://www3.dsi.uminho.pt/pcortez/dss09.bib

## Relevant information

The dataset consists of the following input variables:

- citric acid (g / dm^3);
- free sulfur dioxide (mg / dm^3);
- pH;
- fixed acidity (tartaric acid - g / dm^3);
- residual sugar (g / dm^3);
- total sulfur dioxide (mg / dm^3);
- sulphates (potassium sulphate - g / dm3);
- volatile acidity (acetic acid - g / dm^3);
- chlorides (sodium chloride - g / dm^3);
- density (g / cm^3);
- alcohol (% by volume). 

And output variable (based on sensory data):

- quality (score between 0 and 10).


## Additional information

The dataset contains no missing atribute values with 1599 instances of red wine and 4898 of white wine. Several of the attributes may be correlated, thus it makes sense to apply some sort of feature selection.  

