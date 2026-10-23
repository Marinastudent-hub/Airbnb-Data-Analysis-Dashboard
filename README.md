# Airbnb Data Analysis Dashboard

My first Power BI dashboard, analyzing 500 Airbnb listings across 10 European cities using web scraping, SQL Server, and Power BI.

## Project Overview
This project explores Airbnb listing data across 10 European cities to identify patterns in recorded prices, ratings, Superhost status, and Guest Favorites. The goal is to transform raw scraped data into meaningful insights through data cleaning, SQL-based data processing, and interactive visualization.

## Tools & Technologies
- **Python & Selenium:** Web scraping and data collection
- **SQL Server:** Data cleaning, transformation, and data warehouse management
- **Power BI:** Interactive dashboard and data visualization
- **CSV:** Storage of scraped listing data

## Data Pipeline
The project follows a layered data warehouse approach:

- **Bronze:** Raw data ingestion
- **Silver:** Data cleaning and preparation
- **Gold:** Final tables prepared for analysis and reporting

## Dataset
- **500 Airbnb listings**
- **10 European cities:** Amsterdam, Athens, Barcelona, Berlin, Budapest, Lisbon, London, Paris, Rome, and Vienna
- Listing attributes include recorded price, rating, reviews, Superhost status, Guest Favorite status, and listing URL.

## Key Performance Indicators (KPIs)
- Total Listings
- Average Recorded Price
- Average Rating
- Total Superhosts
- Total Guest Favorites

## Dashboard Features
- Interactive city filter
- Comparison of recorded prices across cities
- Recorded price analysis by Superhost and Guest Favorite status
- Exploration of the relationship between recorded prices and ratings

## Project Files
- `Airbnb.pbix` — Power BI dashboard
- `Airbnb_Scraped_Data.csv` — Scraped dataset
- `SQL.zip` — SQL scripts for data processing and analysis
- `Screenshot 2026-10-23 222439.png` — Dashboard screenshot

## Notes
Recorded prices are analyzed as provided in the collected dataset; they have not been confirmed to represent nightly prices.

## Author
[Marina Essam](https://github.com/Marinastudent-hub)

---

## Dashboard Preview

![Airbnb Power BI Dashboard](Screenshot%202026-10-23%20222439.png)
*This project was completed as a learning project and represents my first Power BI dashboard.*
