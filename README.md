# housePricePrediction
With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, predict the final price of each home.
<br>
<br>
Given data delivers NUMERIC aas well as CATEGORICAL features describing all the relevant information related to houses in Ames, Iowa. Following project tries to predict the target variable, i.e. <b>SalePrice</b> based on remaining independent variable.
<br>
<br>
The Project is split into 3 parts:
<br>
*Data Analysis and Exploration 
<br><br>
Plot Correlation Matrix to visualize relationship across independent variables as well as their relationship with target vraiable 
Normalize target variable distribution to reduce the effect of outliers on model training 
<br><br>
*Feature Engineering
<br><br>
Data Cleaning
<br>
Implemented TSNE and PCA to visualize multivariate data in 2D space
<br>
Introduced new features such as haspool, hasfireplace, Total_sqr_footage, Total_Bathrooms, etc.
<br>
<br>
*Regression Models
<br><br>
Multivariate Linear Regression, Lasso CV, Ridge CV, ElasticNet CV
<br>
Blending of models
<br>