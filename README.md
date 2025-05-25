# 📊 Web Scraping Fortune 500 Companies from Wikipedia

## 🚀 Project Overview
This project automates the extraction of data from Wikipedia’s page listing the **largest companies in the United States by revenue**. Using Python, it scrapes company information such as revenue, profit, number of employees, and industry sector. The data is then structured using pandas and exported to a CSV file for analysis.

---

## 🛠️ Tools & Technologies
- **Python**
- `requests` – For sending HTTP requests
- `BeautifulSoup` – For parsing HTML content
- `pandas` – For cleaning and exporting structured data

---

## 📁 Features
- Automatically scrapes updated company data from Wikipedia
- Parses and structures HTML tables into clean DataFrames
- Exports extracted data to a CSV file
- Ready for further analysis in Power BI, Excel, or Python

---

## 📂 Output
The script generates a file named:


This file includes columns such as:

- Rank
- Name
- Industry
- Revenue
- Profit
- Employees
- Headquarters

---

## ▶️ How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/fortune500-scraper.git
cd fortune500-scraper

# (Optional) Create a virtual environment
python -m venv env
source env/bin/activate  # or env\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run the script
python scrape_fortune500.py
