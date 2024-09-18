# Netflix Stock Data Scraper

**Purpose:**
This Jupyter Notebook scrapes daily stock data for Netflix from a webpage and stores it in a pandas DataFrame.

**Requirements:**
* Python 3.x
* pandas library (`pip install pandas`)
* requests library (`pip install requests`)
* beautifulsoup4 library (`pip install beautifulsoup4`)

**Usage:**
1. Install the required libraries using `pip install pandas requests beautifulsoup4`.
2. Run this Jupyter Notebook.
3. The output will display the first few rows of the extracted Netflix stock data.

**How it Works:**
1. Imports necessary libraries.
2. Defines a URL pointing to the webpage containing Netflix stock data.
3. Fetches the webpage content using `requests` and parses it with BeautifulSoup.
4. Creates an empty pandas DataFrame.
5. Iterates through each table row (`tr`) within the webpage's `tbody` element.
6. Extracts data for individual columns ("Date", "Open", ..., "Volume").
7. Appends a new row containing the extracted data to the DataFrame.
8. Prints the first few rows of the DataFrame.

**Note:**
* This script relies on a specific webpage structure and might need adjustments if the HTML changes.
* This script is for educational purposes only and may not be suitable for commercial use.

**Disclaimer:**
The data source might not be guaranteed to be complete or accurate. Always refer to official sources for reliable financial information.
