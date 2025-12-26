G2 Review Scraper (Selenium + Python) 
This project is a Python Selenium-based web scraper that collects customer reviews from G2.com for a given software product within a specified date range. The script: Opens G2 review pages using Selenium Extracts review title, content, and date Filters reviews between a start date and end date Saves the results into a JSON file If no live reviews are found, a fallback sample review is saved.
Technologies Used are Python, Selenium WebDriver, ChromeDriver (webdriver-manager), JSON, Date parsing (python-dateutil)
Files in the Project are scraper.py (main Python script), README.md, Output file: <company>_g2_reviews.json
How to Run the Script: Open the project folder in VS Code, Open the terminal, Run the script: python scraper.py, Enter the required inputs when prompted: Company name (URL slug), example: slack Start date (YYYY-MM-DD) End date (YYYY-MM-DD)
