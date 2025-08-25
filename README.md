# Python Social Media Forecast Dashboard

This repository contains a **Python-based dashboard** for visualizing and forecasting social media follower growth across Instagram, LinkedIn, and TikTok.

<img width="5370" height="3571" alt="dashboard_snapshot" src="https://github.com/user-attachments/assets/446b97d4-a230-49ca-8aa5-f10072c63415" />

---

## Features

- **Interactive Forecasting**: Scenario-based growth projections (best, middle, worst).  
- **Visualizations**:  
  - Line chart with shaded area between worst and best forecasts  
  - Bar chart of followers after 180 days by scenario  
  - Numeric summary table  
  - Daily growth rate comparison  
- **Customizable Growth Rates**: Adjust daily growth rates for each platform via sliders.  
- **Aesthetic Colour Palette**: Dashboard uses a visually pleasing purple/pink theme.

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/sultanraheem/peaktew-forecast-dashboard.git
cd peaktew-forecast-dashboard
```

## Usage

streamlit run PeakTew_Forecast_Dashboard.ipynb

Note: Use the sidebar sliders to adjust daily growth rates for Instagram, LinkedIn, and TikTok. Visualizations update automatically based on the selected growth rates.

## Folder Structure

- `PeakTew_Forecast_Dashboard.ipynb`: Jupyter notebook with dashboard code  
- `PeakTew_Data_August_1_to_12_2025.csv`: Sample social media data  
- `dashboard_snapshot.png`: Exported image of dashboard  
- `README.md`: Project README

## Findings

### Gain / Loss

TikTok had the highest daily growth rate among the platforms, set at 0.3%. That’s more than double Instagram’s rate and triple LinkedIn’s.

Instagram experienced follower losses on multiple days, including a sharp drop of 28 followers on August 13, 2025, its worst day in the dataset.

LinkedIn showed consistent growth, peaking with a 69-follower gain on August 11, 2025, and maintaining a steady upward trajectory.

### Forecasting Scenarios

The dashboard models three scenarios, best, middle, and worst, for each platform over 180 days.

Even in the worst-case scenario, TikTok is projected to grow, thanks to its strong initial momentum and higher growth rate.

The best-case forecast suggests that Instagram could reach over 2,400 followers, LinkedIn could reach over 16,800, and TikTok could reach over 1,000 by early 2026.

### Visualization Highlights

The dashboard features a shaded line chart illustrating the range between the worst and best forecasts, providing a visual representation of uncertainty.

A bar chart compares final follower counts across scenarios, making it easy to see which platform has the most optimistic outlook.
