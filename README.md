# Mars Data Scraper: A Journey into Martian Data

## Background

After diving into the world of web scraping and data analysis, I've developed this project to showcase my skills in collecting, organizing, analyzing, and visually communicating data. Using Python libraries like Beautiful Soup for HTML parsing and Splinter for automated browsing, I've focused on scraping and analyzing data related to Mars.

## What This Project Does

### Deliverable 1: Mars News Scraper

In this part, I've automated the process of visiting a Mars news website to scrape the latest news titles and their preview text. The scraped data is stored in Python dictionaries and lists, making it easier for further analysis or to export as a JSON file.

Example of scraped data:
```python
{'title': "NASA's MAVEN Observes Martian Light Show Caused by Major Solar Storm", 
 'preview': "For the first time in its eight years orbiting Mars, NASA’s MAVEN mission witnessed two different types of ultraviolet aurorae simultaneously, the result of solar storms that began on Aug. 27."}
```

### Deliverable 2: Mars Weather Data Analyzer

For this section, I've scraped Mars weather data from a table on a specific website. The data is assembled into a Pandas DataFrame, which allows for easy analysis. The DataFrame includes the following columns:

- `id`: Identification number of a single transmission from the Curiosity rover
- `terrestrial_date`: The date on Earth
- `sol`: Number of elapsed Martian days since Curiosity landed
- `ls`: The solar longitude
- `month`: The Martian month
- `min_temp`: Minimum temperature in Celsius for a single Martian day
- `pressure`: Atmospheric pressure at Curiosity's location

I've also made sure to examine and convert the data types for each column to ensure accurate analysis.

## Getting Started

### Files

To get a better understanding of the project, you can check out the Jupyter Notebooks in the repository:

- `part_1_mars_news.ipynb`: Contains the code and analysis for Deliverable 1
- `part_2_mars_weather.ipynb`: Contains the code and analysis for Deliverable 2

## Future Work

- Export the scraped data to a database for real-time analysis
- Implement data visualization techniques to better communicate the findings
- Extend the project to scrape data from additional Mars-related sources

Feel free to dive into the code and notebooks to get a deeper understanding of the project!