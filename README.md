# House Price Prediction
> House price prediction model creation using regularized regression model


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.
- The company is looking at prospective properties to buy to enter the market. A regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not has to be build.

- The company wants to know:
    - Which variables are significant in predicting the price of a house, and
    - How well those variables describe the price of a house.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Ridge and Lasso regressions are used to obtain the regularized model.
- An accuracy of 91% (Ridge) and 90% (Lasso) is obtained on unseen test data
- Following are some of the top predictors as per ridge regression
    - GrLivArea          
    - OverallQual            
    - 1stFlrSF          
    - BsmtFinSF1         
    - TotalBsmtSF           
    - Neighborhood_NridgHt    
    - 2ndFlrSF               
    - GarageArea             
- Following are some of the top predictors as per Lasso regression
    - GrLivArea               
    - OverallQual             
    - BsmtFinSF1              
    - Neighborhood_NridgHt     
    - HouseAge                
    - GarageArea               
    - OverallCond            
    - BsmtExposure_Gd         
     
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas 1.4.2
- seaborn 0.11.2
- matplotlib 3.5.1
- sklearn 1.0.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project is done as part of Execution PG on ML & AI from upgrade with partnership with IIITB
- This project was based on [this tutorial](https://github.com/ContentUpgrad/Advanced-Regression).


## Contact
Created by [@vighu0710] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->