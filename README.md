# CODSOFT_TASK5
# CodSoft Internship - Task 5: Web Data Extraction & Analysis

## About this task
This is Task 5 (final task) of my Data Analytics internship with CodSoft. 
The goal was to scrape data from a website using Python, organize it into a 
proper dataset, and analyze it.

## What I did
- Used BeautifulSoup and the requests library to scrape book data from 
  books.toscrape.com (a website built specifically for practicing web scraping)
- Extracted title, price, star rating, and availability for each book
- Automated the scraping across 20 pages to collect 400 books total
- Cleaned the scraped data - converted price text into proper numbers 
  (had to deal with a currency symbol encoding issue), converted star ratings 
  from words like "Three" into actual numbers
- Checked the data for missing values and duplicates
- Did some basic analysis - average price, price by rating, most expensive books
- Made charts showing price distribution and rating distribution
- Exported the final dataset to CSV

## Key findings
- Average book price was about £34.96
- Ratings were fairly evenly spread across 1 to 5 stars (roughly 73-88 books 
  in each rating category)
- There wasn't a clear relationship between price and rating - the most 
  expensive books weren't necessarily the highest rated ones

## Tools
Python, BeautifulSoup, Requests, Pandas, Matplotlib, Google Colab

## Files in this repo
- CodSoft_Task5_WebScraping.ipynb - all the code
- scraped_books.csv - the final scraped dataset
- task5_chart.png - price and rating distribution charts

#codsoft #dataanalytics #webscraping
