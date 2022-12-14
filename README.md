# Exploratory Data Analysis(EDA) on Residential Properties

Data science project to determine the market value of real estate objects and typical parameters of apartments for sale in St. Petersburg and other cities in the Leningrad Region.

## 1.0 Business Problem

The **(*NDA*)** platform is planning to create an automated system for tracking anomalies and fraudulent activities. 

## 2.0 Business Assumptions
The strategy to use EDA to define the typical parameters for real estate properties may improve the detection of anomalies and fraudulent activities.

## 3.0 Solution Strategy

My solution to solve this problem will be the development of a data science project. This project will provide typical parameters which can later be embedded into an automated system.

Step 01. Data Description: In this first section the data will be collected and studied. The missing values will be treated or removed. Finally, an initial data description will be carried out to know the data. Therefore some calculations of descriptive statistics will be made, such as the mean, std, and IQR values.

Step 02. Data Categories and Metrics: In this section, new metrics and categories will be created to assist the EDA, such as the price per square meter, date categories (weekday, month, and year), square meters ratios (Living / Total Area, and Kitchen / Total Area), floor categories, sale categories (avg. time for sell, fast sale, slow sale). These metrics and categories will help in exploratory data analysis and may improve the detection of typical parameters and outliers.

Step 03. Exploratory Data Analysis: The exploratory data analysis section consists of univariate analysis, bivariate analysis, and multivariate analysis to assist in the understanding of the database. Factors affecting the price will be studied: square meters, the number of rooms, floor category, distance to the city center, and ad publishing date (weekday, month, year). The city center location in St.Petersburg will be determined based on the price per square meter.

Step 04. Correlation and Factor Analysis: In this section, factors that affect apartment prices will be analyzed. Correlation analysis will be performed in two apartment groups: City Centre & Entire St.Petersburg. Typical parameters for city center apartments will be discovered and compared between the groups.

Step 05. Conclusions: This is a conclusion stage that provides typical parameters and other insights needed for the creation of an automated system for anomalies and fraudulent activity tracking. In addition, some business questions are answered to show the applicability of the EDA's results in the business context.

**Insights**:

|              | **City Center** | **Entire City** |
|--------------------|-----------------|-----------------|
| **Total Area**     | 85 sqm          | 60 sqm          |
| **Last Price**     | 12.2 million    | 6.9 million     |
| **Rooms**          | 3               | 2               |
| **Ceiling Height** | 281 cm          | 269 cm          |
| **Days for Sale (mean)**  | 216 days             | 164 days             |
| **Days for Sale (median)**  | 92 days             | 91 days             |

* **Most common total area** of the apartments for sale in St.Petersburg: between 30 and 45 sqm (1-rooms & 2-rooms apartments).

* **Most common prices** of the apartments: from 1.8 million to 7 million. **The peak of sales** is in the price range from 3 to 5 million.

* **Most popular apartments** have 1-room (average price: 8??), followed by 2-room apartments (average price: 7.5??)

* **Most common ceiling heights**: 250cm (over 5500 apartments); 265cm (around 5000),300cm (around 4000 apartments).

* The **average time to sell** is 165 days and the median is 91 days.

* **Fast sale**: up to 45 days. **Long sale**: over 6 months.

* **Factors that affect Pricing** (city center): The total area affects the price most. The number of rooms affects the price as well. Ceiling height and floor have a similar moderate effect.

* **Factors that affect Pricing** (entire St.Petersburg): The total area affects the price most, the second factor affecting the price is the number of rooms. The third factor is the height of the ceilings.

* **City Centre** of St. Petersburg ranges from 0 to 7 km.

* **Highest average price by Date of the Week**: highest on Thursdays (5.88 million), followed by Saturday (5.80 million) and Sunday (5.76 million). The average price on Monday, Tuesday, Wednesday and Friday are approximately 5.7 million.

* **Highest average price per Month**: highest in December (6.0 million), second highest is in September (5.8 million). The lowest average price is in October (5.6 million).

* **Highest Price per Square Meter** in the region: city of St.Petersburg, 111215 Roubles per Square Meter.
* **Lowest Price per Square Meter** in the region: city of Vyborg, 57703 Roubles per Square Meter.
