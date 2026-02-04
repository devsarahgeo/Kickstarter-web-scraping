# Web Scraping for Kickstarter website

## 🧭 Executive Summary
Engineered an automated web scraping solution to extract campaign data from Kickstarter, then conducted exploratory data analysis to identify key success patterns. An analysis of 15K+ campaigns revealed insights into funding success rates, high-performing categories, and geographic concentration of crowdfunding activity.

---

### 💼 Business Problem
Crowdfunding platforms like Kickstarter generate millions in pledges annually, yet most entrepreneurs lack visibility into what drives campaign success. The goal of this project is to mainly to collect data and do an analysis that provides data-driven insights to inform campaign strategy and resource allocation.

---

## ❓ Analysis Questions 
- What is the Overall Success Rate?
- Who are the Category Performance Leaders?
- What is the Geographic Concentration of these campaigns?

---

- ## 💻 Git File Structure Explained:

<strong>Kickstarter_webscraping_code.ipynb</strong> : This code does the webscraping and analysis using Python.

<strong>scraped_data/</strong> : This folder has the final output results. Mainly final_combined.csv has all the scarped records.

---

## 🧠 Skills & Tech Stack
- **Languages & Libraries** – Python, Pandas
- **Web Scraping** - BeautifulSoup & Selenium

---

## ⚙️ Methodology

### What I built:
- Developed Python scripts to **automatically** extract campaign data from Kickstarter
- **Automated** navigation through pages and collected **15K+ campaign data** with 20+ attributes each
- **Automated** data collection process, reducing manual effort by 95%


### Process:

### 1. Data Collection
- Used Selenium for dynamic page navigation and scrolling.
- Used BeautifulSoup for parsing and extracting HTML content.
- Collected details such as project title, category, goal, pledged amount, backers, and project status.
  
### 2. Data Cleaning & Processing
- Removed duplicates and incomplete records.
- Exported the cleaned dataset to CSV for further analysis.

### 3. Exploratory Analysis (EDA)
- Performed summary statistics on success vs failure rates.
  
---

## 📈 Results
- Extracted a structured dataset of Kickstarter projects for analysis.
- Identified campaigns that reached or exceeded their funding goal, identified geographic concentratin and popular capign categories
  
<img width="1297" height="707" alt="Screenshot 2026-02-04 at 11 37 04 AM" src="https://github.com/user-attachments/assets/58a0dac8-d80f-4524-b65a-fb3f9d0bb8c2" />

---

## 📊 Business Insights & Recommendations

  ### 1. **Strong Overall Success Rate**
- **65% of campaigns reached or exceeded their funding goal**
- Indicates healthy platform performance and backer engagement
- <b>Recommendation:</b> Focus on high-performing categories with proven 65% success track record

### 2. **Category Performance Leaders**
- **Shorts and Music** emerged as the most popular campaign categories
- Suggests strong audience demand for creative content projects
- <b>Recommendation:</b>  Target these categories for higher visibility and backer interest

### 3. **Geographic Concentration**
- **Los Angeles and New York** dominate campaign activity
- Reflects concentration of creative industries and entrepreneurial ecosystems. Geographic targeting and local marketing could enhance campaign success.
- <b>Recommendation:</b>  Increase support/resources in LA & NYC markets where activity is highest

## 🚀 Outcome
Gained hands-on experience in automated web scraping and insight generation — key steps in transforming raw online data into actionable startup intelligence.

## ⚡ Future Scope
### 1. Temporal Trend Analysis
- **Launch Timing Optimization:** Determine best days/months to launch campaigns
- **Seasonal Patterns:** Identify holiday effects and seasonal funding trends
- **Duration Analysis:** Optimal campaign length (15 vs. 30 vs. 60 days)
- **Funding Velocity:** Early momentum indicators that predict success



