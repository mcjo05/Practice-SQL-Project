# Practice-SQL-Project
Cleaned and analyzed layoff data using SQL (from a YouTube tutorial). Focused on removing duplicates, handling nulls, and uncovering insights like top companies and countries affected by layoffs. Strengthened my SQL data cleaning and analysis skills.
# 📊 Layoffs Data Cleaning & Analysis Project (SQL)

This project is based on a YouTube tutorial and demonstrates how to clean and analyze a real-world dataset using SQL. It covers the full cycle from raw data to extracting key business insights.

## 📁 Dataset
- Source: https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbkpKcXVXcExpSnRlbjlQaElFOHFQbDZrdXJtZ3xBQ3Jtc0tuYzVLLXBUN2ExOUc5ZUdHaEc4ZEpLRm9nQ1VycWxDaXc2NXJZc0poRFRvbjNHajBsVDhPQW9QTVVsLTZhOTVrX0VVOWYyMlBNdHE4eGdWT2FaUzhEUEp6b0tRanRTVjE1SGNheFFLeWFVdEVYSWVEZw&q=https%3A%2F%2Fgithub.com%2FAlexTheAnalyst%2FMySQL-YouTube-Series%2Fblob%2Fmain%2Flayoffs.csv&v=4UltKCnnnTA
- Format: CSV
- Fields include: company, industry, total_laid_off, percentage_laid_off, country, date, etc.

## 🧼 Phase 1: Data Cleaning

Performed in SQL to prepare the data for analysis:

- Removed rows with null values in critical columns
- Standardized inconsistent formatting (e.g., trimmed whitespace, fixed case)
- Corrected company names with formatting issues
- Converted date fields into proper formats
- Removed duplicate records
- Filtered for relevant rows (e.g., removed blank or test entries)

> 💡 Tools used: SQL Server Management Studio (SSMS)

## 📈 Phase 2: Exploratory Data Analysis

Key insights derived from exploratory queries:

- 📉 **2022 had the most layoffs**, with over 150,000 employees laid off globally.
- 🏢 **Top 5 companies with the most layoffs** include: Amazon, Meta, Google, Microsoft, and Twitter.
- 🌐 **The U.S. accounts for the majority of layoffs**, followed by India and Canada.
- 🏭 **Tech industry** dominates layoffs across all years in the dataset.
- 🔄 There was a sharp increase in layoffs during and after the COVID-19 pandemic.

> 💡 Used `GROUP BY`, `ORDER BY`, `WHERE`, and date functions to extract trends.

## 📌 Skills Demonstrated

- SQL Data Cleaning Techniques
- Aggregate Functions (`SUM()`, `COUNT()`)
- Data Exploration with `GROUP BY`, `HAVING`, and Filtering
- Handling NULLs and Duplicates
- Working with Date/Time formats
- Real-world thinking: drawing insights from workforce trends

## 🧠 Learnings

- Practiced best practices in SQL cleaning and querying
- Improved logic in handling real-world messy data
- Understood global employment impact post-pandemic

## 📂 Files Included

- `Practice SQL Project - World Layoffs Cleaning` — full SQL file with all queries
- `layoffs.csv` — raw dataset
- `Practice SQL Project - World Layoffs Exploratory` — notes on exploratory analysis

## 📺 Credits

This project is based on a https://www.youtube.com/watch?v=4UltKCnnnTA&list=PLUaB-1hjhk8FE_XZ87vPPSfHqb6OcM0cF&index=19. The original dataset and walkthrough helped shape this end-to-end mini project.

## 📎 Portfolio Link

You can view this project in my portfolio:  
🔗 https://www.notion.so/Hey-there-I-am-Michael-Joash-2304f9a1c24980b481a8c3002acf3d4e?source=copy_link

