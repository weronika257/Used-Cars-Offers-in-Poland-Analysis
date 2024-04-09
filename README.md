# Used Cars Offers in Poland Analysis

### Tableau Dashboard

![alt text](<Tableau Dashboard.png>)

### Excel Dashboard

![alt text](<Excel Dashboard.png>)

## Table of Contents

- [Project Overview](#project-overview)
- [Data Source and Files](#data-source-and-files)
- [Tools](#tools)
- [Questions](#questions)
- [Key Findings](#key-findings)
- [Limitations](#limitations)

## Project Overview

This project dives deep into analyzing the Polish used car market in July 2023 using data from a popular online platform for car sales. Through this analysis, we uncover key insights about which car brands are most common, the specific models people are buying, and whether they prefer older or newer cars. We also look into whether people prefer manual or automatic transmissions, which fuel types are most popular, and how mileage affects the price of a car. Additionally, we explore how car availability varies across different parts of Poland. Lastly, we examine how the year a car was made influences its price.

Created dashboards allow for data filtering by selecting the car brand, manufacture year, fuel type and gearbox type.

## Data Source and Files

The source data is contained in the 'data.csv' file that comes from [Kaggle](https://www.kaggle.com/datasets/wspirat/poland-used-cars-offers). The analysis in Excel was performed in the file 'Poland_Used_Cars_Offers.xlsx'. Tableau dashboard is available. The dashboard created in Tableau is available on [Tableau Public](https://public.tableau.com/app/profile/weronika.studzi.ska/viz/PolishUsedCarMarketInsights-June2023/Dashboard1).

## Tools

- Microsoft Excel - Data Cleaning, Pivot Tables, Charts, Dashboard
- Tableau - Dashboard

## Questions

1. How many cars are on sale?
2. What is the average price of a car?
3. What is the ratio between the average price of a car and the year it was manufactured?
4. What is the lowest price of a car?
5. What is the highest price of a car?
6. Which car brand has the most cars on sale?
7. How are cars powered?
8. What is the most popular car model?
9. From which manufacture year are the most and least number of cars available?
10. How does car sales vary by voivodeships? Where are the most cars sold, where the fewest? In which voivodeship is the average car price the highest, and in which the lowest?
11. Which cities have the highest number of offers?
12. What is the distribution of gearbox types among the cars?
13. What is the distribution of average prices based on mileage?
14. Which car brand has the highest average price?

## Key Findings

- 85,632 cars were put up for sale.
- The average price of a car is 75,917 zł.
- In most cases, the later the year of production of a car, the more expensive it is. A significant increase in the average price is noticeable in particular for cars produced since 2015.
- The lowest price is 1,111 zł.
- The highest price is 2,599,000 zł.
- Volkswagen (10,413), Opel (9,803) and BMW (6,598) have the highest number of cars on sale.
- Most cars are powered by petrol - 43,049 out of 85,632 which is about 50%.
- The most popular car model is the Opel Astra.
- Most cars were produced in 2018 (6,169), 2017 (5,882) and 2019 (5,797). The smallest number of cars dates back to 1995, with 477 cars. Based on the values for all years analysed, it can be seen that newer cars dominate sales.
- The most cars are sold in the Masovian Voivodeship (16,863), Greater Poland Voivodeship (11,660), and Silesian Voivodeship (10,547). In the remaining voivodeships, these values are significantly lower. The fewest cars are sold in the Opole Voivodeship (1,400), Podlaskie Voivodeship (1,646), and Warmian-Masurian Voivodeship (1,867).
- Most offers come from Warsaw (6,376 offers). Kraków is second in the ranking with 2,262 offers and Wrocław is third with 2,037.
- Approximately 60% of the cars have manual transmission, while 40% have automatic transmission.
- Based on the data analysed, we can conclude that, in general, as mileage increases, the average price of cars tends to decrease. However, an increase in the average price of cars with mileage between 600,000 and 700,000 km and above 700,000 km is noticeable, which may indicate a different market segment or specific factors affecting prices in this range.
- The cars with the highest average price belong to the Lamborghini brand (average price of 1,271,214 zł) and Ferrari (1,024,220 zł). The cheapest cars are from the Daewoo brand with an average price of 4,545 zł.

## Limitations

Due to data mismatches in some columns in different rows, it was necessary to exclude them from the analysed dataset. The original dataset contained 91,523 records, of which 85,632 were kept for analysis, resulting in the removal of 5,891 records.
