# Netflix SQL Data Analysis

![Netflix](logo.png)

This project is a SQL-based analysis of the Netflix Movies and TV Shows dataset using PostgreSQL.

The objective is to analyze the content available on Netflix and answer different questions using SQL. The main focus is on working with a real-world dataset and using SQL to find useful information from it.

## About the Project

The dataset contains information about Netflix movies and TV shows, including:

- Title
- Type
- Director
- Cast
- Country
- Date added
- Release year
- Rating
- Duration
- Genre
- Description

I used PostgreSQL and pgAdmin to create the table, load the dataset, and run the analysis queries.

## Questions I Worked On

1. How many Movies and TV Shows are available?
2. What is the most common rating for Movies and TV Shows?
3. Which movies were released in a particular year?
4. Which countries have the most content on Netflix?
5. What is the longest movie?
6. What content was added in the last five years?
7. What content was directed by a particular director?
8. Which TV Shows have more than five seasons?
9. How many titles are available in each genre?
10. How has Indian content been added over the years?
11. Which movies are documentaries?
12. Which titles don't have director information?
13. How many recent movies feature Salman Khan?
14. Which actors appear most frequently in Indian content?
15. How can content be classified based on keywords in its description?

## SQL Concepts Used

- SELECT and WHERE
- GROUP BY and ORDER BY
- COUNT and aggregate functions
- DISTINCT
- Subqueries
- Window functions
- RANK()
- CTEs
- CASE statements
- String functions
- STRING_TO_ARRAY()
- UNNEST()
- SPLIT_PART()
- Date functions
- Type casting
- ILIKE

## Project Structure

```text
Netflix-SQL-Data-Analysis/
├── data/
│   └── netflix_titles.csv
├── screenshots/
│   ├── 01_schema.png
│   ├── 02_content_type.png
│   ├── 03_common_rating.png
│   ├── 04_top_countries.png
│   ├── 05_genre_analysis.png
│   ├── 06_indian_actors.png
│   └── 07_content_classification.png
├── sql/
│   ├── schema.sql
│   ├── business_problems.sql
│   └── solutions.sql
├── logo.png
└── README.md