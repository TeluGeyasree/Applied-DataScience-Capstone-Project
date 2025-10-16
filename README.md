This project is part of the **IBM Data Science Professional Certificate**.  
It focuses on predicting the success of **SpaceX Falcon 9 first-stage landings** using data collected from SpaceX API and Wikipedia.  
Predicting landing success helps SpaceX estimate the cost of launches since reusing boosters can significantly reduce expenses.

### 👩‍💻 Author: Telu Geyasree
**Date:** October 2025  
**Course:** IBM Data Science Professional Certificate (Coursera)

---

## 🛰️ Project Overview
This project aims to predict the success of **SpaceX Falcon 9 first-stage landings** using historical launch data.  
The prediction helps determine the likelihood of reusability, which is a key factor in reducing SpaceX’s launch costs.

---

## 📊 Objectives
- Collect data from **SpaceX API** and **Wikipedia**
- Perform **data wrangling** and **cleaning**
- Conduct **Exploratory Data Analysis (EDA)** using SQL and Python
- Build **interactive visualizations** using Folium and Plotly Dash
- Develop **Machine Learning models** to predict landing success

---

## 🧰 Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- SQL (SQLite)
- Plotly, Dash, Folium
- BeautifulSoup (Web Scraping)
- SpaceX REST API
- Jupyter Notebook

---

## 📂 Project Structure

| File/Folder | Description |
|--------------|-------------|
| `1_Spacex_API_Data_Collection.ipynb` | Data extraction using SpaceX API |
| `2_Data_Collection_WebScraping.ipynb` | Data extraction from Wikipedia |
| `3_Data_Wrangling.ipynb` | Data cleaning and preparation |
| `4_EDA_with_SQL.ipynb` | EDA using SQL queries |
| `5_EDA_with_Visualization.ipynb` | EDA using visualizations |
| `6_Interactive Visual Analytics with Folium.ipynb` | Folium map and interactive Plotly |
| `7_SpaceX_Machine Learning Prediction.ipynb` | Machine Learning model training |

---

## 📈 Results
- **Best Model:** Decision Tree Classifier  
- **Accuracy:** ~89%  
- **Key Insight:** Payload mass, launch site, and orbit type significantly impact landing success.  

---

## 🌐 Interactive Components
- **Folium Map:** Displays launch sites and success rates.  
- **Plotly Dash App:** Interactive dashboard for exploring launch outcomes.

---

## 🧠 How to Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/IBM-Data-Science-Capstone-SpaceX.git
