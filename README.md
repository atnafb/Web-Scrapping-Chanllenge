# Web-Scrapping-Chanllenge Mars News and Weather Data

## Overview

This repository contains the results of a web scraping challenge where I scraped Mars-related data, focusing on two key deliverables: Mars news and Mars weather.

### Deliverable 1: Scrape Titles and Preview Text from Mars News Articles
The task involved scraping titles and preview text from Mars news articles to collect essential headlines and summaries. The data was scraped from a Mars news website using the following tools and libraries:
- **Jupyter Notebook** for coding environment
- **Python** for general programming
- **BeautifulSoup** for parsing HTML content
- **JSON** for saving the scraped data in json format

The scraped data was saved in a JSON file named `scraped_mars_news_data.json` and can be found in this repo.

### Deliverable 2: Scrape and Analyze Mars Weather Data
In this deliverable, I scraped Mars weather data, which exists in a table format on a website. The task involved extracting temperature, pressure, and other atmospheric data. The tools used for scraping and data analysis were:
- **Jupyter Notebook** for the development environment
- **Pandas** for manipulating and analyzing data
- **BeautifulSoup** for scraping the weather data table
- **Matplotlib** for visualizing the temperature and pressure trends

The weather data was converted into a pandas DataFrame and saved as a CSV file named `mars_temp_data.csv` and can be found in this repo.

---

## Files in this Repository:
- **scraped_mars_news_data.json**: JSON file containing scraped titles and preview texts of Mars news articles.
- **mars_temp_data.csv**: CSV file containing scraped Mars weather data (temperature, pressure, etc.).
- **part_1_mars_news.ipynb** Jupyter notebook that contain codes and analysis of the scrapped news data
- **part_2_mars_weather.ipynb** Jupyter notebook that contain codes and analysis of the scrapped weather data 

## Requirements to run 
- Jupyter Notebook
- Python (3.x)
- BeautifulSoup
- Pandas
- Matplotlib
- JSON

## How to Run:
1. Clone this repository.
2. Install the required libraries:
   ```bash
   pip install beautifulsoup4 pandas matplotlib
