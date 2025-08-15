# 🎬 Netflix Content Analysis Dashboard

An interactive Tableau dashboard analyzing *Netflix’s global content library* by type, genre, country, release year, and ratings.  
The analysis reveals content trends, geographic spread, and audience targeting insights.

---

## 🖼 Dashboard Preview
![Netflix Dashboard](netflix_dashboard.png)

---

## 📌 Project Overview
This dashboard uses Netflix metadata to visualize:
- Content type distribution (*Movies* vs *TV Shows*)
- Genre popularity
- Country-wise availability
- Growth trends over the years
- Audience rating patterns

Built in *Tableau* using data from the official Netflix dataset.

---

## 📊 Key Insights

### 1) Content Type Distribution
- *Movies*: 6,130 titles  
- *TV Shows*: 2,676 titles  

### 2) Geographic Spread
- *United States* has the largest library (~2,818 titles), followed by *India, **UK, and **Canada*.  
- Availability varies by country due to licensing.

### 3) Top Genres
- *Documentaries* – 359 titles  
- *Dramas, International Movies* – 362 titles  
- *Stand-Up Comedy* – 334 titles  
- *Children & Family Movies* are frequent, indicating strong family content.

### 4) Content Growth Over Time
- Sharp rise between *2015–2019* for both Movies & TV Shows.  
- Slight decline in recent years — possibly market saturation or quality focus.

### 5) Ratings Distribution
- *TV-MA*: 3,207 titles (Mature Audience)  
- *TV-14*: 2,159 titles (Teens)  
- *TV-PG*: 683 titles (Parental Guidance)  
➡ Skewed toward *adult and teen audiences*.

---

## 🗺 Dashboard Features
- *Filters* for content type, title, country, and genre
- *Global heatmap* of titles by country
- *Top genres bar chart*
- *Movies vs TV Shows bubble chart*
- *Yearly trend line chart*
- *Ratings distribution chart*

---

## 📂 Files in This Repository
- Netflix_Dashboard.twbx → Tableau packaged workbook  
- netflix_titles.csv → Dataset used  
- assets/netflix_dashboard.png → Dashboard preview image  
- README.md → Documentation (this file)

---

## 🚀 How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/netflix-content-analysis.git 
