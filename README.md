# NBA Stats Analysis - Tableau Dashboard

## Introduction

This project is centered around a comprehensive analysis of NBA regular season data over the past 20 years. Data was scraped from [nba.com/stats](https://www.nba.com/stats/) and subsequently visualized using Tableau to draw insights and patterns from player performances, team metrics, and more.

## Data Scraping

### Source

The primary data source for this project is the official NBA statistics website: [nba.com/stats](https://www.nba.com/stats/).

### Tools & Libraries

- **[Python](https://www.python.org/)**: The primary language used for scripting the web scraping process.
- **[pandas](https://pandas.pydata.org/)**: A powerful data analysis and manipulation library for Python.
- **[requests](https://docs.python-requests.org/en/master/)**: A simple HTTP library for Python, used to fetch the data from the NBA stats website.

### Process

1. **Setting Up Environment**: 
   - Imported necessary libraries: `pandas` for data manipulation and `requests` for fetching online data.
   - Configured pandas to display all columns for wide dataframes.

2. **Fetching Data**:
   - Made an HTTP request to fetch regular season data from the NBA stats website for the 2003-04 season, focusing on the 'PTS' (points) stat category.

3. **Data Processing**:
   - Extracted column headers and row data from the returned JSON response.
   - Formed a pandas DataFrame from the extracted data.
   - Added additional columns for 'year' and 'Season_type' to provide context to the dataset.

_Note: This process was repeated for each season over the past 20 years to form a comprehensive dataset. For those interested in replicating or building upon this work, please ensure you adhere to the terms of service and usage policies of any website you scrape._

## Tableau Dashboard

After processing the scraped data, I created a comprehensive Tableau dashboard to visualize the dataset and draw meaningful insights.

[View the NBA Stats Tableau Dashboard](https://public.tableau.com/views/NBAstatsTableau/NBAStatsDashboard?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

## Insights & Observations

- **[Insight 1]**: Brief description of the insight.
- **[Insight 2]**: Another observation or pattern noticed from the data.

_Feel free to explore the dashboard and derive your own insights!_

## Future Work

- Extend the data scraping to cover playoff statistics.
- Integrate advanced metrics and analytics for a deeper analysis.

## Acknowledgments

Huge thanks to the NBA for maintaining a comprehensive stats database and Tableau for providing a powerful platform for data visualization.

---

**Disclaimer**: This project is for educational and research purposes. Ensure you have the right to scrape and use data from any website.

