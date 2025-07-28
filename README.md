# 🎵 Music Store Sales Analysis using SQL

## Project Overview

This project demonstrates practical SQL skills by analyzing a digital music store's data to derive actionable business insights. Using real-world relational data, I performed in-depth analysis on customer behavior, sales trends, and artist performance to support data-driven decision-making for marketing and operations.

>  **Focus**: Revenue analysis, genre preferences, customer segmentation, and top-performing artists.

---

## Techniques and SQL Concepts

This project showcases the use of diverse SQL techniques and concepts, including:

- **Basic Queries**: Data extraction, filtering, and sorting.
- **Aggregations**: `SUM`, `COUNT`, `AVG`, and `GROUP BY` to summarize data.
- **Window Functions**: `RANK`, `ROW_NUMBER`, and `CUME_DIST` for advanced analytical insights.
- **Joins**: Combining data across multiple tables for comprehensive analysis.
- **Subqueries and CTEs**: Structuring complex queries for better readability and efficiency.
- **Date and Time Functions**: Analyzing trends and patterns based on timestamped data.
- **Dynamic Calculations**: Deriving metrics such as percentage contributions, growth rates, and cumulative totals.


---

## Analytical Goals

- Identify high-value customers and top revenue-generating countries and cities.
- Explore music genre popularity across different countries.
- Determine which artists and tracks drive the most sales.
- Segment customers based on their music preferences and spending patterns.
- Practice using SQL joins, subqueries, window functions, and CTEs.
- Analyze invoice and sales data to identify top revenue-generating locations.
- Rank employees and customers based on their roles and total spending.
- Extract long-duration tracks by comparing to average track lengths.
- Determine top artists by genre-specific track contributions (e.g., Rock).
- Find most popular genres and top spenders per country using advanced ranking techniques.
- Clean and structure raw `.csv` data into relational formats for querying and analysis.

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



➡️ [See Summary & Business Insights](./Insights.md)
📊 [See SQL Queries and Outputs](./Query_Results.md)

