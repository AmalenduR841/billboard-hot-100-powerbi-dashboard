# 🎵 Billboard Hot 100 — Power BI Dashboard

![Billboard Dashboard]<img width="1920" height="998" alt="github readme" src="https://github.com/user-attachments/assets/8eb264f4-14dd-4d39-bdbd-6335188fece8" />


## 📊 Overview

An interactive 6-page Power BI dashboard analyzing the complete 
history of the Billboard Hot 100 chart from 1958 to 2026 — 
covering 68 years, 32,415 unique songs, and 11,195 artists.

This project transforms raw weekly chart data into meaningful 
visual stories about music trends, artist dominance, collaboration 
patterns, and cultural revivals.

---

## 🔗 Live Dashboard
👉 [View Interactive Dashboard](https://app.powerbi.com/links/LUHLhecyXS?ctid=e3c2aae2-b62f-4a04-988c-92357cbcc60c&pbi_source=linkShare)

---

## 📁 Dashboard Pages

| Page | Title | Description |
|------|-------|-------------|
| 1 | Hall of Fame | All-time records — longest songs, most charted artists |
| 2 | Decade by Decade | How music changed across each decade |
| 3 | Artist Deep Dive | Search any artist — career timeline & best songs |
| 4 | Top Songs Explorer | Top songs by year or decade with chart journeys |
| 5 | Trends & Insights | Streaming effect, collab explosion, seasonal patterns |
| 6 | Revivals & Comebacks | Songs that returned, one hit wonders, Christmas classics |

---

## 🔍 Key Insights

- 📈 Songs last **3x longer** on chart since streaming began in 2014
- 👑 **Taylor Swift** leads all artists with 1,736 chart appearances
- 🤝 Collaborations grew from **9% to 35%** between 1980s and 2010s
- 🎄 **3 of the top 10** comeback songs are Christmas classics
- 💫 **7,457 artists** had exactly one hit and never charted again
- 🎵 Only **1,162 songs** have ever reached #1 in 68 years
- ⚡ **Lose Control** by Missy Elliott holds the record — 112 weeks

---

## 📂 Data Source

| Detail | Info |
|--------|------|
| Source | GitHub — mhollingshead/billboard-hot-100 |
| Format | JSON |
| Update | Weekly (every Friday) |
| URL | https://raw.githubusercontent.com/mhollingshead/billboard-hot-100/main/all.json |

The dashboard connects directly to this URL and refreshes 
automatically every Wednesday via Power BI Service scheduled refresh.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Power BI Desktop | Dashboard development |
| Power BI Service | Publishing & scheduled refresh |
| Power Query (M) | Data transformation & cleaning |
| DAX | Calculated columns & measures |
| JSON | Source data format |

---

## 📐 Technical Details

### Calculated Columns (14)
Song Artist Key, Position Change, Is Number One, Is New Entry, 
Trend Direction, Decade, Year, Month Name, Month Number, 
Is Collab, Collab Label, Weeks Tier, First Chart Date, Is Revival

### DAX Measures (21)
Total Chart Entries, Unique Songs, Unique Artists, Unique Number 
One Songs, Longest Run Ever, Avg Weeks on Chart, Artist Best Peak,
Artist Chart Appearances, Artist Total Weeks, Weeks to Peak, 
Avg Weeks to Peak, Total Collabs, Collab %, Total New Entries,
Number One Changes, Total Revivals, Revival %, One Hit Wonders,
Artist Selected Message, Latest Data Date, Last Refreshed

---

## 📚 Documentation

Full project documentation is available in the folder:

- **Dashboard Documentation** — complete project walkthrough from 
data extraction to publishing
- **Technical Reference** — definitions of every calculated column, 
DAX measure, and visual used

---

## 🚀 How to Use

1. Download the `.pbix` file from the `/pbix` folder
2. Open with Power BI Desktop (free download from Microsoft)
3. The data connects automatically to the GitHub JSON source
4. Click **Refresh** to load the latest Billboard data
5. Explore all 6 pages using the navigation bar

---

## 📊 Data Model Stats

| Metric | Value |
|--------|-------|
| Total Rows | ~352,987 |
| Unique Songs | 32,415 |
| Unique Artists | 11,195 |
| Date Range | 1958 — 2026 |
| Pages | 6 |
| Calculated Columns | 14 |
| DAX Measures | 21 |

---

## ⚠️ Usage & Rights

This project and all its contents — including the dashboard design, 
DAX measures, calculated columns, documentation, and insights — 
are the intellectual property of the author.

- ✅ Viewing and referencing this project is welcome
- ✅ Using it as inspiration for your own learning is encouraged
- ❌ Reproducing, copying, or redistributing any part without 
explicit written permission is not permitted
- ❌ Commercial use of any kind is strictly prohibited

For permissions or collaborations please connect via LinkedIn.

---

## 🙏 Acknowledgements
- Data source: [mhollingshead/billboard-hot-100](https://github.com/mhollingshead/billboard-hot-100)
- Built with Microsoft Power BI

---

⭐ If you found this useful, please give it a star!
