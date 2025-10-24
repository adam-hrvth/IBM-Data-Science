IBM Data Science Capstone: SpaceX Falcon 9 Landing Predictor
Overview
This repository hosts the IBM Data Science Professional Certificate Capstone Project. It analyzes SpaceX Falcon 9 first-stage landing data to build a predictive model for success, supporting a startup's bidding strategy.
Project Structure

1_API_SpaceX.ipynb: Fetches launch data via SpaceX REST API.
2_Web_Scraping.ipynb: Scrapes Wikipedia for mission outcomes.
3_Data_Wrangling.ipynb: Cleans and merges datasets.
4_EDA_Visualization.ipynb: Plots for exploratory insights.
5_SQL_EDA.ipynb: SQL queries on SQLite DB.
6_Folium_Map.ipynb: Interactive global launch map.
7_Dash_App.py: Plotly Dash dashboard for analytics.
8_ML_Prediction.ipynb: Classification models (RF best @92%).

Setup

Clone: git clone https://github.com/adam-hrvth/IBM-Data-Science.git
Install: pip install -r requirements.txt (pandas, requests, folium, plotly, scikit-learn, sqlite3)
Run notebooks sequentially.

Key Findings

Success ~70%, improving yearly.
Optimal: <4000kg payloads from KSC.
Model enables accurate predictions.

License
MIT. For educational use.