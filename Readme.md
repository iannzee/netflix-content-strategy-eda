# 🍿 Netflix Content Strategy Data Analysis

## 📌 Project Overview
This project is an Exploratory Data Analysis (EDA) of Netflix's content catalog. The goal of this analysis is to extract actionable business insights regarding Netflix's content strategy, regional production hubs, and historical growth trends. 

## 🛠️ Tech Stack
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / VS Code

## 🧹 Data Cleaning & Preprocessing
Real-world data requires strategic cleaning. In this project:
* Handled missing text data (e.g., Directors, Cast, Country) by strategically imputing "Unknown" to preserve valuable row data.
* Dropped a negligible percentage of rows with missing critical dates or ratings.
* Applied **Feature Engineering** to convert string-based release dates into formal `datetime` objects and extracted the exact `year_added` for time-series analysis.

## 📊 Key Business Insights Discovered
1. **Content Strategy (Movies vs. TV Shows):** Netflix's historical library heavily favors Movies over TV Shows, maintaining roughly a 2:1 ratio.
2. **Top Global Producers:** The **United States** is the leading content producer for the platform, followed closely by **India**, highlighting Netflix's heavy investment in the Bollywood and Indian tech/entertainment markets.
3. **Content Expansion Over Time:** Content additions peaked sharply between **2018 and 2020** (coinciding with the height of the streaming wars and pandemic-driven home entertainment demand) before experiencing a production drop-off.

## 📂 Project Structure
```text
netflix-eda-project/
│
├── data/
│   └── netflix_titles.csv       # Raw dataset (downloaded from Kaggle)
├── notebooks/
│   └── netflix_eda.ipynb        # Main Jupyter Notebook with code and analysis
└── README.md                    # Project documentation
