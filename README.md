# 🎵 Spotify Data Analytics ETL  

🚀 This project demonstrates an **Extract, Transform, and Load (ETL)** pipeline using **Spotify data**.  
It extracts raw song/artist data (via the **Spotify API** or dataset), transforms it into a clean and structured format, and loads it into a database for analysis.  

The main objective is to showcase **data engineering**, **pipeline automation**, and **music analytics**.  

---

## Features
- ✅ Extracts data from **Spotify API** (tracks, artists, albums, playlists)  
- ✅ Cleans & transforms data (handling duplicates, formatting dates, durations, popularity scores)  
- ✅ Loads transformed data into a **SQL database**  
- ✅ Enables **analytics & insights** (top artists, popular songs, genre trends, etc.)  

---

## Tech Stack
- **Python** → Pandas, NumPy, Requests, Spotipy  
- **Spotify API** → for raw data  
- **SQL / PostgreSQL / MySQL** → for data storage  
- **Airflow / Prefect (optional)** → for automation  
- **Git & GitHub** → version control  

---

## 🔄 ETL Workflow
```mermaid
graph TD;
    A[Extract] --> B[Transform];
    B --> C[Load];
    C --> D[Analytics];
