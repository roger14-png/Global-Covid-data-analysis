COVID-19 Global Data Tracker
📌 Project Overview

The COVID-19 pandemic has been one of the most significant global health crises in recent history.
This project analyzes global COVID-19 data to:

Understand worldwide trends in confirmed cases and deaths

Identify the countries most affected

Compare the progression of the pandemic in the US, India, and Brazil

Visualize pandemic waves using 7-day rolling averages

The analysis follows the Ask – Prepare – Process – Analyze – Share framework from the Google Data Analytics Capstone.

📊 Dataset

We use the COVID-19 cleaned dataset from Kaggle:
👉 Corona Virus Report Dataset (Kaggle)

Key fields:

Date – Reporting date

Country/Region – Country where cases are reported

Confirmed – Cumulative confirmed cases

Deaths – Cumulative deaths

Recovered – Cumulative recovered cases

⚙️ Data Processing

Before analysis, we cleaned and transformed the dataset by:

Renaming columns for consistency

Converting Date column into proper datetime format

Handling missing values

Creating rolling averages for better trend visualization

📈 Analysis & Visualizations

The notebook explores and visualizes:

Global confirmed cases and death trends

Country comparisons (US, India, Brazil)

Pandemic wave detection with rolling averages

Heatmaps and line plots for trend patterns

🚀 Tools & Libraries

This project uses:

Python (Jupyter Notebook)

Pandas – data processing

Matplotlib – plotting

Seaborn – advanced visualizations

📂 Project Structure
covid19-global-analysis.ipynb   # Main notebook with code, analysis, and visualizations
README.md                       # Project documentation (this file)

📢 Stakeholders

Health policy makers

Public health researchers

General public interested in pandemic insights

✅ How to Run

Clone/download this repository

Install dependencies:

pip install pandas matplotlib seaborn


Open the Jupyter notebook:

jupyter notebook covid19-global-analysis.ipynb


Run cells step by step to reproduce results

📌 Future Improvements

Add vaccination and recovery analysis

Include machine learning for forecasting trends

Create an interactive dashboard (Plotly/Dash or Streamlit
