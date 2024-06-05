# Mars Web-Scraping and Data Analysis Project
## Overview
This project involved utilizing web scraping and data analysis techniques to collect, organize, and analyze data related to Mars. The project comprised two main tasks: scraping Mars news articles and analyzing Mars weather data.

## Deliverables
Scraped Mars News Articles:

Utilized Splinter for automated browsing to visit the Mars news site.
Employed Beautiful Soup to parse HTML and extract titles and preview text of news articles.
Stored the data in a list of dictionaries, with each dictionary containing the title and preview text.

Scraped and Analyzed Mars Weather Data:

Visited the Mars Temperature Data Site using Splinter.

Parsed the HTML table using Beautiful Soup to extract weather data.

Assembled the data into a Pandas DataFrame with columns for id, terrestrial_date, sol, ls, month, min_temp, and pressure.

Analyzed the data to determine the number of months on Mars, the number of Martian days with data, and the average minimum temperatures and atmospheric pressures for each month.

Created bar charts to visualize temperature and pressure data.

Estimated the number of terrestrial days in a Martian year using the data.

Exported the final DataFrame to a CSV file for further analysis and sharing.

This project required skills in web scraping, data organization, analysis, and visualization, providing valuable insights into Mars' climate and news.
