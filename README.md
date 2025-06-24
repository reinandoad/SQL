# World Database SQL Project

This project demonstrates my SQL querying skills using the **World Database**, a classic dataset containing structured information about countries, cities, and languages. The project focuses on answering a range of analytical and real-world questions using SQL.

## Project Objectives

- Practice advanced SQL queries across multiple tables
- Extract meaningful insights from global demographic, economic, and linguistic data
- Showcase proficiency in SQL for portfolio and job applications

## Dataset Overview

The **World Database** includes three main tables:

- `country`: Contains country-level information such as name, continent, region, population, GNP, government form, etc.
- `city`: Contains details about major cities, including population and country code
- `countrylanguage`: Lists languages spoken in each country, their status (official or not), and usage percentage

## Key Features

### 1. Data Exploration & Aggregation
- Counted total countries and unique languages
- Calculated average life expectancy and GNP by region or continent
- Total population for Southeast Asia and other groupings

### 2. Filtering & Conditional Queries
- Filtered countries by area, population, government form, and independence year
- Found country names using string patterns (e.g., starting with `I`, ending in `o`)

### 3. Grouping & Sorting
- Grouped countries by continent and region
- Sorted countries and cities by population, GNP, and life expectancy
- Identified regions with increasing GNP over time

### 4. Relational Joins
- Joined `country`, `city`, and `countrylanguage` to enrich the data
- Showed capital cities and populations for ASEAN and G-20 countries
- Identified countries with the highest official use of English

### 5. Subqueries & Advanced Analysis
- Compared countries’ life expectancy to the global average
- Analyzed language usage by percentage in specific countries like Indonesia

## Tools and Techniques

- **SQL**: MySQL syntax
- **Joins**: INNER JOIN for relational analysis
- **Aggregations**: `SUM`, `AVG`, `COUNT`, `ROUND`
- **Filtering**: `WHERE`, `LIKE`, `IN`, `HAVING`
- **Grouping**: `GROUP BY` with `ORDER BY` for analysis
- **Subqueries** for comparative analysis

Purpose
This project was developed to sharpen my SQL skills through hands-on problem-solving. It demonstrates my ability to query structured databases, work with relational joins, and uncover insights from real-world data.

File
World_SQL.sql: All SQL queries used in this project

License
This project is for educational and portfolio purposes.
