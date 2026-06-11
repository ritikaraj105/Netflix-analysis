# Netflix-analysis
Performed exploratory and business-oriented analysis on the Netflix Movies &amp; TV Shows dataset using SQL, extracting insights on content distribution, ratings, genres, countries, and release trends. Utilized advanced SQL techniques such as CTEs, window functions, string manipulation, and date operations to solve real-world analytical problems.
Netflix Movies & TV Shows Data Analysis using SQL
Project Overview

This project analyzes the Netflix Movies & TV Shows dataset using SQL to uncover content trends, audience ratings, genre distribution, country-wise content production, and release patterns. The analysis demonstrates practical SQL skills including data cleaning, aggregation, window functions, CTEs, string manipulation, and business-driven data exploration.

Objectives
Analyze the distribution of Movies and TV Shows.
Identify the most common content ratings.
Explore content trends across countries and release years.
Examine genre popularity and content duration.
Generate business insights using SQL queries.
Dataset
Source: Netflix Movies and TV Shows Dataset (Kaggle)
Records: 8,800+ Netflix titles
Attributes: Title, Type, Director, Cast, Country, Release Year, Rating, Duration, Genre, Description, etc.
Tools & Technologies
SQL (PostgreSQL)
PostgreSQL Functions
Window Functions
Common Table Expressions (CTEs)
Data Aggregation & Analysis
Key Business Questions Solved

✔ Count Movies vs TV Shows

✔ Find the most common ratings for each content type

✔ Identify top countries producing Netflix content

✔ Discover the longest movies

✔ Analyze content added in recent years

✔ Find content by specific directors

✔ Identify TV Shows with more than 5 seasons

✔ Analyze genre distribution

✔ Explore India's yearly content contribution

✔ Find documentary content

✔ Detect missing director information

✔ Analyze actor appearances and popularity

✔ Categorize content based on keywords such as Kill and Violence

 15 Business Problems & Solutions

1. Count the number of Movies vs TV Shows
2. Find the most common rating for movies and TV shows
3. List all movies released in a specific year (e.g., 2020)
4. Find the top 5 countries with the most content on Netflix
5. Identify the longest movie
6. Find content added in the last 5 years
7. Find all the movies/TV shows by director 'Rajiv Chilaka'!
8. List all TV shows with more than 5 seasons
9. Count the number of content items in each genre
10.Find each year and the average numbers of content release in India on netflix. 
return top 5 year with highest avg content release!
11. List all movies that are documentaries
12. Find all content without a director
13. Find how many movies actor 'Salman Khan' appeared in last 10 years!
14. Find the top 10 actors who have appeared in the highest number of movies produced in India.
15.Categorize the content based on the presence of the keywords 'kill' and 'violence' in 
the description field. Label content containing these keywords as 'Bad' and all other 
content as 'Good'. Count how many items fall into each category.

SQL Concepts Demonstrated
SELECT Statements
GROUP BY & Aggregations
CASE Statements
String Functions
Date Functions
CTEs
Window Functions (RANK)
Subqueries
Data Transformation
Filtering & Sorting
Sample Insights
Movies constitute the majority of Netflix content.
TV-MA is among the most common ratings on Netflix.
The United States and India contribute significantly to Netflix's content library.
Drama and International Movies are among the most popular genres.
Netflix content additions increased significantly during recent years.
Project Structure
Netflix-SQL-Analysis/
│
├── netflix_dataset.csv
├── netflix_analysis.sql
├── README.md
└── screenshots/
Learning Outcomes

Through this project, I strengthened my ability to:

Write complex SQL queries for real-world business scenarios.
Perform exploratory data analysis using SQL.
Extract actionable insights from large datasets.
Apply advanced SQL concepts frequently used in Data Analyst roles.
