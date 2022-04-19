# housePricePrediction
With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, predict the final price of each home.
<br>
<br>
Given data delivers NUMERIC aas well as CATEGORICAL features describing all the relevant information related to houses in Ames, Iowa. Following project tries to predict the target variable, i.e. <b>SalePrice</b> based on remaining independent variable.
<br>
<br>
The Project is split into 3 parts:<br><br>
<b>Data Analysis and Exploration</b><br>
Plot Correlation Matrix to visualize relationship across independent variables as well as their relationship with target vraiable<br> 
Normalize target variable distribution to reduce the effect of outliers on model training<br>
<br>
<b>Feature Engineering</b>
Data Cleaning<br>
Implemented <b>TSNE</b> and <b>PCA</b> to visualize multivariate data in 2D space<br>
Introduced new features such as haspool, hasfireplace, Total_sqr_footage, Total_Bathrooms, etc.<br>
<br>
<b>Regression Models</b><br>
Multivariate Linear Regression, Lasso CV, Ridge CV, <b>ElasticNet CV</b><br>
Blending of models<br>
<br>

### Result:
Model: RSME<br>
Ridge: 0.1081<br>
LASSO: 0.1065<br>
Elastic net: 0.1067<br>

<b>Blended Model</b>: 0.4*Ridge + 0.2*LASSO + 0.4*ElasticNet<br>

RMSLE score on train data: 0.09624111606162275<br>

<b>Lowest RSME (0.09624)<b> is achieved for blended model
    
