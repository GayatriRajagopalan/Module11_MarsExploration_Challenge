# Mars News & Weather Data Analysis

This project involves scraping and analyzing data from Mars News and Mars Weather data sources. The two main tasks are:

1. Scraping Mars news article titles and preview text. 
2. Scraping and analyzing Mars weather data, including temperature and pressure.
   
The project utilizes web scraping techniques using Splinter and Beautiful Soup, data manipulation with Pandas, and visualization with Matplotlib.

# Project Overview

This project is split into two parts:

Part 1: Scrape Titles and Preview Text from Mars News

Goal: Scrape news article titles and their preview text from a Mars news website.

Tools Used: Splinter for automated browsing, Beautiful Soup for HTML parsing.

Output: A list of dictionaries containing article titles and preview text. The data is also saved to a JSON file.


Part 2: Scrape and Analyze Mars Weather Data

Goal: Scrape Mars weather data from a specified webpage containing temperature and pressure information from the Curiosity rover.

Tools Used: Beautiful Soup for web scraping, Pandas for data analysis, Matplotlib for visualization.

Output: A CSV file containing the scraped data

# Setup Instructions

To get started with the project, ensure you have the following Python libraries installed:

Splinter (for automated browsing)

Beautiful Soup (for HTML parsing)

Pandas (for data manipulation)

Matplotlib (for plotting and visualizations)

# Data Analysis

Part 1: Mars News Scraping

Scrape titles and preview text from news articles.

Each article is stored as a dictionary with keys: title and preview.

These dictionaries are stored in a Python list and then exported to a JSON file.

Part 2: Mars Weather Data Analysis

Scrape data from a Mars temperature and pressure table.

Analyze the following:

How many months exist on Mars?

How many Martian days worth of data exist?

Which month has the coldest and warmest temperatures?

Which month has the lowest and highest atmospheric pressures?

Estimate how many Earth days are equivalent to a Martian year.

# Visualization

Part 1: This part does not require any data visualization. The data is just scraped and stored in a list of dictionaries.

Part 2: Visualizations include:

A bar chart showing the coldest and warmest months based on minimum temperature.

A bar chart showing the months with the highest and lowest atmospheric pressure.

A line plot estimating how many Earth days correspond to a Martian year based on temperature observations.

# Exports

Part 1: Scraped Mars news data is saved in a JSON file (scraped_data.json).

Part 2: The final Mars weather data is exported into a CSV file (output/mars_weather.csv)

# License

This project is licensed under the MIT License 

# Conclusion

This project demonstrates how web scraping can be used to gather valuable information from websites, clean and process the data, and create insightful visualizations.


