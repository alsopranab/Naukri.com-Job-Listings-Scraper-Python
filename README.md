# Naukri Job Listings Scraper (No Login)

A production-ready web scraping and exploratory data analysis (EDA) pipeline in **Python** for scraping recent job listings from Naukri.com without requiring any user login. [web:1][web:2]

---

## Project Overview

- Scrapes publicly available job listings from Naukri.com. [web:2][web:11]
- Focuses on jobs posted within the last 24 hours.
- Cleans, structures, and analyzes data to understand job market trends.
- Emphasizes experience requirements and their variance across listings. [web:2]

---

## Objectives

- Scrape publicly available job listings from Naukri.com.
- Filter jobs posted within the last 24 hours.
- Extract structured job information.
- Clean and transform experience ranges into numeric values.
- Perform exploratory data analysis.
- Visualize experience variance.

---

## Tech Stack

- **Python**
- Selenium [web:13][web:15]
- WebDriver Manager
- Pandas
- Matplotlib
- Jupyter Notebook

---

## Data Fields

The scraper extracts the following fields for each job:

- Job Title  
- Company  
- Location  
- Experience  
- Posted  
- Job Link  

All extracted data is saved in CSV format for analysis. [web:2][web:4]

---

## Project Structure

- Modular Selenium-based scraper.
- Explicit waits and controlled delays for JavaScript-rendered content. [web:13]
- Defensive selectors to handle DOM changes. [web:5][web:13]
- Separate scraping and EDA logic.
- CSV-based data persistence.

---

## Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/naukri-job-scraper.git
cd naukri-job-scraper
```

Install Dependencies
```
pip install selenium webdriver-manager pandas matplotlib
```
For Jupyter Notebook users:
```
pip install selenium webdriver-manager pandas matplotlib
```
How to Run
```
python naukri_scraper.py
```
After execution, the output file will be generated:
```
naukri_jobs_last_24_hours.csv
```

# Disclaimer
> This project is created strictly for educational purposes.
> 
> It accesses only publicly available information and does not bypass authentication or security mechanisms of any platform.


with regards,
@alsopranab
