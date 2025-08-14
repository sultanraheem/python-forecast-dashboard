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
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Usage
Run the dashboard locally with:

bash
Copy
Edit
streamlit run PeakTew_Forecast_Dashboard.ipynb
Use the sidebar sliders to adjust daily growth rates for Instagram, LinkedIn, and TikTok.

Visualizations update automatically based on the selected growth rates.

Folder Structure
nginx
Copy
Edit
PT Test/
├── PeakTew_Forecast_Dashboard.ipynb  # Jupyter notebook with dashboard code
├── PeakTew_Data_August_1_to_12_2025.csv  # Sample social media data
├── dashboard_snapshot.png  # Exported image of dashboard
├── README.md
License
Later
