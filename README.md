[README_updated (1).md](https://github.com/user-attachments/files/32366423/README_updated.1.md)
# 🎮 Game Market Analysis (Steam + GOG)

## 📌 Project Overview

This project analyzes video game data collected from two platforms:

- Steam  
- GOG (Good Old Games)

The objective is to explore:
- pricing behavior of games  
- user ratings and popularity  
- impact of discounts  
- differences between platforms  
- trends in game releases over time  

The project follows a complete data analysis pipeline:

1. Web Scraping (Data Collection)  
2. Data Cleaning & Transformation  
3. Exploratory Data Analysis (EDA)  
4. Data Visualization  

The final dataset contains approximately 10,000 records.

---

## ⚙️ Dependencies

Install all required libraries:

pip install pandas numpy requests beautifulsoup4 matplotlib seaborn plotly squarify lxml

---

## 🚀 How to Run the Code

Step 1 — Run Scrapers:
python gog_scraper.py
python steam_scraper.py

Step 2 — Clean Data:
python gog_cleaning.py
python steam_cleaning.py

Step 3 — Combine Data (Python):
python combining two csv

Step 4 — Run EDA:
python eda_analysis.py

Step 5 — Run Visualization:
python visualization.py

---

## 📊 Dataset Description

Each record includes:
APP_ID, Title, Genre, Rating, Votes_In_Rates, Released_Date, Discount, Price, Platform, Director_Author, Product_URL, Source

---

## 👨‍💻 Author
 Dastan Medetov
