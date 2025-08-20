# 🎵 Spotify Data Analytics Project  

## 📌 Overview  
This project explores Spotify track data to understand **music trends, listener behavior, and what makes songs successful**.  
Using **SQL for data cleaning** and **Tableau for visualization**, the analysis answers 10 business questions about genres, artists, audio features, and track performance.  

👉 [View the Tableau Dashboard](https://public.tableau.com/views/SpotifyDataAnalyticsTrendsinGenreMoodandTrackSuccess/SpotifyMusicTrendsInsights)  

---

## 📂 Dataset  
- **Source:** Kaggle Spotify Dataset  
- **Final Cleaned Table:** `spotify_full_view`  
- **Cleaning Process (SQL):**
  - Removed duplicates and missing values  
  - Dropped tracks with 0 popularity  
  - Standardized audio features for consistency  

---

## 🛠 Tools & Skills  
- **SQL** – cleaning, wrangling, querying  
- **Tableau Public** – dashboards, storytelling  
- **Data Analytics** – identifying patterns & insights  

---

## ❓ Business Questions & Insights  

### 1. What are the most dominant genres on Spotify?  
- Genres like **pop, hip hop, and EDM** have the **largest track volume**.  
- But **volume ≠ popularity** — some smaller genres actually perform better in popularity.  

### 2. Which genres are most popular on average?  
- **Pop and hip hop** dominate popularity, not just volume.  
- Niche genres with fewer songs sometimes score higher in **average popularity**.  

### 3. Who are the top 10 artists by track count?  
- Artists with the **highest number of songs uploaded** (e.g., prolific EDM creators) flood the platform.  
- Quantity doesn’t always mean success.  

### 4. Who are the top 10 most popular artists?  
- A different picture emerges: **globally known stars** rank higher by **average popularity**, even with fewer songs.  
- Shows the difference between **output vs impact**.  

### 5. How do explicit vs clean tracks perform?  
- **Explicit songs** are highly present in hip hop & rap, but popularity is **balanced**.  
- Clean songs often perform just as well, showing that **lyrics alone don’t decide popularity**.  

### 6. How do audio features (danceability, energy, valence) impact popularity?  
- **Popular tracks** tend to cluster around:  
  - **High danceability** (great for parties)  
  - **Medium-high energy** (not too loud, not too soft)  
  - **Balanced valence** (mix of happy & emotional songs)  

### 7. Do audio features differ by popularity buckets?  
- Yes. **Tracks in the top popularity bucket** consistently have stronger energy/danceability balance.  
- Lower-popularity tracks often score **too extreme** (too slow/low or too noisy/high).  

### 8. What separates the top 1% of songs from the rest?  
- The **top 1% hits** usually:  
  - Have slightly **higher energy & danceability**  
  - Sit in the **sweet spot of valence (emotion)**  
- Small tweaks in features can mean the difference between a regular track and a viral hit.  

### 9. Does speechiness (lyrics-heavy vs instrumental) affect popularity?  
- **Very high speechiness (like podcasts or spoken word)** = low popularity.  
- **Medium speechiness (rap, pop with clear vocals)** = higher popularity.  

### 10. Overall, what drives track success?  
- Success = **right balance of genre, mood, and audio features**.  
- Quantity of songs helps visibility, but **quality (features + artist reputation) drives popularity**.  

---

## 📊 Dashboards  

The Tableau story is split into **three dashboards**:  
1. **Genre & Artist Insights** – genre volume, popularity, top artists.  
2. **Content & Mood Analysis** – explicit vs clean, audio features & popularity.  
3. **Track Success Factors** – top 1% vs others, speechiness impact.  

👉 [Explore on Tableau Public](https://public.tableau.com/views/SpotifyDataAnalyticsTrendsinGenreMoodandTrackSuccess/SpotifyMusicTrendsInsights)  

---

## 📝 Conclusion  
This project shows how **data + music meet**: genres may flood the platform, but **listener choices, mood, and subtle audio features decide success**. For artists and labels, the sweet spot lies in balancing **energy, emotion, and accessibility**.  

---

## ⚖️ License  
This project is shared for **educational purposes only**. Dataset belongs to Spotify/Kaggle.  
