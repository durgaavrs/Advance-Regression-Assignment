# Surprise Housing - Advanced regression assignment
>   A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. The company is looking at prospective properties to buy to enter the market.


## Table of Contents
* General Info
* Technologies Used
* Conclusions
* Acknowledgements

<!-- You can include any other section that is pertinent to your problem -->

## General Information
-   A US-based housing company named Surprise Housing has decided to enter the Australian market. The company is looking at prospective properties to buy to enter the market.

- Determine the significant variables in predicting the price of a house
  How those variables describe the price of a house
  Determine the optimal value of lambda for Ridge and Lasso regression.

- Dataset - Company has collected a data set from the sale of houses in Australia.


## Conclusions
-  There are quite a number of variables and we used Ridge, Lasso regression for creating models so regularization and overfiting issues will be addressed.
-  Optimal value of alpha was 3 and 0.0001 for Ridge and Lasso respectively
-  The Train and test datasets performed well on Lasso (marginally better) than Ridge and hence we will go with Lasso model.
-  The significant variables in predicting the price of the house are
    GrLivArea
    OverallQual_Excellent
    TotalBsmtSF
    OverallQual_VGood
    OverallQual_VExcellent
    LotArea
    Neighborhood_Crawfor
    BsmtFullBath
    OverallCond_Excellent
    Neighborhood_NoRidge

## Technologies Used
- Python 3.0


## Acknowledgements
Give credit here.
- Upgrad - Thanks for sharing the dataset and details related to the dataset.


## Contact
Created by [@durgaavrs] - feel free to contact me!
