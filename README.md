# Chicago Taxi Market Analysis 🚕 📊

## Project Overview
This project explores the Chicago taxi industry by analyzing big data from November 2017. The goal is to identify market leaders, understand geographic demand concentration, and statistically prove how external factors —like weather— affect operational efficiency.

The project bridges the gap between **SQL data extraction** and **Python-based statistical analysis**.

## 🚀 Key Features
- **Exploratory Data Analysis (EDA):** Visualizing market share and destination hotspots using `Seaborn` and `Matplotlib`.
- **Hypothesis Testing:** Implementing **Levene’s Test** and **Independent T-tests** to quantify the impact of weather on trip durations.
- **Data Cleaning:** Handling duplicates and ensuring data integrity for robust statistical results.

## 📈 Main Findings
1. **Market Concentration:** A single company (**Flash Cab**) dominates nearly 20% of the top-tier market share.
2. **The "Golden Triangle":** Over 20,000 daily trips are concentrated in just two neighborhoods: **The Loop** and **River North**.
3. **Weather Impact:** Rain significantly increases travel time to O'Hare Airport on Saturdays ($p < 0.05$), suggesting a need for weather-contingent logistics.

## 🛠️ Tech Stack
- **Languages:** Python (Pandas, Numpy, Scipy), SQL.
- **Visualization:** Seaborn, Matplotlib.
- **Environment:** Jupyter Notebook / Anaconda.

## 📂 Project Structure
- `project.ipynb`: Main analysis notebook containing code and interpretations.
- `datasets/`: Folder containing the three CSV results from SQL queries.
- `requirements.txt`: List of dependencies.

## ⚙️ How to Run
1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt