# Netflix Title Analysis Dashboard

### Author: **Gherardo Frusci**  
Higher Diploma in Business Systems Analysis – SETU Waterford (2024/25)
Data Analytics Continuous Assessment – Weight: 70%

---

##  Overview

The **Netflix Title Analysis Dashboard** is a **data-driven project** built to support strategic decisions for the **Director of Marketing Strategies** at Netflix.  
It provides insights on **content trends**, **audience segmentation**, and **production patterns** through an **interactive Excel dashboard**.

The project applies **descriptive and diagnostic analytics** to identify which genres, directors, and countries drive Netflix’s content catalogue, offering actionable recommendations for future strategy.

---

##  Objectives

- Identify **top genres** by audience group.  
- Analyse **most prolific directors** per genre and demographic segment.  
- Discover **top producing countries** across genres.  
- Present findings through an **interactive Excel dashboard** built with Power Query and Pivot Tables.

---

##  Dataset

**Source:** [Kaggle – Netflix Movies and TV Shows Dataset (2025)](https://www.kaggle.com/datasets/anandshaw2001/netflix-movies-and-tv-shows)  
**Total Titles:** 8,809  
**Key Variables:** `listed_in`, `director`, `country`, `rating`, `type`

---

##  Data Preparation & Cleansing

Performed entirely in **Excel Power Query**.

| Variable | Transformation | Purpose |
|-----------|----------------|----------|
| `listed_in`, `director`, `country` | Split into rows | Enable accurate frequency analysis |
| `rating` | Grouped into `Audience_group` | Build audience segmentation |
| `Audience_group` | Kids, Teens, Older Teens, Adults, Unknown | Standardise viewer categories |
| Missing values | Replaced with “Unknown” | Maintain data consistency |
| Duplicates | Removed (Title + Genre + Director + Country) | Ensure data integrity |

---

##  Descriptive Analytics

| Metric | Value |
|---------|--------|
| Total Titles | 8,809 |
| Unique Genres | 42 |
| Unique Directors | 4,530 |
| Audience Distribution | 45.6% Adults • 30.1% Older Teens • 13.0% Teens • 10.3% Kids • 1.0% Unknown |

**Key Findings**
- 78.7% of all Netflix titles belong to **International Movies**, **Dramas**, or **Comedies**.  
- **Adults** and **Older Teens** dominate Netflix’s catalogue.  
- **Top-producing countries:** 🇺🇸 USA • 🇮🇳 India • 🇬🇧 United Kingdom.  
- **Most prolific director (Adults):** *Juan Suter* – 20 titles in *Stand-Up Comedy*.

---

##  Dashboard Design

Built using **Microsoft Excel** with:
- **Power Query** for data transformation  
- **Pivot Tables** for aggregations  
- **Slicers** for audience/genre filters  
- **Bar charts** with cumulative frequency lines  

All charts are **interactive** and automatically update via slicers.  
The dashboard is locked for layout protection, but slicers remain fully usable.  
Hidden worksheets can be made visible by right-clicking the dashboard tab → *Unhide*.

---

##  Predictive Extension

Although focused on descriptive analytics, this project establishes a base for **predictive analysis**, such as:
- Forecasting genre popularity using *trendlines* and *regression (R²)* in Excel.  
- Analysing title growth by genre or audience group using the *Forecast Sheet* feature.  

---

## 🧾 Conclusions & Recommendations

- Expand **children and teen content** to diversify audience engagement.  
- Strengthen collaboration with **high-output directors** in top genres.  
- Explore **emerging production markets** beyond the USA, India, and UK.  

---

##  Video Presentation

🎥 [Watch the full video on OneDrive](https://1drv.ms/v/c/efaf869602287654/EUrzcfCaqOhCu6K4P_Svt3sBCRe3OUAP1fLI2l_Nc67TCg)

---

##  Tools Used

| Tool | Purpose |
|------|----------|
| **Microsoft Excel (Power Query, PivotTables, Slicers, Charts)** | Data transformation and dashboard design |
| **Kaggle Dataset** | Data source |
| **Microsoft Word & PDF** | Analytical report |
| **OneDrive Video** | Project presentation |

---

##  Author

**Gherardo Frusci**  
🎓 Higher Diploma in Business Systems Analysis – SETU Waterford  
💼 Data Analytics | Process Optimisation | Dashboard Design  
📧 data.analysis.gherardo@gmail.com  
🌐 [LinkedIn](https://www.linkedin.com/in/gherardo-frusci-biz/)

---

## Tags

`Excel Dashboard` • `Power Query` • `Data Analytics` • `Kaggle Dataset` • `Descriptive Statistics` • `Business Intelligence` • `SETU`

---

##  License

 **MIT License** 
