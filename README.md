# housePricePrediction
With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, predict the final price of each home.

## Features

#### NUMERIC FEATURES
LotFrontage<br>
LotArea<br>
MasVnrArea<br>
BsmtFinSF1<br>
BsmtFinSF2<br>
BsmtUnfSF<br>
TotalBsmtSF<br>
1stFlrSF<br>
2ndFlrSF<br>
LowQualFinSF<br>
GrLivArea<br>
BsmtFullBath<br>
BsmtHalfBath<br>
FullBath<br>
HalfBath<br>
BedroomAbvGr<br>
KitchenAbvGr<br>
TotRmsAbvGrd<br>
Fireplaces<br>
GarageYrBlt<br>
GarageCars<br>
GarageArea<br>
WoodDeckSF<br>
OpenPorchSF<br>
EnclosedPorch<br>
3SsnPorch<br>
ScreenPorch<br>
PoolArea<br>
MiscVal<br>

<b>Note</b><br>
Below features are numeric in datatype but represents dates. These features can be manipulated to important numeric features.<br>

MoSold<br>
YrSold<br>
YearBuilt<br>
YearRemodAdd<br>


### CATEGORICAL FEATURES

MSSubClass<br>
OverallQual<br>
OverallCond<br>
MSZoning<br>
Street<br>
Alley<br>
LotShape<br>
LandContour<br>
Utilities<br>
LotConfig<br>
LandSlope<br>
Neighborhood<br>
Condition1<br>
Condition2<br>
BldgType<br>
HouseStyle<br>
RoofStyle<br>
RoofMatl<br>
Exterior1st<br>
Exterior2nd<br>
MasVnrType<br>
ExterQual<br>
ExterCond<br>
Foundation<br>
BsmtQual<br>
BsmtCond<br>
BsmtExposure<br>
BsmtFinType1<br>
BsmtFinType2<br>
Heating<br>
HeatingQC<br>
CentralAir<br>
Electrical<br>
KitchenQual<br>
Functional<br>
FireplaceQu<br>
GarageType<br>
GarageFinish<br>
GarageQual<br>
GarageCond<br>
PavedDrive<br>
PoolQC<br>
Fence<br>
MiscFeature<br>
SaleType<br>
SaleCondition<br>

<b>Note</b><br>
Cateorical features will require feature tranformation and feature engineering as apart from Randomm forest model all other model require data in numeric format.<br>
