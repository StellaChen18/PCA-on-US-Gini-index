# PCA-on-US-Gini-index

## Task
The task is to investigate how the historical events of the Great Depression, the World War II and the Global Financial Crisis impacts income inequality for the 52 U.S. states. It requires to conduct some preliminary analysis on the data, including data cleaning and providing basic summary and visualization of the data, and conduct analyses using the techniques covered so far in this unit. The only mandatory requirement is that MUST use principal component analysis (PCA). Can also use the other techniques covered in the unit such as cluster analysis and multidimensional scaling, but each of these is optional. Must summarise results in a report of no more than 1500 words. R code and any additional work not directly described in the report must be included in an Appendix (this will not count towards the word limit). The maximum page limit for Appendix is 10 pages.

## Data
The Gini index is a measure of income inequality. This assignment uses Gini index data on the set of 52states of the U.S. The data was sourced from U.S. State-Level Income Inequality Data - Mark W. Frank. For this assignment, I have been provided with the Gini index of the 52 U.S. states over a selection of years. The first block, available in Inequality_GD.csv, covers the period between 1929 and 1945. This period covers the Great Depression and World War II. The second block, available in Inequality_GR.csv, covers the period between 2007 and 2015, which corresponds to the Global Financial Crisis and the economic downturn that followed.

## Preliminary Analysis
- Check NAs
- Check outliers
- Repalce NA and outlier

## PCA
In this report, Principal Component Analysis (PCA) will be conducted on two data sets. PCA is a statistical method used to simplify and reduce the dimensionality of a data set while retaining as much essential information as possible. It achieves this by transforming the original variables into a new set of uncorrelated variables known as ‘principal components.’ These principal components are linear combinations of the original variables and are ordered so that the first component explains the most variance in the data, the second component explains the second most, and so on. The goal is to use as few principal components as possible to capture the majority of the variance. To determine the optimal number of principal components, we will employ methods such as the scree plot and Kaiser’s Rule.

## Conslusion
In conclusion, historical events such as the Great Depression, World War II, and the Global Financial Crisis have all had significant impacts on income inequality in the United States. The impacts of the Great Depression and World War II on income inequality appear different from the impact of the Global Financial Crisis. During the Great Depression and World War II, the majority of states in the United States experienced a reduction in income inequality, resulting in relatively lower levels of income inequality. Only a very few states exhibited high levels of income inequality at the end of this period. In contrast, the Global Financial Crisis also influenced the level of income inequality in the states. This historical event often mirrored states with low levels of income inequality, shifting them to high levels of income inequality, and vice versa. Consequently, some states with low levels of income inequality experienced an increase in income inequality, while some states with high levels of income inequality have a relatively lower level of income inequality following this historical event.
