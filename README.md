# magist


# Customer Review Analysis Project README

This project focuses on analyzing customer reviews and extracting insights from a database containing information about customer orders, review scores, and other related data. The main goal is to gain valuable insights into customer satisfaction and identify factors that may influence review scores in a Brazilian e-commerce context.

## Table of Contents
1. [Introduction](#introduction)
2. [Database Setup](#database-setup)
3. [Analysis Overview](#analysis-overview)
4. [SQL Queries and Stored Procedure](#sql-queries-and-stored-procedure)
5. [Further Analysis](#further-analysis)
6. [Results and Findings](#results-and-findings)
7. [How to Use](#how-to-use)
8. [Contributing](#contributing)
9. [License](#license)

## Introduction
Customer reviews play a crucial role in understanding customer satisfaction and product/service quality. In this project, we analyze customer reviews from a Brazilian e-commerce platform to identify patterns, trends, and factors that influence review scores. The project utilizes an SQL database that contains information about customer orders, review scores, and geographical data.

## Database Setup
To run this analysis, you need to import the provided dataset into your SQL database. The dataset includes tables for orders, customers, products, and order reviews. Additionally, you will need to create the `geo_brazilian_state_names` table to store information about Brazilian states and their abbreviations.

## Analysis Overview
The analysis covers several key areas, including:
1. Calculating the average review score by state to identify regional variations in customer satisfaction.
2. Investigating whether reviews containing positive words have higher average scores.
3. Finding the state with the highest review score for reviews containing positive words and having a minimum threshold of reviews.
4. Automating a KPI using a stored procedure to calculate the average review score for a given state, product category, and year.

## SQL Queries and Stored Procedure
The SQL queries provided in this project are used to extract relevant data from the database and perform the necessary calculations. The queries cover tasks such as calculating average review scores, filtering reviews based on positive keywords, and joining data from multiple tables.

The stored procedure `items_purchased` allows users to input a state name, product category (in English), and a year to obtain the average review score for orders meeting these criteria.

## Further Analysis
To enhance the analysis, several additional steps can be taken, including:
1. Time series analysis to identify trends in review scores over time.
2. Sentiment analysis on review comments to categorize reviews as positive, neutral, or negative.
3. Geospatial analysis to visualize review scores on a map of Brazil.
4. Review length analysis to explore whether review length affects review scores.
5. Customer segmentation based on review scores and other attributes.


## Results and Findings
The results of the analysis, along with key findings and insights, will be documented in a separate report or presentation. Visualizations, tables, and charts will be used to communicate the findings effectively.

## How to Use
To use this project, follow these steps:
1. Set up the database and import the provided dataset.
2. Execute the SQL queries and stored procedure to perform the analysis.
3. Explore the results and findings in the generated report or presentation.

## Contributing
Contributions to this project are welcome. If you find any issues or have ideas for improvement, please open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE.md). Feel free to use and modify the code for your purposes. Attribution is appreciated but not required.
