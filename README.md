# Spotify 2023 Top Songs Analysis 🎵📊

This project focuses on cleaning and analyzing Spotify's most streamed songs of 2023 to uncover trends in artist popularity, platform dominance, and seasonal streaming patterns. The dataset was cleaned using industry-standard data preprocessing techniques, then visualized in Power BI to support meaningful insights.

---

## 📁 Dataset Cleaning & Data Modeling

### 1. Missing Values (Replaced with Mean) — `in_shazam_charts` Column

**Explanation:**  
The `in_shazam_charts` column contained missing values that could distort insights, as Shazam plays a critical role in music discovery. I calculated the column's mean and used it to replace the missing values. This ensures the data remains consistent while preserving the analytical integrity of how frequently songs are discovered on Shazam.

---

### 2. Data Outliers (Replaced with Mean) — `streams` Column  

**Explanation:**  
The `streams` column is central to identifying popular tracks. I identified extreme outliers that skewed the distribution. To normalize the data, I replaced these outlier values with the column mean. This allowed for fairer comparisons of artist and song popularity.

---

### 3. Data Typos (Corrected Special Characters) — `artist(s)_name` Column  

**Explanation:**  
The `artist(s)_name` column included incorrect characters (e.g., missing tildes or accents) due to formatting issues when importing to Power BI. I manually corrected these entries to ensure accurate artist grouping and cleaner visualizations.

---

## 📊 Visualizations & Insights

### 🎤 1. Top Artists by Stream Count
**Insight:**  
The Weeknd was the most streamed artist of 2023 with **~14 billion streams**.  
Danceability correlates with stream count — artists with higher danceability scores (e.g., The Weeknd, Bad Bunny) saw higher streaming success. This supports research such as Laura Gao’s *“The Evolution of Dance Music”*, which highlights that upbeat and energetic music tends to perform better.

---

### 📈 2. Streaming Platform Distribution
**Insight:**  
Spotify accounts for **90%** of charting songs in the dataset, followed by Apple Music, Deezer, and Shazam combined (10%).  
This aligns with external industry rankings (e.g., CNET) that recognize Spotify as the leading music streaming platform for both content and features.

---

### 📅 3. Stream Count vs. Release Month
**Insight:**  
A spike in music **streams in January** coincides with **high release volumes in December**.  
This indicates that end-of-year releases carry over into the following year’s stream counts — a trend supported by Nadav Peleg’s insights on holiday release strategies. The lowest release month was January, yet it saw the highest stream count, reinforcing the lag effect between release and consumption.

---

## 🧠 Summary of Key Findings
- **The Weeknd** dominates Spotify’s 2023 streams.
- **Danceability** strongly influences popularity.
- **Spotify** is the top charting platform by a wide margin.
- **Release timing** affects stream volume — December releases surge in January.
- **Clean data** improves result reliability and business relevance.

---

## 🛠️ Tools & Technologies Used
- **Power BI** – Data Modeling & Visualization  
- **Excel** – Data Cleaning (Missing Values, Outliers, Typos)  
- **Data Source:** Spotify Top Songs 2023 Dataset (Manually Collected & Cleaned)

---

## 📄 Project Files
- `/screenshots/` – Contains pre/post cleaning images for visual reference  
- `Spotify_Top_Songs_2023.pbix` – Power BI project file  
- `README.md` – This file  
- `spotify_cleaned_dataset.xlsx` – Cleaned and preprocessed dataset

---

## 📬 Contact
Created by Jessie Estrada  
📧 jestrada3745@gmail.com | [GitHub](https://github.com/JessieEstrada) | [LinkedIn](https://linkedin.com/in/jessieestrada)

