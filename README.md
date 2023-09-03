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

<p align="justify"> The primary goal of this project is to determine which variables have the most significant influence on the price of a house. To achieve this, we need to suggest the parameters we believe have the most impact on our dependent variable, "SalePrice," and then test them during the data analysis process.
    
Spatial variables
- 'TotalBsmtSF': Area of the basement
- 'GrLivArea': Total area of living space in the house

Construction variables
- 'OverallQual': Overall quality of the construction materials and the final design of the house
- 'YearBuilt': The year in which the house was built



## Data Analysis

<p align="justify"> The Jupyter Notebook was the tool utilized for conducting exploratory data analysis. The documentation was incorporated within the notebook, along with calculations and graphs. One of the main advantages of using Jupyter Notebooks is that all data analysis tasks, including visualization, documentation, and calculations, can be performed in a single file. So please head to the notebook "House Pricing in California_Data Analysis with Python.ipynb". </p>

[**Link here**](https://github.com/AlvaroM99/Python---House-Pricing-in-California-Analysis/blob/main/House%20Pricing%20in%20California__Data%20analysis%20with%20Python.ipynb).

## Conclusions

Let's expose the conclusions of the data analysis:

+ Overall quality, Housing area, Basement surface, and Garage area are strongly correlated with SalePrice.

- Year of construction and Bath quality are somehow related to the Sale price, however, its dependency is lower.

+ The sale price distribution is right-skewed and has a strong kurtosis. This means that prices concentrate on the price range basis.

* <p align="justify"> Whereas the housing area ('GrLivArea') has a linear relationship with the sale price, the basement area ('TotalBsmtSF') has kind of an exponential relationship (a slight increase of the basement area causes the house price to increase disproportionately).

- <p align="justify"> It's worth noting that the sale price of a house is closely linked to its quality ('OverallQual'). As the quality of the house improves, the range of sale prices also widens. This suggests that higher-quality houses tend to have more variability in their sale prices.

+ <p align="justify"> It seems that the cost of housing tends to rise as it gets newer, though the correlation between the sale price and year of construction is not as strong as with other factors. This could be due to a small but consistent linear increase, which may be influenced by the steadily rising inflation.

* <p align="justify"> It is interesting to note the upward trend in housing prices from the early 2000s to the peak in 2008, which was caused by the housing bubble. After the crisis, housing prices experienced a drastic drop. This pattern can also be seen in other years when comparing SalePrice and YearBuilt, but the most significant example is the 2008 housing bubble.

- <p align="justify"> The scatter plot concerning 'SalePrice' and 'YearBuilt' also reveals more insights that were impossible to see in the box plot graphed before. At the bottom of the 'dots cloud,' we see what appears to be a shy exponential function. This tendency can also be seen in the 'dots cloud' upper limit. These insights might be related to the fact that very old houses have the attraction of antiquities and history, on the other hand, newer houses built with fresh designs and better materials are significantly more expensive. The upper tendency increases faster than the bottom one, probably due to an increasingly saturated real estate market.

+ <p align="justify"> The scatter plot between 'TotalBsmtSF' and 'GrLiveArea' unveils a new obvious but interesting insight. In the graph, we can see some dots drawing a perfectly straight line, which almost acts like a border. It makes sense that the majority of the dots stay below that line, as the basement area can be equal to or smaller than the above living area, but it is very rare to find a basement bigger than the actual living area.
