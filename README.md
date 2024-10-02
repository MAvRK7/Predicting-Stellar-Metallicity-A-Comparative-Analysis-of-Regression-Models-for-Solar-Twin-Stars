# Predicting-Stellar-Metallicity-A-Comparative-Analysis-of-Regression-Models-for-Solar-Twin-Stars

Abstract

The research focuses on determining the metallicity ([Fe/H]) predicted in the
solar twin stars by using various regression modeling techniques which are,
Random Forest, Linear Regression, Decision Tree, Support Vector, and Gradient Boosting. The data set that is taken into account here includes Stellar
parameters and chemical abundances derived from a high-accuracy abundance
catalog of solar twins from the GALAH survey. To overcome the missing values, intensive preprocessing techniques involving, imputation are done. Each
model will subjected to training using different critical observables, which include,
Mean Squared Error(MSE), Mean Absolute Error(MAE), Root Mean Squared
Error(RMSE), and R-squared(R²). Modeling is done by using, different feature sets like temperature: effective temperature(Teff), surface gravity: log g of
14 chemical abundances namely, (([Na/Fe], [Mg/Fe], [Al/Fe], [Si/Fe], [Ca/Fe],
[Sc/Fe], [Ti/Fe], [Cr/Fe], [Mn/Fe], [Ni/Fe], [Cu/Fe], [Zn/Fe], [Y/Fe], [Ba/Fe])).
The target variable considered is the metallicity ([Fe/H]).
The findings indicate that the Random Forest model achieved the highest accuracy, with an MSE of 0.001628 and an R-squared value of 0.9266. The results
highlight the efficacy of ensemble methods in handling complex datasets with high
dimensionality. Additionally, this study underscores the importance of selecting appropriate regression models for astronomical data analysis, providing a foundation for future research in predicting stellar properties with machine learning
techniques.

Keywords: Stellar Metalicity, Random Forest,Linear Regression, Decision Tree,
Support Vector, and Gradient Boosting

Introduction

Stellar metallicity is an important, commonly measured parameter, usually represented by a number, of so-called [Fe/H]. It is a basic element of astrophysics that governs the way stars and galaxies have formed and it is important for understanding their histories. Stellar metallicity can serve as a predictor of the age of stars. This paper focuses on predicting the metallicity of solar twin stars (this is a collection of stars that have many important characteristics resembling the Sun) through the application of regression models. This study utilizes a dataset from the GALAH survey, specifically the high precision abundance catalog of solar twins, as detailed by Walsen et al. (2024). The dataset, produced using The Cannon algorithm, comprises approximately 38,320 solar twin stars, providing detailed measurements of stellar parameters such as effective temperature, surface gravity, and metallicity, along with 14 different chemical abundances. The rich and extensive nature of this dataset makes it ideal for training and testing regression models aimed at predicting stellar metallicity. The goal of this research is to see which of the five regression models (Random Forest, Linear Regression, Decision Tree, Support Vector, and Gradient Boosting) gives a better result in predicting stellar metallicity. An overall approach is used for implementing this project in which preprocessing on the data is handled, including dealing with missing values using imputation. The training of each of the regression models is done next and analyzing results for each reporting metric (Mean Squared Error (MSE), Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R2)) is performed. By systematically comparing these models, this study seeks to identify the most effective approach for predicting stellar metallicity. This comparative analysis not only contributes to the field of astrophysics by enhancing the accuracy of stellar parameter predictions but also demonstrates the potential of machine learning techniques in astronomical research. The findings of this research will provide valuable insights into the chemical composition and evolution of solar twin stars, offering a benchmark for future studies in the prediction of stellar properties using regression models.


My contribution:
I developed the code for Gradient Boosting, data handling and comparison of the developed model with existing literature.
