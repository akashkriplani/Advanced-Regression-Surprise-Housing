# Predictive Analytics for Real Estate Investment: A Regression Model Approach for Surprise Housing in the Australian Market

## Problem Statement

Surprise Housing, a US-based real estate company, has set its sights on entering the Australian market with a strategic approach to property investment. Leveraging data analytics, the company aims to identify lucrative opportunities by acquiring houses below market value and selling them at a premium. To facilitate this, Surprise Housing has gathered a comprehensive dataset from Australian house sales, presented in the provided [CSV file](./train.csv).

The task at hand is to develop a regression model with regularization techniques to predict the actual values of potential properties. This predictive model will play a pivotal role in aiding decision-making on whether to invest in prospective properties or not. The primary objectives include identifying the significant variables influencing house prices and assessing how effectively these variables explain the variation in house prices.

Additionally, the assignment involves determining the optimal values of lambda for both ridge and lasso regression, contributing to the precision of the predictive model.

## Business Goal

The ultimate goal is to create a robust model that accurately captures the dynamic relationship between independent variables and house prices. This model will serve as a valuable tool for management, enabling a nuanced understanding of price variations and empowering strategic decision-making. By concentrating efforts on areas with high return potential, Surprise Housing aims to optimize its investment strategy in the Australian market. Furthermore, the model will provide insights into the unique pricing dynamics of this new market, offering a comprehensive understanding for effective market penetration and sustained success.

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Recommendations](#recommendations)
- [Acknowledgements](#acknowledgements)

## General Information

## Objectives

The objectives for this project involve building a regression model with regularization techniques to predict house prices in the Australian real estate market using the [dataset](./train.csv). Key goals include identifying significant variables impacting house prices, evaluating the model's effectiveness in explaining price variations, and determining optimal lambda values for ridge and lasso regression. The overarching business goal is to create a robust model that aids strategic decision-making for Surprise Housing, optimizing their investment strategy in the Australian market and providing insights into the unique pricing dynamics of this new market for sustained success.

## Inferences

1. The Ridge Regression model was optimized with a lambda value of 5.0.
2. Lasso Regression achieved its optimal performance with a lambda value of 0.001.
3. Utilizing Ridge Regression:
   1. The model indicates that `Total_Sqr_Footage`, `GrLivArea`, and `TotalBsmtSF` exert the highest positive impact on estimating the sale price of a house.
   2. Positive contributions to the prediction of sale price also come from features like `Total_Bathrooms`, `LotArea`, `OverallQual_Very Excellent`, and `OverallQual_Very Good`, albeit with slightly lower coefficients.
   3. Neighborhood characteristics, specifically `Neighborhood_StoneBr` and `Neighborhood_Crawfor`, significantly influence the determination of house sale prices.
   4. The `OverallCond_Excellent` feature, representing the overall excellent condition of the house, positively influences the predicted sale price.
4. Employing Lasso Regression:
   1. The model highlights the importance of features such as `Total_Sqr_Footage`, `GrLivArea`, and `BsmtUnfSF` in positively impacting the estimation of house sale prices.
   2. Crucial factors influencing sale prices include `OverallQual_Very Excellent` and `OverallQual_Excellent`, both exhibiting substantial positive coefficients.
   3. The presence of the `SaleType_New` feature positively contributes to the predicted sale price, indicating a notable impact from this particular sale type.
   4. Additional positive contributors to the prediction of sale price include features like `OverallQual_Very Good`, `GarageCars`, `Total_Bathrooms`, and `LotArea`, although with slightly lower coefficients.

## Business Recommendations

1. **Prioritize Size and Quality:** Invest in spacious and high-quality properties, as features like `Total_Sqr_Footage` and `OverallQual` significantly impact house prices.

2. **Target Desirable Neighborhoods:** Focus on neighborhoods like `StoneBr` and `Crawfor`, identified by regression models, to maximize returns on investments.

3. **Consider Bathrooms and Condition:** Properties with ample bathrooms and excellent overall conditions are likely to command higher prices; factor these into investment decisions.

4. **Explore New Construction:** Investigate opportunities in new developments or properties labeled as "New" in the sale type category, aligning with the market trend favoring new constructions.

5. **Optimize Garage Space:** Properties with sufficient garage capacity, emphasized by regression models, appeal to buyers and contribute to overall property value. Consider investing in garage improvements.

## Technologies Used

- [Python](https://www.python.org/) - version 3.11.4
- [Matplotlib](https://matplotlib.org/) - version 3.7.1
- [Numpy](https://numpy.org/) - version 1.24.3
- [Pandas](https://pandas.pydata.org/) - version 1.5.3
- [Seaborn](https://seaborn.pydata.org/) - version 0.12.2
- [Scikit-Learn](https://scikit-learn.org/stable/) - version 1.3.0

## Acknowledgements

- This project was inspired by live session of upGrad on Advanced regression by Amit Pandey
- UpGrad tutorials on Advanced Regression on the learning platform

## Contact

Created by [@akashkriplani](https://github.com/akashkriplani)
