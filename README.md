# Have Canadian Earnings Kept Pace with the Cost of Living?

## Overview
This project investigates whether Canadian earnings have kept pace with the cost of living. By analyzing the relationship between the Consumer Price Index (CPI) and individual incomes over the last four decades (1981-2021), we aim to understand the impact of inflation on the average Canadian's earnings and highlight which categories of the CPI data have had the largest effect on price increases.

## Table of Contents
- [Overview](#overview)
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Datasets](#datasets)
- [Data Cleaning](#data-cleaning)
- [Guiding Questions and Visualizations](#guiding-questions-and-visualizations)
- [Contributing](#contributing)
- [Contact](#contact)
- [Acknowledgments](#acknowledgments)

## Introduction
An article posted on January 6, 2023, by Global News highlights how difficult it has been for Canadians to keep up with the price of goods, emphasizing how the affordability of goods has become one of the biggest sources of stress among Canadians. The average Canadian is also struggling to earn a living wage, making it more difficult to decide whether to focus on feeding their children a healthier diet or cut necessary expenses to make their monthly rent. Across Canada, we see inflation rise alongside wages, but wages seem not to be keeping up at the same pace.

Our objective is to compare the difference in CPI and average incomes across provinces to see how the average Canadian has been doing. The Consumer Price Index (CPI) represents changes in prices as experienced by Canadian consumers. It measures price changes by comparing, through time, the cost of a fixed basket of goods and services. These baskets of goods are composed of eight major categories:

1. Food
2. Shelter
3. Household operations, furnishings, and equipment
4. Clothing and footwear
5. Transportation
6. Health and personal care
7. Recreation, education, and reading
8. Alcoholic beverages, tobacco products, and recreational cannabis

We aim to analyze the relationship between CPI and individual incomes to understand whether people's earnings have kept up with rising prices and to highlight which categories of the CPI data have had the largest effect on price increases.

## Features
- Analysis of CPI categories contributing to the highest increase in prices
- Comparison of CPI and average incomes across Canadian provinces
- Data cleaning and preprocessing
- Data visualization using Matplotlib, Seaborn, and Plotly
- Interactive visualizations for better data interpretation

## Datasets
### Income of Individuals by Age Group, Sex, and Income
This dataset includes columns with values for years ranging from 1976 to 2021. For this project, we focus on years from 1981 to 2021. The rows provide details such as:

- Geography
- Age Group
- Sex
- Income Source
- Various statistics including:
  - Total population of people aged 16 or older
  - Total population of people aged 16 or older with income
  - Aggregate Income
  - Average Income
  - Median Income
### Consumer Price Index (CPI)
The CPI dataset includes columns with values for years ranging from 1914 to 2022. For this project, we focus on years from 1981 to 2021.

## Data Cleaning
The data cleaning process involved merging the CPI and Income datasets by Geography and Year. We downloaded and merged 22 datasets for both CPI and income using the main Geography row and Year columns from every dataset. Provinces with small populations, such as Yukon, the Northwest Territories, and Nunavut, were excluded. The merged dataset was then cleaned by:

- Removing unnecessary columns
- Renaming columns for clarity
## Guiding Questions and Visualizations
### Guiding Question 1
#### What CPI categories have contributed to the highest increase in prices over the past 40 years?

This question aims to identify which categories within the Consumer Price Index (CPI) have seen the most significant price increases over the past four decades. Understanding these categories can help us pinpoint the primary drivers of inflation in Canada.

- Visualization 1: Multiple subplots representing the change in CPI categories over 40 years for Canada on average.
- Visualization 2: A single line graph comparing the CPI growth for each category in Canada.
- Visualization 3: A line chart comparing the CPI Index average for each province, showing consistent increases in the price of goods.
### Guiding Question 2
#### Have Canadian earnings kept up with the rise in CPI?

This question explores whether the growth in Canadian earnings has kept pace with the rise in the cost of living as measured by the CPI. It helps us understand if wage growth has been sufficient to maintain the purchasing power of Canadians in the face of inflation.

- Visualizations: This section includes visualizations comparing the average and median incomes with the CPI index for various provinces and for Canada as a whole.
### Guiding Question 3
#### How do the changes in CPI and income vary across different provinces in Canada?

This question investigates the regional variations in CPI and income changes across different provinces. It highlights how inflation and income growth differ from one province to another, providing insights into regional economic disparities.

- Visualizations: Visualizations and analysis comparing the variations in CPI and income changes across different provinces, highlighting regional differences and trends.
### Guiding Question 4
#### Which provinces have had the most significant disparity between income growth and CPI increase?

This question identifies the provinces with the largest gaps between income growth and CPI increase. It helps to pinpoint where the economic challenges are most severe, indicating regions where the cost of living has outpaced earnings the most.

- Visualizations: A detailed analysis and visualizations identifying the provinces with the most significant disparity between income growth and CPI increase, providing insights into the economic challenges faced by different regions.
