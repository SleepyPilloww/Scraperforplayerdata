# Scraperforplayerdata
Web Scraper to extract data from ESPN Cricinfo 


## ⚙️ Requirements 

Install dependencies using:

```bash 
pip install requests beautifulsoup4 pandas openpyxl

# 🏏 ESPNcricinfo Player Career Stats Scraper

This Python script allows you to extract **comprehensive batting and bowling statistics** of any cricketer from [ESPNcricinfo's Statsguru](https://stats.espncricinfo.com), across various formats like:

- Tests
- ODIs
- T20Is
- First-Class
- List A
- Domestic T20s
- IPL

The statistics are combined into a **single Excel sheet** with additional columns such as format, level (international/domestic/IPL), and stat type (batting/bowling).

---

## 📊 Features

✅ Fetches:
- Batting & Bowling stats  
- Across all major formats (international, domestic, IPL)  
- Combines all formats into a single Excel sheet  
- Automatically handles different stat structures  
- Outputs `.xlsx` file, ready for Excel or Google Sheets

---

## 📂 Output Columns

The resulting file contains columns such as:

| Format | Level | Type | Class | Matches | Innings | Runs | Average | Wickets | Economy | ... |
|--------|-------|------|-------|---------|---------|------|---------|---------|---------|-----|

(*Actual columns may vary depending on stat type and data availability*)

---

## ⚙️ Requirements

Install dependencies:

```bash
pip install pandas openpyxl
