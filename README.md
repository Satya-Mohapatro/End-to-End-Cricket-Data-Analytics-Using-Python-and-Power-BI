# 🏏 Cricket Data Analytics: T20 World Cup Insights using Python & Power BI

This project demonstrates an end-to-end sports data analytics pipeline using **Python, Pandas, Web Scraping**, and **Power BI**. We extract real-time cricket data from **ESPN Cricinfo**, transform it using **Pandas**, and create interactive dashboards in **Power BI** to uncover insights from the **T20 World Cup**.

---

## 📌 Table of Contents
- [Project Overview](#project-overview)
- [Tech Stack](#tech-stack)
- [Data Source](#data-source)
- [Project Workflow](#project-workflow)
- [Power BI Dashboard](#power-bi-dashboard)
- [Key Insights](#key-insights)
---

## 📊 Project Overview

The goal of this project is to analyze the performance of players and teams in the T20 World Cup using a real dataset. This includes:

- Scraping cricket match and player data from [ESPN Cricinfo](https://www.espncricinfo.com)
- Cleaning and structuring the data using Python and Pandas
- Creating an interactive Power BI dashboard to visualize trends and insights
- Identifying top batsmen, bowlers, and the best playing XI

---

## 🛠️ Tech Stack

- **Python** – for web scraping and data processing
- **Pandas** – for data manipulation and transformation
- **Power BI** – for data modeling and dashboard creation
- **Jupyter Notebook / VSCode** – for development and testing

---

## 🌐 Data Source

- Match data was scraped from [ESPN Cricinfo T20 World Cup section](https://www.espncricinfo.com)
- Includes player statistics (batting, bowling), team scores, and match results

---

## 🔄 Project Workflow

1. **Web Scraping**  
   - Use `requests` and `BeautifulSoup` to fetch HTML content
   - Extract tables for batting and bowling scorecards

2. **Data Cleaning & Transformation**  
   - Parse and clean data using `Pandas`
   - Merge, filter, and reshape datasets into analysis-ready format

3. **Power BI Integration**  
   - Import cleaned `.csv` files into Power BI
   - Build relationships and KPIs (Runs, Wickets, Strike Rates, etc.)
   - Create dynamic visuals and dashboards

---

## 📈 Power BI Dashboard

The Power BI dashboard includes:
- Top Batsmen by Runs & Strike Rate
- Best Bowlers by Economy & Wickets
- Team-wise Performance Summary
- Most Valuable Player (MVP)
- Filterable match-by-match statistics

---

## 💡 Key Insights

- Top-performing players across the tournament
- Team comparisons based on aggregated statistics
- Identification of consistent match-winners
- MVP-based selection for the Best Playing XI

---

