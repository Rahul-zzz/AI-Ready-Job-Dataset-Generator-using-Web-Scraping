# AI-Ready-Job-Dataset-Generator-using-Web-Scraping

📖 Project Overview
This project is a Python-based web scraping automation tool that extracts job listings from Naukri.com. It collects important job details such as job title, company name, location, required skills, posting date, and job URL, and stores them in a structured CSV format for further analysis.


⚙️ Features
Automated job search on Naukri.com
Extracts job title, company, location, skills, and job link
Handles multiple job roles in a single run
Stores data in structured CSV format
Includes basic error handling for stable execution


🧰 Technologies Used
Python
Selenium WebDriver
Pandas
ChromeDriver


📂 Project Structure
naukri-job-scraper/
│
├── naukri_final.py        # Main scraper script (final version)
├── naukri.py              # Basic scraper version
├── inspect_naukri.py      # Debugging script
├── selenium_test.py       # Selenium setup test
├── jobs.csv               # Output file (generated after run)
└── README.md              # Project documentation


🚀 How It Works
Opens Chrome browser using Selenium
Navigates to Naukri job search pages
Extracts job details from job cards
Stores extracted data in a list
Converts data into a Pandas DataFrame
Saves final output as a CSV file


▶️ How to Run
pip install selenium pandas
python naukri_final.py

Make sure ChromeDriver is installed and matches your Chrome version.


📊 Output
A CSV file named jobs.csv will be generated containing all scraped job listings in structured format.


🎯 Learning Outcome
Web scraping using Selenium
Handling dynamic websites
Data extraction and automation
Working with Pandas for data storage
Basic debugging and testing of automation scripts


📌 Note
This project is for educational purposes only and demonstrates web automation and data extraction techniques using Python.
