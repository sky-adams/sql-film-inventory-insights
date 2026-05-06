# Advanced SQL Analytics: Film Inventory & Customer Insights

## Description
I did this project as part of Udacity's Programming for Data Science with Python nanodegree. Despite the name, much of the nanodegree was focused on SQL. 

This project demonstrates my ability to write complex SQL queries using joins, common table expressions (CTEs), window functions, and aggregation to explore a relational database and uncover insights.

The dataset used was a fictional movie rental database provided by Udacity. Although the data is synthetic, it’s modeled after a real-world rental system and includes tables for films, inventory, rentals, stores, actors, and customers.

## Files
queries.txt: Contains the queries I wrote for the project. I wrote the queries to answer the questions I wrote in the slides.

SQL_Project_Slides.pdf: Contains the slides I created for the project. These slides include visualizations created using the query results and summarize key findings and conclusions.

## Insights
The analysis addressed several questions about movie availability, customer demographics, and rental trends:

### Query 1 – Film Availability Over Time
Calculated the number of days each film was completely unavailable (all copies rented out). The results identified the ten films that are most frequently unavailable, highlighting which films it may be best to buy more copies of in order to maximize profits.

### Query 2 – Most-Rented Actors
Counted total rentals per actor, providing insight into which actors may be the most popular, which can guide decisions about what new films to purchase to maximize profits.

### Query 3 – Customer Distribution by Country
Determined the percentage of customers from each country and grouped minor contributors under “Other.” This helped visualize geographic representation and identify key customer bases.

### Query 4 – Top Percentile Films by Rentals
Assigned each film a percentile rank based on its rental frequency using a window function. The query isolated films in the top percentile, revealing the most popular films.
