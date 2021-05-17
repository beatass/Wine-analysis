# Red-wine-analysis

The project concerns the prediction of what makes the red wine taste good using Machine Learning approaches. 

In this study the exploratory analysis (EDA) with visualizations of red wine quality dataset has been performed.

Project is created with Python libraries:

 -  scikit-learn/pandas/numpy.

## Files in this repository

1. The EDA_analysis.ipynb file contains all the codes, plots and relevant descriptions of conducted analysis.

## The dataset origin

The dataset can be found at Kaggle but is also public available for research in the work of Cortez et al. from 2009 and contains two datasets with red and white wine samples.,

P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553. ISSN: 0167-9236.

Available at: [@Elsevier] http://dx.doi.org/10.1016/j.dss.2009.05.016 [Pre-press (pdf)] http://www3.dsi.uminho.pt/pcortez/winequality09.pdf [bib] http://www3.dsi.uminho.pt/pcortez/dss09.bib

## Relevant information

The dataset consists of the following input variables:

- citric acid (g / dm^3);
- free sulfur dioxide (mg / dm^3);
- pH;
- quality (score between 0 and 10);
- fixed acidity (tartaric acid - g / dm^3);
- residual sugar (g / dm^3);
- total sulfur dioxide (mg / dm^3);
- sulphates (potassium sulphate - g / dm3);
- volatile acidity (acetic acid - g / dm^3);
- chlorides (sodium chloride - g / dm^3);
- density (g / cm^3);
- alcohol (% by volume) Output variable (based on sensory data).

Description of the particular input variables:

- citric acid: found in small quantities, citric acid can add 'freshness' and flavor to wines;
- free sulfur dioxide: the free form of SO2 exists in equilibrium between molecular SO2 (as a dissolved gas) and bisulfite ion; it prevents microbial growth and the oxidation of wine;
- pH: describes how acidic or basic a wine is on a scale from 0 (very acidic) to 14 (very basic); most wines are between 3-4 on the pH scale;
- fixed acidity: most acids involved with wine or fixed or nonvolatile (do not evaporate readily);
- residual sugar: the amount of sugar remaining after fermentation stops, it's rare to find wines with less than 1 gram/liter and wines with greater than 45 grams/liter are considered sweet;
- total sulfur dioxide: amount of free and bound forms of S02; in low concentrations, SO2 is mostly undetectable in wine, but at free SO2 concentrations over 50 ppm, SO2 becomes evident in the nose and taste of wine;
- sulphates: a wine additive which can contribute to sulfur dioxide gas (S02) levels, wich acts as an antimicrobial and antioxidant;
- volatile acidity: the amount of acetic acid in wine, which at too high of levels can lead to an unpleasant, vinegar taste;
- chlorides: the amount of salt in the wine;
- density: the density of water is close to that of water depending on the percent alcohol and sugar content;
- alcohol: the percent alcohol content of the wine.

Description of the output variable:

- quality (score between 0 and 10).

## Additional information

The dataset contains no missing atribute values with 1599 instances of red wine. Several of the attributes may be correlated, thus it makes sense to apply some sort of feature selection.
