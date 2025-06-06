# 🎧 Spotify Power BI Dashboard

A visually engaging Power BI Dashboard built to analyze Spotify data. It includes insights into tracks, artists, genres, and audio features using interactive visuals.

---

## 📊 Features

- **Top Tracks & Artists** by popularity, streams, or followers
- **Genre Distribution** with filtering by year, mood, and tempo
- **Audio Features Analysis**: danceability, energy, acousticness, etc.
- **Monthly Listening Trends**
- **KPIs**:
  - Total Tracks  
  - Total Duration  
  - Average Popularity  
  - Total Artists  

---
## 📁 Data Source

- 📅 Data: **Weekly files from 01 Jan 2025 to 08 May 2025**
- 📌 Source: Manually downloaded from [Spotify Charts](https://spotifycharts.com/)
- 🗂️ Format: `.csv` files for each weekly chart

### Columns:
| Column          | Description                                      |
|------------------|--------------------------------------------------|
| `rank`           | Current position on the chart                    |
| `uri`            | Spotify URI of the track                        |
| `artist_names`   | Artist(s) of the track                          |
| `track_name`     | Title of the track                              |
| `source`         | Chart type (e.g., top200, viral50)             |
| `peak_rank`      | Highest position reached                        |
| `previous_rank`  | Previous week's position                        |
| `weeks_on_chart` | Total weeks the track has appeared              |
| `streams`        | Weekly stream count (for top200 charts only)    |

---
