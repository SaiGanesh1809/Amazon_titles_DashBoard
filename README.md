# 📊 Prime Video Content Analysis Dashboard

An interactive Power BI dashboard that explores and visualizes key insights from Amazon Prime Video titles between 1981 and 2021.

[🔗 View Dashboard File (.pbix)](https://github.com/SaiGanesh1809/Amazon_titles_DashBoard/blob/main/amazon_prime_titles.pbix)


## 🎯 Objective

- Analyze the evolution and distribution of Amazon Prime Video content.
- Understand trends in genres, ratings, content types, and regional availability.
- Present insights in a visually interactive and user-friendly format.


## 📝 Project Description

This project visualizes Amazon Prime Video metadata using a Power BI dashboard. It presents insights like:

- **Total Titles**: 350  
- **Total Directors**: 271  
- **Total Ratings**: 18  
- **Genres Covered**: 1+  
- **Start Year**: 1981  
- **End Year**: 2021  


## 🛠️ Procedure

### 1. Data Collection
- Dataset sourced from publicly available Prime Video metadata.
- Includes fields like title, genre, rating, release year, type, and country.

### 2. Data Cleaning
- Removed duplicates and null values.
- Standardized ratings and genre entries.
- Extracted year, region, and type from raw fields.

### 3. Data Modeling
- Created relationships and calculated measures in Power BI.
- Aggregated content by genre, type, year, and country.

### 4. Dashboard Design
- Used visual components such as:
  - KPI Cards (Titles, Ratings, Directors, etc.)
  - Bar Charts (Genre, Ratings)
  - Line Chart (Release Year Trends)
  - Donut Chart (TV Shows vs Movies)
  - Map Visual (Geographical Distribution)


## 📸 Dashboard Snapshot

![Dashboard Preview](https://github.com/SaiGanesh1809/Amazon_titles_DashBoard/blob/main/snapshot%20of%20the%20dashboard.png)

> A visual summary of Prime Video’s content trends, including genre distribution, country-wise representation, and release year insights.


## 📈 Key Insights

- **Drama** and **Comedy** are the top genres, with **986** and **536** titles respectively.
- Most titles are rated **13+** and **16+**, suggesting content suitable for teenagers.
- Content production significantly increased after **2015**.
- **TV Shows** dominate the catalog over movies.
- **North America** is the leading content-producing region.


## 🚀 Future Enhancements

- [ ] Add filters by actor, language, and runtime.
- [ ] Integrate IMDb or TMDB ratings using API.
- [ ] Enable drill-down analysis by genre/year.
- [ ] Deploy using Power BI Embedded or Streamlit.


## 📂 Project Structure

```bash
Amazon_titles_DashBoard/
│
├── amazon_prime_titles.pbix              # Power BI dashboard file
├── snapshot of the dashboard.png         # Dashboard image
├── README.md                             # Project documentation

