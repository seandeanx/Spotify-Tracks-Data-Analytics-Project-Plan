🎵 Spotify Data Analytics Project
📌 Project Overview

This project analyzes a large dataset of Spotify tracks to uncover insights into genre dominance, artist popularity, audio features, mood trends, and track success factors.
The analysis was done using SQL for data wrangling and Tableau for visualization.

The goal: explore what makes tracks popular on Spotify and how different musical attributes influence success.

📂 Dataset

Source: Kaggle Spotify Dataset

Final cleaned dataset: spotify_full_view

Cleaning steps (SQL):

Removed duplicates and missing key values (track_id, track_name, popularity, etc.)

Excluded tracks with 0 popularity

Standardized audio feature values

🔗 SQL Cleaning & Query Script

🛠 Tools Used

SQL (BigQuery / SQLite) – data wrangling & analysis

Tableau Public – visualization & storytelling

GitHub – project documentation

📊 Tableau Dashboard

All visualizations were built in Tableau and published as a story.
👉 View the Interactive Dashboard

🔍 Business Questions & Insights
1. What are the most dominant genres on Spotify based on track count and average popularity?

Pop and hip-hop dominate both in number of tracks and popularity, confirming their global appeal. Emerging genres like EDM also show strong popularity despite fewer tracks.

2. Which artists have consistently high popularity across their discography?

Top artists like Drake and Taylor Swift stand out with high average popularity, reflecting strong fan bases and consistent output.

3. What audio features (danceability, energy, valence, tempo) correlate most with track popularity?

Tracks with higher energy and danceability tend to score higher in popularity. Valence (happiness) plays a moderate role, while acousticness is less significant.

4. Are there differences in popularity between explicit and non-explicit tracks?

Yes — explicit tracks generally have a slight edge in popularity, likely due to alignment with hip-hop/rap where explicit content is common.

5. How do energy and valence shape the emotional appeal of songs?

Popular songs often balance high energy with positive valence, creating upbeat and engaging listening experiences.

6. How do audio features vary across genres?

EDM/House → High energy, high danceability

Acoustic/Folk → High acousticness, lower energy

Rap → High speechiness, moderate energy
Different genres clearly align with distinct audio feature profiles.

7. What audio features distinguish the top 1% most popular tracks?

Compared to all others, the top 1% tracks have:

Higher danceability and energy

Lower acousticness and instrumentalness

Slightly higher valence (positivity)

8. Do tracks with high speechiness (spoken-word/rap) perform better?

High speechiness songs are less popular on average.

Medium to low speechiness levels perform best, suggesting fans prefer a blend of lyrics and melody.

9. What characteristics define the top 1% of tracks?

Top 1% songs typically combine:

High danceability (great for parties/playlists)

High energy (keeps engagement strong)

Moderate valence (positive emotion without being overly cheerful)

10. How do tracks with unusually high speechiness perform compared to average?

While rap-heavy tracks exist, extreme speechiness lowers average popularity. Balance is key — lyrical flow works best when paired with musicality.

📌 Key Takeaways

Popularity is driven by a mix of danceability, energy, and balanced emotional tone.

Genres like Pop and Hip-Hop dominate, but niche genres also shine with distinct features.

The top 1% tracks aren’t random — they share clear audio feature patterns.

For artists: focusing on energetic, danceable tracks with positive vibes increases chances of success.

👤 Author

Sangam Thapa
Business Analytics | Data Analytics & Visualization
