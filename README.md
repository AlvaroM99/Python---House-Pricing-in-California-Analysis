# House Pricing in California: Data Analysis with Python
</br>
<p align="center" width="100%">
    <img width="100%" src="https://github.com/AlvaroM99/Python---House-Pricing-in-California-Analysis/assets/129555669/bf7c8f81-c3aa-45e3-9b48-f00ce7b4f15c">
</p>

## Index

- [Overview](https://github.com/AlvaroM99/Python---House-Pricing-in-California-Analysis/tree/main#overview)
- [Guiding Variable over the Sale Price](https://github.com/AlvaroM99/Python---House-Pricing-in-California-Analysis/tree/main#guiding-variables-over-the-sale-price)
- [Data Analysis](https://github.com/AlvaroM99/Python---House-Pricing-in-California-Analysis/tree/main#data-analysis)
- [Conclusions](https://github.com/AlvaroM99/Python---House-Pricing-in-California-Analysis/tree/main#conclusions)


## Overview

<p align="justify"> Despite cyclical recessions, often caused by the real estate market, this continues to be a succulent market. Although the brick crises undermined the belief that a house is a safe investment, investors continue to have confidence in this product. For this reason, housing prices have maintained an upward trend since records began. Therefore, in order to predict property prices, this data analysis focuses on finding the factors that most influence housing prices in California.



## Guiding Variables over the Sale Price

<p align="justify"> The main quest of this work is to identify which variables are the most influential over the house price. For this purpose, we must propose the parameters that we think have the greatest impact over our dependent variable 'SalePrice' and test them during the data analysis.

Spatial variables
- 'TotalBsmtSF': Area of the basement
- 'GrLivArea': Total area of living space in the house

Construction variables
- 'OverallQual': Overall quality of the construction materials and the final design of the house
- 'YearBuilt': The year in which the house was built



## Data Analysis

<p align="justify"> The tool used for this exploratory data analysis has been the Jupyter Notebook; the documentation has been done throughout the notebook, alongside the calculations and graphs. We take advantage of the main feature of Jupyter Notebooks, gathering all the data analysis tasks (calculations, visualization, and documentation) in a single file. So please head to the notebook "House Pricing in California_Data Analysis with Python.ipynb". </p>

[**Link here**](https://github.com/AlvaroM99/Python---House-Pricing-in-California-Analysis/blob/main/House%20Pricing%20in%20California__Data%20analysis%20with%20Python.ipynb).

## Conclusions

Let's expose the conclusions of the data analysis:

+ Overall quality, Housing area, Basement surface, and Garage area are strongly correlated with SalePrice.

- Year of construction and Bath quality are somehow related to the Sale price, however, its dependency is lower.

+ The sale price distribution is right-skewed and has a strong kurtosis. This means that prices concentrate on the price range basis.

* <p align="justify"> Whereas the housing area ('GrLivArea') has a linear relationship with the sale price, the basement area ('TotalBsmtSF') has kind of an exponential relationship (a slight increase of the basement area causes the house price to increase disproportionately).

- <p align="justify"> There's a clear linear relationship between the quality of the house ('OverallQual') and the sale price. It's also interesting to point out how as the house quality increases, the boxes' width increases. This implies that the higher the quality of the house there is also greater variability in its sale price.

+ <p align="justify"> There is an upward trend for the price of housing when it is newer, however, the dependency relationship between the sale price and the year of construction is not as critical as with the previous variables. The slight but constant linear increase could be due to the constant increasing inflation.

* <p align="justify"> It is curious to observe how the price of housing increased from the 2000s until it reached an exorbitant maximum in 2008 due to the brick bubble; and as of the year following the outbreak of said crisis, the price of housing plummeted. This behavior can be seen in other years in the SalePrice vs. YearBuilt, but not as well as in 2008.

- <p align="justify"> The scatter plot concerning 'SalePrice' and 'YearBuilt' also reveals more insights that were impossible to see in the box plot graphed before. At the bottom of the 'dots cloud,' we see what appears to be a shy exponential function. This tendency can also be seen in the 'dots cloud' upper limit. These insights might be related to the fact that very old houses have the attraction of antiquities and history, on the other hand, newer houses built with fresh designs and better materials are significantly more expensive. The upper tendency increases faster than the bottom one, probably due to an increasingly saturated real estate market.

+ <p align="justify"> The scatter plot between 'TotalBsmtSF' and 'GrLiveArea' unveils a new obvious but interesting insight. In the graph, we can see some dots drawing a perfectly straight line, which almost acts like a border. It makes sense that the majority of the dots stay below that line, as the basement area can be equal to or smaller than the above living area, but it is very rare to find a basement bigger than the actual living area.
