# Exploratory Data analysis on weather dataset

* This repository contains the code of exploratory data analysis in which i used several techniques to handle null values , outliers , duplicate values
  * IQR proximity - IQR is used to handle outliers when the distribution of data is skewed . however, if the data is normal distribution we can use Z- scores method
  * Handling Null values - as per the % of null values , it should be treated .  In this is notebook i used median imputation and mode impitation to fill the null values
    since the data is skewed , i used median imputation . We can also use CCA (complete case analysis) where column whith < 5% missing values can be removed from the data
  * Outlier Treatmant - i used capping method and trimming method we handle the outliers 
