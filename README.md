# 📺 Streaming Platforms vs Traditional TV — Data Analysis

A comparative exploratory data analysis (EDA) of Netflix's OTT streaming performance against traditional broadcast television, examining how viewer behaviour and content popularity differ across the two mediums.

## 📁 Repository Structure

OTT-vs-Streaming-data-analysis/
│
├── StreamingPlatformsVsTraditionalTV.ipynb   # Main analysis notebook
├── netflix daily top 10.csv                  # Netflix Daily Top 10 dataset
└── traditional_tv_data_cleaned.csv           # Cleaned traditional TV ratings dataset

## 📊 Datasets

### 1. `netflix daily top 10.csv`
Tracks Netflix's daily top 10 most-watched titles. Typical fields include:

| Column | Description |
|---|---|
| `As of Date` | Date of the ranking snapshot |
| `Rank` | Position in the daily top 10 (1–10) |
| `Show Title` | Name of the film or TV series |
| `Type` | Content type — `Film` or `TV` |
| `Netflix Exclusive` | Whether the title is a Netflix original |
| `Netflix Release Date` | Date the title was made available on Netflix |
| `Days In Top 10` | Cumulative days the title has spent in the top 10 |
| `Viewership Score` | Relative viewership score assigned by Netflix |

### 2. `traditional_tv_data_cleaned.csv`
Contains broadcast/cable TV ratings data (~750 records). Typical fields include viewership numbers, ratings, network/channel names, programme titles, air dates, and time slots. This dataset has already been pre-processed and cleaned.

---

## 🔍 Analysis Overview

The notebook `StreamingPlatformsVsTraditionalTV.ipynb` covers:

- **Data Loading & Inspection** — Shape, dtypes, null-value checks, and summary statistics for both datasets.
- **Exploratory Data Analysis (EDA)** — Distribution plots, rankings, content-type breakdowns, and temporal trends.
- **Netflix-Specific Analysis**
  - Top titles by cumulative viewership score
  - Film vs TV show split in the top 10
  - How long titles stay in the top 10 (longevity analysis)
  - Exclusives vs licensed content performance
- **Traditional TV Analysis**
  - Viewership trends across networks and time slots
  - Top-performing programmes and genres
  - Rating/share distributions
- **Comparative Insights** — Side-by-side visualisations and discussion of how content consumption patterns diverge between OTT streaming and linear broadcast TV.

---

## 🛠️ Tech Stack

- **Python 3**
- **Jupyter Notebook**
- `pandas` — data manipulation
- `numpy` — numerical operations
- `matplotlib` / `seaborn` — data visualisation


## 💡 Key Questions Explored

- How does Netflix streaming viewership compare to traditional TV ratings?
- Which content types (films vs series) dominate on each platform?
- How have viewership habits shifted toward on-demand consumption?
- What does title longevity look like on Netflix vs a weekly broadcast schedule?

---

## 📌 Notes

- The traditional TV dataset has been pre-cleaned (hence the `_cleaned` suffix); no additional preprocessing is required before running the notebook.
- The Netflix Daily Top 10 data is sourced from Netflix's public ranking tracker.

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to change.

---

## 👤 Author

**Abd-Sam** — [GitHub Profile](https://github.com/Abd-Sam)
