# NBA Data Scraper 
The goal of this project is to scrape sports data from a given URL and transform it into a structured format (Pandas DataFrame) for further analysis. This scraper is designed to collect team rankings and performance statistics, which can then be used for sports prediction models.

## Key Features:
- Scrapes Sports Data from a specified URL using Selenium and BeautifulSoup.
- Extracts Table Data: The scraper identifies and extracts relevant information from the table on the webpage, including rankings, team names, and additional statistics.
- Transforms Data: The scraped data is converted into a structured Pandas DataFrame, making it ready for analysis.
- Export to CSV: The DataFrame can be easily exported to a CSV file for storage or further use in sports analytics projects.


## How It Works:

### Data Collection:

The scraper uses Selenium to load the webpage, ensuring that dynamic content is rendered before scraping.
BeautifulSoup is used to parse the page source and extract the data from the table.
Data Transformation:

The extracted data is organized into a structured format and stored in a Pandas DataFrame.
Columns such as Rank, Team, and additional statistics are dynamically extracted based on the HTML structure of the table.
Data Export:

The save_to_csv method allows users to export the DataFrame to a CSV file, facilitating easy sharing and analysis.
