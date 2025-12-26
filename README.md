* G2 Review Scraper 
This project is a Python Selenium-based web scraper that collects customer reviews from G2.com for a given software product within a specified date range.

* The script:
1. Opens G2 review pages using Selenium
2. Extracts review title, content, and date
3. Filters reviews between a start date and end date
4. Saves the results into a JSON file
5. If no live reviews are found, a fallback sample review is saved.

* Technologies Used
1. Python
2. Selenium WebDriver
3. ChromeDriver (webdriver-manager)
4. JSON
5. Date parsing (python-dateutil)

* Files in the Project
1. scraper.py (main Python script)
2. README.md
3. Output file: <company>_g2_reviews.json

* Required Libraries
1. Install the required packages before running the script:
2. pip install selenium webdriver-manager python-dateutil

* How to Run the Script
1. Open the project folder in VS Code
2. Open the terminal
3. Run the script:python scraper.py
4. Enter the required inputs when prompted:
5. Company name (URL slug), example: slack
6. Start date (YYYY-MM-DD)
7. End date (YYYY-MM-DD)

* How the Script Works
1. Launches Chrome using Selenium
2. Navigates to G2 review pages (up to 5 pages)
3. Waits for review cards to load
4. Extracts review title, review text, and review date
5. Filters reviews based on the given date range
6. Saves the results into a JSON file
7. Writes fallback data if no live reviews are found

* Output
The output is saved as a JSON file named:
<company>_g2_reviews.json

