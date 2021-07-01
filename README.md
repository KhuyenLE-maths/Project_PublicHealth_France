# Project: Exploratory data analysis with PublicHealth-France dataset

## Context
- We have a large databaset which presents the information of 320 772 different food products. These informations can be separated into four sections:
   + General information containing name, modification date,
   + A set of tags as product category, location, original country, brand,
   + The ingredients of the products and their possible additives,
   + Nutritional information: amount in grams of a nutrient per 100 grams of the product, etc

- In this project, we have discovered a completed procedure of the data analysis, from the basic steps as data importing and cleaning to dimensional reduction as well as data testing.
- Through this project, we can see the importance of the variance-covariance matrix in data analysis. It is not only used for presenting the relationships between variables, it is also a premise for both PCA and ANOVA methods.
- The objective of PCA is finding the components at which the projection of data are most discriminated. This method is really helpful for dimensional reduction, by keeping only the most important features. This make a lot of sense in data data analysis, especially in high dimensional case, as:
  + Simplifying the data visualization,
  + Saving stockage, computational time,
  + Improving the performance of Machine learning methods, etc
- Through analyzing the variances between groups, the ANOVA test import also the information of means between these groups. There are many Python packages which support for this test, for example pingouin, statsmodels, pandas, scipy.

    <img width="721" alt="food_image" src="https://user-images.githubusercontent.com/69978820/124141810-ffaf8600-da89-11eb-8360-0b1cca37cf31.png">

