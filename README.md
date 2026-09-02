# 🧱 LEGO UNIVERSE

## 50 Years of LEGO Evolution

An interactive Power BI dashboard exploring the evolution of LEGO sets from 1970 to 2022.

The dashboard explores LEGO releases, themes, pieces, pricing, minifigures, and categories across five decades.

---

## 📊 Project Overview

This project was created as a Power BI portfolio project to analyze LEGO sets and present insights through an interactive dashboard.

### Key Questions

* How has the number of LEGO sets changed over time?
* Which LEGO themes have the most sets?
* How has the number of LEGO pieces evolved across decades?
* How has average LEGO set price changed over time?
* Which themes have the highest average number of minifigures?
* How do different LEGO categories compare?

---

## 🛠️ Tools Used

* Microsoft Power BI
* Power Query
* DAX
* GitHub

---

## 📁 Dataset

**Source:** Maven Analytics — LEGO Sets Dataset

The dataset contains 18,459 LEGO sets released between 1970 and 2022.

Key fields include:

* Set ID
* Set Name
* Year
* Theme
* Subtheme
* Theme Group
* Category
* Pieces
* Minifigures
* Minimum Age
* US Retail Price

---

## 🧹 Data Preparation

Data preparation was performed using Power Query.

Main steps included:

* Removing unnecessary URL columns
* Correcting data types
* Preserving relevant missing values
* Creating a Decade column
* Preparing the dataset for analysis

---

## 📐 DAX Measures

Key measures used in the dashboard include:

```DAX
Total Sets = COUNTROWS(lego_sets)

Total Pieces = SUM(lego_sets[pieces])

Average Pieces = AVERAGE(lego_sets[pieces])

Average Price = AVERAGE(lego_sets[US_retailPrice])

Total Minifigs = SUM(lego_sets[minifigs])

Average Minifigs = AVERAGE(lego_sets[minifigs])

Total Themes = DISTINCTCOUNT(lego_sets[theme])
```

---

## 📈 Dashboard Features

The dashboard includes:

* Total Sets KPI
* Total Pieces KPI
* Average Pieces KPI
* Average Price KPI
* LEGO Releases by Year
* Top 10 LEGO Themes
* LEGO Pieces by Decade
* Average Price by Year
* Average Minifigures by Theme
* Category Filter

---

## 🎨 Dashboard Design

The dashboard was designed as a single-page interactive report with a clean and modern layout.

The design focuses on:

* Clear KPI cards
* Easy-to-read charts
* Consistent visual hierarchy
* Interactive filtering
* LEGO-inspired visual storytelling

---

## 📸 Dashboard Preview

![LEGO Universe Dashboard](LEGO_Universe_Dashboard.png)

---

## 📂 Repository Contents

* `LEGO_Universe.pbix` — Power BI dashboard
* `LEGO_Universe_Dashboard.png` — Dashboard preview
* `README.md` — Project documentation

---

## 🚀 How to Use

1. Download the `.pbix` file.
2. Open it using Power BI Desktop.
3. Explore the dashboard and use the category filter to interact with the visuals.



Created as a Power BI portfolio project.
