# 🎵 Music Store Sales Analysis using SQL

## Project Overview

This project demonstrates practical SQL skills by analyzing a digital music store's data to derive actionable business insights. Using real-world relational data, I performed in-depth analysis on customer behavior, sales trends, and artist performance to support data-driven decision-making for marketing and operations.

>  **Focus**: Revenue analysis, genre preferences, customer segmentation, and top-performing artists.

---

## Tools & Technologies

- **SQL** – Data querying and transformation
- **DBMS** – SQLite (CSV-based relational structure)
- **Environment** – DB Browser for SQLite / MySQL Workbench / DBeaver
- **Data Source** – Raw `.csv` files imported into a SQL-compatible engine

---

## Key Objectives

- Identify high-value customers and top revenue-generating countries and cities
- Explore music genre popularity across different countries
- Determine which artists and tracks drive the most sales
- Segment customers based on their music preferences and spending patterns
- Practice using SQL joins, subqueries, window functions, and CTEs

---

## Dataset Description

The dataset simulates a digital music platform and consists of the following CSV-based tables:

| Table Name         | Description                                               |
|--------------------|-----------------------------------------------------------|
| `customer.csv`     | Customer details (ID, name, country)                      |
| `employee.csv`     | Employee hierarchy and job titles                         |
| `artist.csv`       | Artist metadata                                           |
| `album2.csv`       | Album details (linked to artists)                         |
| `genre.csv`        | Music genres                                              |
| `media_type.csv`   | Audio file format types                                   |
| `playlist.csv`     | Playlist metadata                                         |
| `playlist_track.csv` | Track-to-playlist mapping (many-to-many)                |
| `invoice_line.csv` | Individual purchase items with pricing and track info     |
| `invoice.csv`      | 	Stores purchase transactions made by customers           |
| `track.csv`        | Contains metadata for individual music tracks             |


## 📊 Key Analytical Queries

### 🧑‍💼 Business Operations
- Who is the **senior-most employee** based on job title?
- What are the **top 3 invoice totals** across the store?
- Which **cities** and **countries** generated the most revenue?

### 🎧 Customer & Music Preferences
- Who are the **best customers** by spending?
- Which **customers listen to Rock music** most?
- What are the **longest tracks** (above average song duration)?
- Which **artists wrote the most Rock tracks**?

### 📈 Advanced Insights using CTEs & Window Functions
- How much has each customer spent on the **top-selling artist**?
- What is the **most popular genre per country**?
- Who is the **top customer in each country**?


➡️ [See Summary & Business Insights](./Insights.md)
📊 [See SQL Queries and Outputs](./Query_Results.md)

