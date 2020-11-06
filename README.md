# Project_House_Prices
> The study objective: House price analysis.


## Table of contents
* [General info](#general-info)
* [Yearly prices](#image)
* [Packages and approaches](#R)
* [Status](#status)
* [Inspiration](#inspiration)
* [Files] (#files) 

## General info
House features such as location, size, year ... play important role in defining the house prices. Can we udnerstand the features relationships and the price?

## Yearly prices
the increase in the house prices can be seen in most cases as we move towards future.

socal.org
![Yearly prices](./Houses.jpg) 


## Packages and approaches
Pandas, numpy, matplotlib and seaborn.


#### Code Example - Year vs house price

	for feature in year_feature:
    if feature !='YrSold':
        data=df.copy()
        #compare the difference between yearsold 
        data[feature]=data['YrSold']-data[feature]
        plt.scatter(data[feature], data['SalePrice'])
        plt.xlabel(feature)
        plt.ylabel('YrSold')
        plt.show()
    
## Status
Project is ongoing.

## Inspiration
The importance of unknown unknonws (e.g., pandemics) on the house prices.

## Files 
Ref codes: https://github.com/melaniaAB/Project_House_Prices.git



