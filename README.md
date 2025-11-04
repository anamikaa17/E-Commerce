# 🛒 E-Commerce Product Price Scraper

A Python-based web scraper that compares product prices across **Amazon**, **Flipkart**, and **Google Shopping** using Selenium and BeautifulSoup.  
The results are stored in an SQLite database and displayed in a clean, sortable HTML report.

## 🚀 Features
- Scrapes product details and prices from multiple sites.
- Stores all results in `scraper.db`.
- Generates a professional HTML report with:
  - ✅ Price sorting (High → Low / Low → High)
  - ✅ Search/filter feature
  - ✅ Auto-numbered results

## 🧩 Tech Stack
- Python 3
- Selenium + BeautifulSoup
- SQLite3
- HTML + JavaScript for report

## ⚙️ How to Run
```bash
pip install -r requirements.txt
python scraper.py
python results.py
