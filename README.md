# Web Scraper

This Python script scrapes case details from a website and saves them to a CSV file.

## Prerequisites

Before running the script, make sure you have Python installed on your system. You also need to install the following Python libraries:

pip install selenium pandas beautifulsoup4


Additionally, download the ChromeDriver from the official website: [ChromeDriver Downloads](https://sites.google.com/a/chromium.org/chromedriver/downloads)

## Usage

1. Replace the `path` variable in the code with the path to the ChromeDriver executable on your system.
2. Run the Python script.
3. The scraped data will be stored in a CSV file named `detailed_cases.csv` on your Desktop.

## Customization

- You can modify the website URL, search queries, and other parameters in the script according to your requirements.
- Customize the file path to save the CSV file in a location of your choice.

## Note

- Ensure that you have an active internet connection while running the script.
- The script may take some time to execute, depending on the number of cases to scrape and the website's response time.
