# 🚦 Smart City Traffic Analytics

A Python-based data analytics project for analyzing traffic patterns, identifying accident hotspots, visualizing accident locations, and demonstrating live accident reporting through interactive dashboards.

## 📌 Project Overview

Smart City Traffic Analytics helps analyze traffic and accident datasets to understand congestion patterns, peak traffic hours, accident-prone locations, and accident severity. It uses data visualization and interactive maps to present useful insights for smart city monitoring.

The project includes a simulated live accident reporting feature for demonstration purposes.

## ✨ Features

- 📊 Traffic pattern and congestion analysis
- 🕒 Peak-hour traffic analysis
- 🚨 Accident hotspot identification
- 🗺️ Interactive accident maps using OpenStreetMap
- 📍 GPS-coordinate-based accident visualization
- 📈 Accident severity monitoring
- ⚡ Simulated live accident reporting dashboard
- 📁 CSV-based dataset processing
- 📉 Charts and analytical summaries

## 🛠️ Technologies Used

- **Python** — Core programming language
- **Pandas** — Data processing and analysis
- **Streamlit** — Interactive web dashboards
- **Folium** — Interactive geographical maps
- **Matplotlib** — Data visualization
- **OpenStreetMap** — Map background and geographical visualization
- **CSV** — Dataset storage

## 📂 Project Structure

```text
SmartCityTrafficAnalytics/
├── data/
│   ├── outputs/
│   ├── accident_map.py
│   ├── accidents.csv
│   ├── analysis.py
│   ├── dashboard.py
│   ├── live_accidents.csv
│   ├── live_dashboard.py
│   └── traffic_data.csv
├── generate_data.py
└── README.md
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/mdisha2005/SmartCityTrafficAnalytics.git
cd SmartCityTrafficAnalytics
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

### 3. Install the required libraries

```bash
python -m pip install pandas folium streamlit matplotlib streamlit-folium
```

## ▶️ How to Run

Run the following commands from the project root directory.

### Generate traffic and accident data

```bash
python generate_data.py
```

### Run traffic analysis

```bash
python data/analysis.py
```

### Display the accident map

```bash
python data/accident_map.py
```

### Launch the traffic analytics dashboard

```bash
python -m streamlit run data/dashboard.py
```

### Launch the live accident reporting dashboard

```bash
python -m streamlit run data/live_dashboard.py
```

After starting a Streamlit dashboard, open the local URL displayed in your terminal, usually `http://localhost:8501`.

## 📊 Expected Results

- Traffic analysis summaries and charts
- Peak-hour and congestion insights
- Accident hotspot maps
- Interactive geographical visualization
- Accident severity summaries
- A simulated accident reporting dashboard

Generated charts and map files are saved in the `data/outputs/` directory when the corresponding scripts create them.

## ⚠️ Important Note

The live accident reporting feature is a simulation. The project does not independently detect actual road accidents or automatically dispatch emergency services. Real-world operation would require validated detection technology, live data sources, and appropriate integrations.

## 🎯 Project Objective

To demonstrate how Python, data analytics, and geographical visualization can help explore traffic conditions and accident patterns for smart city monitoring.

## 👩‍💻 Repository

GitHub: https://github.com/mdisha2005/SmartCityTrafficAnalytics
