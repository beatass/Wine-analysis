# Red wine analysis

The project concerns the prediction of what makes the red wine taste good using Machine Learning approaches. 

In this study the exploratory analysis (EDA) with visualizations of red wine quality dataset has been performed.

Project is created with Python libraries:

 -  scikit-learn/pandas/numpy.

## Files in this repository

1. The red_wine_analysis.ipynb file contains all the codes, plots and relevant descriptions of conducted analysis.

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

The dataset contains no missing atribute values with 1599 instances of red wine. Several of the attributes may be correlated, thus it makes sense to apply some sort of feature selection.
