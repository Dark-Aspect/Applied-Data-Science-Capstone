# 🚀 Applied-Data-Scence-Capstone
This project analyzes SpaceX Falcon 9 launch data to predict whether the first stage of the rocket will successfully land. The analysis includes data collection from the SpaceX REST API, data wrangling, exploratory data analysis, interactive dashboards using Plotly Dash, and predictive modeling using machine learning algorithms

## 📂 Project Structure
- 01_jupyter-labs-spacex-data-collection-api.ipynb – Collects data using SpaceX REST API

- 02_jupyter-labs-webscraping.ipynb – Collects data using web scraping

- 03_labs-jupyter-spacex-Data wrangling.ipynb – Cleans, transforms, and prepares data

- 04_jupyter-labs-eda-sql-coursera_sqllite.ipynb – Analyzes data using SQL queries

- 05_edadataviz.ipynb – Performs Exploratory Data Analysis (EDA)

- 06_lab_jupyter_launch_site_location.ipynb – Creates interactive maps using Folium

- 07_spacex-dash-app.py – Builds an interactive dashboard using Plotly Dash

- 08_SpaceX_Machine Learning Prediction_Part_5.ipynb – Trains and evaluates classification models

## 🧠 Techniques Used
- REST API calls and BeautifulSoup web scraping

- Data cleaning and wrangling with Pandas

- SQL queries via %sql magic in Jupyter

- Visualizations using Seaborn, Matplotlib, Plotly, and Folium

- Supervised machine learning: Logistic Regression, SVM, KNN, Decision Trees

- Hyperparameter tuning with GridSearchCV

- Model evaluation using accuracy and confusion matrices

- Plotly Dash for interactive dashboards

## ✅ Results
- All ML models achieved 83% accuracy on the test set

- Key features like FlightNumber, PayloadMass, Orbit, and LaunchSite impact landing success

- Visualizations and dashboards provided actionable insights for mission planning

## 📊 Business Impact
Understanding the predictors of successful landings can help SpaceX reduce mission costs, optimize launch conditions, and improve decision-making for future launches.

## 🔗 External Links
- [SpaceX API](https://api.spacexdata.com/v4/launches/past)

- [Wikipedia Falcon 9 Launches Page](https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches)

## 📌 Requirements
- Python 3.8+

- Jupyter Notebook

- pandas, numpy, matplotlib, seaborn, plotly, folium

- scikit-learn, beautifulsoup4, requests

- sqlalchemy, ipython-sql
