# Analyzing_WDI
This project aims at analysing World Development Indicators- a compilation of various metrics provided by The World Bank. The project is split into two sections. The first section involves cleaning and transforming data according to the requirements, applying text mining techniques to prepare data, executing k-means clustering to cluster indicators and  word2vec has been used to calculate similarity between statements. The second section of the project focuses upon using Tableau as a tool to develop visualisations to study patterns in the data over time. 
Data can be found at: https://datacatalog.worldbank.org/dataset/world-development-indicators

## About the dataset: size and cleaning the data
1. The dataset is huge with 132948 rows and 65 columns after removing missing values. 
2. The missing values cannot be substituted with mean/mode or any other specific value and it can't be removed as well. Therefore to clean the data, the rows which contain the maximum null values are removed. Also, the columns which had no values at all, such as the initial years (1960-1980), were removed too.
3. The data contains 1440 unique indicators that concern education, poverty etc. 
4. 
