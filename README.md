# Zomato-Data-Analysis

Zomato Data Analysis
Project Overview
This project is a comprehensive analysis of Zomato's dataset to uncover insights about customer preferences, restaurant ratings, and spending patterns. Using Python's data analysis libraries, we performed data cleaning, transformation, and exploratory data analysis (EDA) to answer specific business questions related to restaurant types, ratings, and order modes.

Prerequisites
To run this project, ensure you have the following Python libraries installed:

1. Pandas
2. Numpy
3. Matplotlib
4. Seaborn
Install the libraries using pip if you haven't already.

Dataset
The dataset used for this analysis is named Zomato data.csv. Ensure the file is in the same directory as your script or provide the correct path.

Project Steps
1. Load and Inspect the Data
We start by loading the dataset and inspecting the first few rows to understand its structure and content.

2. Data Cleaning: Handling the "Rate" Column
The "rate" column contains ratings in a string format (e.g., 4.5/5). We need to convert this into a float for analysis.

3. Data Summary
We inspect the summary of the dataframe to check for any null values and understand the data types.

Conclusion: There are no null values in the dataframe, so no further data cleaning is necessary.

Exploratory Data Analysis (EDA)
Query 1: Type of Restaurant Majority of Customers Order From
Conclusion: Most orders are from the Dining category.

Query 2: Votes for Each Type of Restaurant
Conclusion: Dining category restaurants receive the highest votes.

Query 3: Rating Distribution Among Restaurants
Conclusion: The majority of restaurants received ratings in the range of 4 to 4.25.

Query 4: Average Spending of Couples on Online Orders
Conclusion: Couples spend between 500 to 600 rupees on their partner through online food orders.

Query 5: Rating Comparison Between Online and Offline Orders
Conclusion: Online food orders generally receive higher ratings compared to offline orders.

Query 6: Type of Restaurant Receiving Most Offline Orders
Conclusion: Dining restaurants primarily accept offline orders, while cafes receive more online orders.

Conclusion
This analysis provides insights into customer behavior and preferences on Zomato. Key findings include the dominance of Dining category orders, higher ratings for online orders, and spending patterns of couples. These insights can be used by restaurants and Zomato to improve their services and tailor their offerings to customer needs.

Next Steps
Further Analysis: Extend the analysis to include other factors such as location-based preferences or time-based order patterns.
Modeling: Develop predictive models to forecast restaurant ratings or customer spending.
