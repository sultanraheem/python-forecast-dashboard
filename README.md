# PeakTew Social Media Forecast Dashboard

This repository contains a **Python-based dashboard** for visualizing and forecasting social media follower growth for PeakTew across Instagram, LinkedIn, and TikTok.

---

## Features

- **Interactive Forecasting**: Scenario-based growth projections (best, middle, worst).  
- **Visualizations**:  
  - Line chart with shaded area between worst and best forecasts  
  - Bar chart of followers after 180 days by scenario  
  - Numeric summary table  
  - Daily growth rate comparison  
- **Customizable Growth Rates**: Adjust daily growth rates for each platform via sliders.  
- **Aesthetic Color Palette**: Dashboard uses a visually pleasing purple/pink theme.

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/sultanraheem/peaktew-forecast-dashboard.git
cd peaktew-forecast-dashboard

2. Install dependencies

pip install -r requirements.txt

3. Usage

streamlit run PeakTew_Forecast_Dashboard.ipynb

FOLDER STRUCTURE

PT Test/
├── PeakTew_Forecast_Dashboard.ipynb  # Jupyter notebook with dashboard code
├── PeakTew_Data_August_1_to_12_2025.csv  # Sample social media data
├── dashboard_snapshot.png  # Exported image of dashboard
├── README.md
