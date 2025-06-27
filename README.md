# Uber_Data_Analytics_Project---Modern Data Engineering GCP Project

## Introduction

The goal of this project is to perform data analytics on Uber trip data using a modern data engineering stack on Google Cloud Platform (GCP). This project leverages GCP Storage, Python, Compute Instance, Mage Data Pipeline Tool, BigQuery, and Looker Studio to extract, transform, load, and visualize insights from large-scale taxi trip data.

## 📎 Technology Used

- **Programming Languages:** Python, SQL
- **Google Cloud Platform Services:**
  - Google Cloud Storage (for raw data storage)
  - Compute Instance (for data processing)
  - BigQuery (for data warehousing and analytics)
  - Looker Studio (for dashboarding and visualization)
- **Modern Data Pipeline Tool:** Mage ([mage.ai](https://www.mage.ai/))

## Dataset Used

- **Source:** NYC TLC Trip Record Data (Yellow and Green taxi trip records)
- **Fields Include:**
  - Pick-up and drop-off dates/times
  - Pick-up and drop-off locations (latitude/longitude)
  - Trip distances
  - Itemized fares (base fare, taxes, surcharges)
  - Rate types
  - Payment types (credit card, cash, etc.)
  - Driver-reported passenger counts

- **More info:**
  - [TLC Trip Record Data Website](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
  - [Data Dictionary](https://drive.google.com/file/d/1OYlh0BCoN4i3dUtJEvZ2_ArzzJkdq1YB/view?usp=sharing)

## Dashboard

- **Looker Studio Dashboard:**  
  [View Dashboard](https://lookerstudio.google.com/reporting/f6d83de6-42d6-471f-a7a9-384ab025ec25)

---

## Architecture

![architecture](https://private-user-images.githubusercontent.com/100662026/267892696-1f7d70c1-95cb-4cc7-8bbe-9db9bc10d322.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTA5OTQzNjEsIm5iZiI6MTc1MDk5NDA2MSwicGF0aCI6Ii8xMDA2NjIwMjYvMjY3ODkyNjk2LTFmN2Q3MGMxLTk1Y2ItNGNjNy04YmJlLTlkYjliYzEwZDMyMi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNjI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDYyN1QwMzE0MjFaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1mZDNmYWNlODE1MThhOWMyOTU3NzlhM2ZhYTViNmYwNTYwMWZkZmY0ZjY4YzIzZWRhNDU1NGVkMjY1OGQxZTdhJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.agsS_cJKpD6kYzxnLpBTWJFfnuxGwKefuZ4w4uyGiqo)

---

## Data Model

![datamodel](https://private-user-images.githubusercontent.com/100662026/267891630-deb31d50-4f01-4c31-8609-afd6c1e3606d.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTA5OTQzNjEsIm5iZiI6MTc1MDk5NDA2MSwicGF0aCI6Ii8xMDA2NjIwMjYvMjY3ODkxNjMwLWRlYjMxZDUwLTRmMDEtNGMzMS04NjA5LWFmZDZjMWUzNjA2ZC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNjI3JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDYyN1QwMzE0MjFaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1hOWI2YmI0NjllMmFlNTYyNDkwZGY4OGEyM2RjMjljMmE4OWYzMzg0Mzg1MGU4MDdlNzEzN2E4YzkxYmExOTJhJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.uBg_zyfljA7jgEuMoeWANha7T7xANAKeWTPWRlzO9K8)

---

## ETL Process

1. **Extraction:**  
   Download and store raw trip data in Google Cloud Storage.

2. **Transformation:**  
   Data cleaning and preprocessing using Python and Mage (data normalization, filtering, enrichment).

3. **Loading:**  
   Load processed data into BigQuery for analytics.

---

## Data Analysis

Key insights uncovered include:

- Peak hours for trips
- Most popular pick-up and drop-off locations
- Average trip distances and fares
- Distribution of payment methods
- Passenger count trends

---

## Visualization

Looker Studio dashboards provide interactive visualizations for:

- Trip distribution by date, time, and location
- Fare analysis and trends
- Passenger and trip distance trends
- Popular locations and payment types

---

## Conclusion

This project demonstrates the use of modern data engineering practices on GCP to analyze Uber trip data. By leveraging Mage for ETL, BigQuery for warehousing, and Looker Studio for visualization, the pipeline enables scalable, efficient analytics and actionable business insights.

---

**Contacts:**  
Email: your.email@example.com  
LinkedIn: linkedin.com/in/yourprofile  
GitHub: github.com/yourusername

---

## Topics

python | bigquery | looker | data-engineering | data-analysis | google-cloud-platform | etl-pipeline

