# Car Sales Data Analysis

This project is a data analysis of car sales data from a dealership. The dataset contains information such as car prices, mileage, year, fuel type, transmission, body type, color, doors, engine size, CO2 emissions, number of reviews, rating value, distance, and make.

## Getting Started

To get started with this project, you will need to clone this repository to your local machine and install the required libraries.

## Prerequisites
You will need to have Python 3 installed on your machine, as well as the following libraries:

* Pandas
* Matplotlib
* Seaborn
* requests
* time
* BeautifulSoup

# Data Cleaning
We started by checking for missing values and found that the dataset had missing values in several columns. We handled these missing values by filling them in with appropriate values. For example, for numerical columns like mileage and no_of_reviews, we filled in the missing values with the median value of the respective column. For categorical columns like fuel_type, we filled in the missing values with the mode value of the respective column.

We also converted the data types of some columns to their appropriate types. For example, we converted the mileage column, which had commas in the numbers, to an integer type after removing the commas. We also renamed the semiauto category in the transmission column to semi auto.

Overall, the cleaning and processing of the dataset was a crucial step in the analysis process, as it allowed us to work with a clean and structured dataset and draw meaningful insights from it.

## Exploratory Data Analysis
The dataset was explored using various visualizations such as histograms, scatterplots, and bar plots. The following insights were obtained from the analysis:

* The most popular car body type in the dataset is the Hatchback with 501 cars having this body type. Secondly, the SUV has 219 cars, and Estate comes in third with 45.
* A majority of the cars in the dataset have a manual transmission, followed by automatic cars and then semi-automatics.

* A majority of total sales were listed in 2020, followed by 2021 and 2019.

* The oldest car in the dataset is a Renault Megane 1.6 16v Monaco 2dr, year 2000, price 2490, mileage 88000, transmission automatic

* The newest car in the dataset is the Toyota Yaris Cross 1.5 Hybrid Icon 5dr CVT with a price of 27290, mileage of 998 and a year of 2023.

* And many more you should look at :)

## Conclusion 
For this project, I learned a lot about data analysis, cleaning, and visualization. It was an amazing experience to work with real-world data and see how it can be manipulated and transformed to gain insights.

One of the key takeaways for me was the importance of cleaning and preprocessing data before analysis. The dataset we worked with had missing values, inconsistent formatting, and outliers that could have skewed our results if not handled appropriately. By using techniques like filling missing values with median/mode values and converting data types to appropriate formats, we were able to make the data more suitable for analysis.

Another important aspect was the visualization of data. With the help of various visualization tools like Seaborn and Matplotlib, we were able to gain insights into the data by creating different plots, histograms, and heatmaps. These visualizations made it easier to understand the trends and patterns in the data.

Overall, this project has taught me valuable skills that I can use in future data analysis projects. I have learned how to collect data, clean it, analyze it, and visualize it, and I'm excited to apply these skills to new and interesting datasets in the future.

## Acknowledgments 

This project was completed as part of an Applied data science course at The University of Buckingham.

** URL 🔗 **
https://www.theaa.com/used-cars/displaycars?fullpostcode=MK181SF&travel=2000&page=

