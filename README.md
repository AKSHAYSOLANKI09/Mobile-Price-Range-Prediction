# Mobile-Price-Range-Prediction--Classification-Problem
In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone(eg:- RAM, Internal Memory, etc) and its selling price. In this problem, we do not have to predict the actual price but a price range indicating how high the price is


# Attribute Information:
* **Battery_power** - Total energy a battery can store in one time measured in mAh
* **Blue** - Has bluetooth or not
* ***Clock_speed*** - speed at which microprocessor executes instructions
* ***Dual_sim*** - Has dual sim support or not
* ***Fc*** - Front Camera mega pixels
* ***Four_g*** - Has 4G or not
* ***Int_memory*** - Internal Memory in Gigabytes
* ***M_dep*** - Mobile Depth in cm
* ***Mobile_wt*** - Weight of mobile phone
* ***N_cores*** - Number of cores of processor
* ***Pc*** - Primary Camera mega pixels
* ***Px_height*** - Pixel Resolution Height
* ***Px_width*** - Pixel Resolution Width
* ***Ram*** - Random Access Memory in Mega Bytes
* ***Sc_h*** - Screen Height of mobile in cm
* ***Sc_w*** - Screen Width of mobile in cm
* ***Talk_time*** - longest time that a single battery charge will last when you are
* ***Three_g*** - Has 3G or not
* ***Touch_screen*** - Has touch screen or not
* ***Wifi*** - Has wifi or not
* ***Price_range*** - This is the target variable with value of 
* 0(low cost), 
* 1(medium cost),
* 2(high cost) and
* 3(very high cost).
* Thus our target variable has 4 categories so basically it is a Multiclass classification problem.

# Conclusions:
* We Started with Data understanding, data wrangling, basic EDA where we found the relationships,
trends between price range and other independent variables.
* We selected the best features for predictive modeling by using K best feature selection method using
Chi square statistic.
* Implemented various classification algorithms, out of which the SVM(Support vector machine) algorithm
gave the best performance after hyper-parameter tuning with 98.3% train accuracy and 97 % test
accuracy.
* XG boost is the second best good model which gave good performance after hyper-parameter tuning
with 100% train accuracy and 92.25% test accuracy score.
* KNN gave very worst model performance.
* We checked for the feature importance's of each model. RAM, Battery Power, Px_height and px_width
contributed the most while predicting the price range.
