🦠 COVID-19 Global Data Tracker
A data analysis and visualization project that explores global COVID-19 trends using public datasets. This interactive tracker helps users explore patterns in case numbers, deaths, recoveries, and more — with optional date and country filters for tailored insights.
📌 Project Objectives

Load and clean real-world COVID-19 datasets.
Analyze global and country-level COVID-19 trends.
Visualize cases, deaths, recoveries, and testing with Matplotlib, Seaborn, and Plotly.
(Optional) Build an interactive dashboard using Streamlit.

📊 Features

Global summary statistics and time series plots.
Top 10 countries by total cases, deaths, and recoveries.
Country-level filtering and date range analysis.
Correlation heatmaps to explore data relationships.
Optional stretch goal: Interactive dashboard with Streamlit (if enabled).

🧰 Tools & Technologies

Python 3
Jupyter Notebook
Pandas for data manipulation
Matplotlib & Seaborn for static visualizations
Plotly Express for interactive charts
Streamlit (optional) for dashboard interface

📁 Project Structure
COVID-19-Global-Data-Tracker/
├── covid_data_analysis.ipynb # Main Jupyter notebook
├── data/
│   └── [covid_data.csv] # Input data files (if applicable)
├── images/
│   └── [plots.png] # Generated visuals (optional)
├── app.py # Streamlit dashboard (if created)
└── README.md # Project documentation

🚀 Getting Started
1. Clone the repository
git clone https://github.com/Mal-archLumi/COVID-19-Global-Data-Tracker.git
cd COVID-19-Global-Data-Tracker

2. Create a virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install dependencies
pip install -r requirements.txt

Or manually install key libraries:
pip install pandas matplotlib seaborn plotly
# Dashboard
pip install streamlit

4. Launch the Jupyter Notebook
jupyter notebook

Open covid_data_analysis.ipynb and run all cells.
📈 Sample Visualizations

Line chart of daily global COVID-19 cases
Bar chart of top countries by total deaths
Heatmap of correlation between features
Interactive Plotly chart (hover-enabled)

✅ Stretch Goals

Add user input for country and date range.
Create dynamic Plotly visualizations.
Integrate hospitalization/ICU data (if available).
Build interactive dashboard with Streamlit.

👤 Author
Makutu Alvine LumitiBachelor of Science in IT @ Mount Kenya UniversitySoftware Engineer @ PLP AfricaGitHub | LinkedIn | Email
📄 License
This project is licensed under the MIT License.
