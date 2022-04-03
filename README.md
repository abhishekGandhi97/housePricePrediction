# housePricePrediction
With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, predict the final price of each home.

### Features
~~~
NUMERIC FEATURES
~~~
LotFrontage
LotArea
MasVnrArea
BsmtFinSF1
BsmtFinSF2
BsmtUnfSF
TotalBsmtSF
1stFlrSF
2ndFlrSF
LowQualFinSF
GrLivArea
BsmtFullBath
BsmtHalfBath
FullBath
HalfBath
BedroomAbvGr
KitchenAbvGr
TotRmsAbvGrd
Fireplaces
GarageYrBlt
GarageCars
GarageArea
WoodDeckSF
OpenPorchSF
EnclosedPorch
3SsnPorch
ScreenPorch
PoolArea
MiscVal

~~~
Below features are numeric in datatype but represents dates. These features can be manipulated to important numeric features.
~~~
MoSold
YrSold
YearBuilt
YearRemodAdd

~~~
CATEGORICAL FEATURES
~~~
MSSubClass
OverallQual
OverallCond
MSZoning
Street
Alley
LotShape
LandContour
Utilities
LotConfig
LandSlope
Neighborhood
Condition1
Condition2
BldgType
HouseStyle
RoofStyle
RoofMatl
Exterior1st
Exterior2nd
MasVnrType
ExterQual
ExterCond
Foundation
BsmtQual
BsmtCond
BsmtExposure
BsmtFinType1
BsmtFinType2
Heating
HeatingQC
CentralAir
Electrical
KitchenQual
Functional
FireplaceQu
GarageType
GarageFinish
GarageQual
GarageCond
PavedDrive
PoolQC
Fence
MiscFeature
SaleType
SaleCondition


~~~ 
Note:
cateorical features will require feature tranformation and feature engineering as apart from Randomm forest model all other model require data in numeric format 
~~~
