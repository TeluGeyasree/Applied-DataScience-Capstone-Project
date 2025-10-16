# 🚀 SpaceX Falcon 9 Landing Prediction – IBM Data Science Capstone

**Author:** Telu Geyasree
**Course:** IBM Data Science Professional Certificate (Coursera)

---

## Project Overview
This project predicts the success of SpaceX Falcon 9 first-stage landings using historical launch data.  
It uses **Python, SQL, visualization, machine learning, and a Plotly Dash dashboard** for interactive exploration.

---

## Project Files

| File/Folder | Description |
|--------------|-------------|
| `1_Spacex_API_Data_Collection.ipynb` | Extracts SpaceX launch data using the API |
| `2_Data_Collection_WebScraping.ipynb` | Scrapes additional launch data from Wikipedia |
| `3_Data_Wrangling.ipynb` | Cleans and prepares the data |
| `4_EDA_with_SQL.ipynb` | EDA using SQL queries |
| `5_EDA_with_Visualization.ipynb` | Data visualization with Matplotlib/Seaborn |
| `6_Interactive Visual Analytics with Folium.ipynb` | Folium map and interactive visuals |
| `7_SpaceX_Machine Learning Prediction.ipynb` | ML model training and evaluation |
| `spacex_dash_app.py` | Plotly Dash interactive dashboard |

---

## How to Run
1. Open Jupyter Notebook to run notebooks `1 → 7` in order.  
2. Optional: Run the dashboard:
```bash
pip install dash plotly pandas
python spacex_dash_app.py
