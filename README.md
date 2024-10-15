# Airbnb-Dataset-Visualization
This project focuses on exploratory data analysis (EDA) of an Airbnb dataset of New York.
Overview

This project focuses on exploratory data analysis (EDA) of an Airbnb dataset to derive insights and visual representations of the data. The dataset contains various attributes of listings, including price, location, availability, and host details. The goal is to clean the dataset by removing outliers, checking for duplicates, handling null values, and then performing visualizations using bar plots, pie charts, count plots, and histograms.

Dataset Description

The Airbnb dataset consists of various features such as:

id: Unique identifier for each listing
name: Name of the listing
host_id: Unique identifier for the host
neighbourhood: Neighborhood of the listing
price: Price per night
availability: Number of available nights

Additional features related to the listing and host
Data Cleaning

Removing Outliers:
Outliers can skew our analysis. In this project, we identified outliers in the price and availability columns using the IQR method. These outliers were removed to ensure a more accurate analysis.

Checking for Duplicates:
We checked for duplicate listings using the id column. Any duplicates found were removed to maintain data integrity.

Handling Null Values:
Null values were identified and addressed as follows:

For categorical variables, we filled null values with the mode.
For numerical variables, we filled null values with the median.
Exploratory Data Analysis (EDA)



Visualizations

Bar Plot:
Used to show the distribution of listings by neighborhood.
Pie Chart:
Illustrated the proportion of listings by room type (Entire home, Private room, etc.).
Count Plot:
Displayed the count of listings by price ranges.
Histogram:
Provided insights into the distribution of prices.
Heatmap:
Provided insights of correlation between the features of the dataset.
lineplot:
We use line plot to compare the average prices of propertie preset at different locations.



Technologies Used

Python
Pandas
NumPy
Matplotlib
Seaborn
Conclusion

This project successfully cleaned the Airbnb dataset and conducted a thorough exploratory data analysis. The visualizations provided valuable insights into the distribution and characteristics of the listings. Future work may involve further predictive modeling or machine learning applications.
