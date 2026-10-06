# 🎵 Spanish Music Chart Analysis

## 🚀 Live Dashboard

**[Open the Interactive Streamlit
Dashboard](https://spanish-music-analysis-oagkmjgnccrx3yswqe9ds3.streamlit.app/)**

------------------------------------------------------------------------

## 📌 Project Overview

An end-to-end data analytics project focused on the **Spain Top 50 music
chart**, developed during a data analytics internship.

The project analyzes playlist performance, song lifecycle, chart
movement, content type, and playlist rotation to identify patterns in
how tracks enter, grow, peak, mature, and exit the chart.

The project includes both a **Python analysis workflow** and an
interactive **Streamlit dashboard**.

------------------------------------------------------------------------

## 🎯 Business Objective

The analysis was designed to answer questions such as:

-   How long do songs remain on the Top 50 playlist?
-   How quickly do new entries reach their peak position?
-   Which songs and artists demonstrate strong playlist longevity?
-   How frequently does the playlist rotate?
-   What is the daily churn rate?
-   How does explicit content compare with clean content?
-   What proportion of tracks are singles versus album tracks?
-   Which lifecycle stages contribute most to playlist activity?

------------------------------------------------------------------------

## 📊 Key Performance Indicators

The dashboard provides interactive KPIs including:

-   Average days on playlist
-   Median days on playlist
-   Median time-to-peak
-   Average daily churn rate
-   Explicit-content share
-   Singles vs. album-track distribution

------------------------------------------------------------------------

## 📈 Dashboard Features

The Streamlit dashboard provides:

### Playlist Lifecycle Analysis

Tracks are classified into lifecycle stages including:

-   **New Entry**
-   **Growth**
-   **Peak**
-   **Mature**
-   **Decline**

### Churn & Rotation Analysis

Visualizes:

-   Daily playlist entries and exits
-   Monthly churn patterns
-   Playlist rotation trends
-   Track longevity

### Content Analysis

Interactive filters allow analysis by:

-   All content
-   Explicit content
-   Clean content
-   Singles
-   Album tracks

### Interactive Filtering

Users can filter the dashboard by:

-   Date range
-   Lifecycle stage
-   Content type
-   Album type

------------------------------------------------------------------------

## 🛠️ Tech Stack

  Technology         Purpose
  ------------------ ----------------------------------
  Python             Data processing and analysis
  Pandas             Data cleaning and transformation
  NumPy              Numerical analysis
  Plotly             Interactive visualizations
  Streamlit          Interactive dashboard
  Jupyter Notebook   Exploratory analysis

------------------------------------------------------------------------

## 🔄 Data Processing Pipeline

The project follows an end-to-end analytics workflow:

``` text
Raw Chart Data
      ↓
Data Cleaning
      ↓
Date Standardization
      ↓
Duplicate Removal
      ↓
Daily Top 50 Validation
      ↓
Song Lifecycle Classification
      ↓
Time-to-Peak Analysis
      ↓
Churn & Rotation Analysis
      ↓
Interactive Dashboard
```

------------------------------------------------------------------------

## 📁 Project Structure

``` text
spanish-music-analysis/
│
└── spanish_music_analysis/
    ├── Atlantic_Spain.csv
    ├── app.py
    ├── analysis.ipynb
    ├── README.md
    └── requirements.txt
```

### Files

**`app.py`**\
Main Streamlit application containing the interactive dashboard and
analytical logic.

**`analysis.ipynb`**\
Jupyter Notebook containing exploratory data analysis and
data-processing work.

**`Atlantic_Spain.csv`**\
Dataset used for the analysis.

**`requirements.txt`**\
Python dependencies required to run the project.

------------------------------------------------------------------------

## ▶️ Run Locally

### 1. Clone the repository

``` bash
git clone https://github.com/VihaanJ-commits/spanish-music-analysis.git
cd spanish-music-analysis
```

### 2. Install dependencies

``` bash
pip install -r spanish_music_analysis/requirements.txt
```

### 3. Run the Streamlit dashboard

``` bash
streamlit run spanish_music_analysis/app.py
```

The dashboard will open in your browser.

------------------------------------------------------------------------

## 🌐 Live Deployment

The dashboard is deployed using **Streamlit Community Cloud** and is
available here:

**[Launch Spanish Music Analytics Dashboard
→](https://spanish-music-analysis-oagkmjgnccrx3yswqe9ds3.streamlit.app/)**

------------------------------------------------------------------------

## 💡 Skills Demonstrated

This project demonstrates practical experience in:

-   Data cleaning and preprocessing
-   Exploratory data analysis
-   Business-oriented KPI development
-   Time-series analysis
-   Data aggregation
-   Lifecycle analysis
-   Churn analysis
-   Interactive dashboard development
-   Data visualization
-   Python-based analytics
-   Deploying data applications to the web

------------------------------------------------------------------------

## 👤 Author

**Vihaan Jade**

Data Science / Analytics \| Python \| SQL \| Data Visualization \|
Business Analytics

[GitHub](https://github.com/VihaanJ-commits)
