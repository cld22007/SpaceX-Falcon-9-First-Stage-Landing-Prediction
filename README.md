# SpaceX Falcon 9 First Stage Landing Prediction

## Project Overview
This project focuses on predicting the success rate of SpaceX Falcon 9 first stage landings using data science techniques. The goal was to determine the factors that influence the success of the first stage landing and build predictive models to forecast landing outcomes.

## Key Objectives
- **Data Collection:** Collected data using SpaceX REST API and web scraping techniques.
- **Data Wrangling:** Cleaned and prepared the data for analysis, including handling missing values and creating a binary outcome variable for landing success.
- **Exploratory Data Analysis (EDA):** Conducted EDA using SQL and data visualization tools like Folium and Plotly Dash to explore launch site success rates and payload mass impact.
- **Predictive Modeling:** Built and evaluated machine learning models (Logistic Regression, SVM, Decision Tree, KNN) to predict landing outcomes.
- **Interactive Visualizations:** Created interactive maps and dashboards to visualize launch site success rates and payload mass impact.

## Tools and Technologies
- **Programming Languages:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Folium, Plotly Dash
- **Data Collection:** SpaceX REST API, Web Scraping with Beautiful Soup
- **Data Analysis:** SQL, Jupyter Notebook
- **Version Control:** Git, GitHub

## Key Findings
- **Launch Site Success Rates:** KSC LC-39A had the highest success rate among all launch sites.
- **Payload Mass Impact:** Higher payload masses were associated with higher success rates.
- **Orbit Types:** Orbits such as ES-L1, GEO, HEO, and SSO had a 100% success rate.
- **Predictive Models:** The Decision Tree model outperformed other models with an accuracy of 87.5%.

## Repository Structure
- **Notebooks:**
  - `01_SpaceX_Data_Collection_API.ipynb`: Data collection using SpaceX API.
  - `02_SpaceX_Web_Scraping.ipynb`: Web scraping for additional data.
  - `03_SpaceX_Data_Wrangling.ipynb`: Data wrangling and preparation.
  - `04_SpaceX_EDA_SQL.ipynb`: Exploratory Data Analysis using SQL.
  - `05_SpaceX_EDA_Data_Visualization.ipynb`: Data visualization using Matplotlib and Seaborn.
  - `06_SpaceX_Interactive_Visual_Analytics_Folium.ipynb`: Interactive map visualizations with Folium.
  - `07_SpaceX_Interactive_Visual_Analytics_Plotly.ipynb`: Interactive dashboards with Plotly Dash.
  - `08_SpaceX_Machine_Learning_Prediction.ipynb`: Predictive modeling and evaluation.
- **Presentation:**
  - `09_SpaceX_Final_Presentation`: Presentation gathering my findings.

- **Data:**
  - `spacex_launch_data.csv`: Cleaned dataset used for analysis and modeling.
