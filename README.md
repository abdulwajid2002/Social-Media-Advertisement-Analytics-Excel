# Social Media Advertisement Analytics — Excel Dashboard

---

## 📌 Project Overview
This project evaluates historical performance across **15,000+ social media advertising campaigns** run on Facebook, Instagram, Twitter, and Pinterest. The objective was to clean an unformatted raw dataset, engineer core financial and engagement metrics, and build a dynamic Excel dashboard to support marketing budget decisions.

---

## 📊 Key Performance Summary
* **Total Impressions:** 208,981,224
* **Total Clicks:** 67,427,454
* **Average Conversion Rate:** 8.02%
* **Total Acquisition Cost:** $28,727,298
* **Net Profit:** $82,348,831

---

## 🧹 Data Cleaning & Transformation
Working from the raw dataset (`Social Media Marketing Dataset (2).xlsx`), the following steps were executed in Excel:
* **Duplicate Audit:** Checked and verified unique `Campaign_ID` entries across all records.
* **Demographic Parsing:** Split the `Target_Audience` field into separate `Gender` and `Age_Group` columns to analyze demographic segments independently.
* **Text & Format Cleanup:** Removed special characters (`*`, `$`) from `Campaign_Goal`, stripped newline characters from `ROI`, and separated numeric values from text strings in `Duration`.
* **Calculated Columns:**
  * `Net Profit` = `ROI * Acquisition_Cost`
  * `Clicks/Day` = `Clicks / Duration`

---

## 📈 Dashboard Architecture & Analysis
The final workbook (`Portfolio Project.1 ABDUL WAJID.xlsx`) includes structured Pivot Tables feeding an interactive dashboard controlled by Slicers (`Campaign_Goal`, `Channel_Used`, `Age_Group`, `Gender`, `Location`, `Customer_Segment`) and a Date Timeline:
* **Campaign Goal Engagement:** Compared average engagement scores across *Increase Sales*, *Market Expansion*, *Brand Awareness*, and *Product Launch*.
* **Audience Breakdown:** Analyzed campaign distribution across age brackets (18–24, 25–34, 35–44, 45–60) split by Male and Female segments.
* **Regional Spend:** Mapped total acquisition costs across targeted cities including Las Vegas, Miami, New York, Austin, and Los Angeles.
* **Monthly Click Volume:** Tracked monthly click trends to identify seasonal performance shifts.

---

## 📂 Repository Structure
* `Social Media Marketing Dataset (2).xlsx` — Raw dataset (15,000+ rows)
* `Portfolio Project.1 ABDUL WAJID.xlsx` — Cleaned data, Pivot Tables, and interactive dashboard
* `Project_Social Media Advertisement Analytics (1).pdf` — Case study brief and project requirements

---

## 👤 Author

**Abdul Wajid** — Data Analyst & Business Consultant

[![LinkedIn](https://img.shields.io/badge/LinkedIn-abdul--wajid--dataanalyst-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdul-wajid-dataanalyst/)
[![GitHub](https://img.shields.io/badge/GitHub-abdulwajid2002-181717?style=flat&logo=github&logoColor=white)](https://github.com/abdulwajid2002)
