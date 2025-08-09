# COVID-19 India - Data Analysis & Visualizations

**Author:** YASH PAL
**Project type:** Exploratory Data Analysis (EDA) + Visualizations  
**Dataset (example):** Kaggle - COVID-19 India dataset  
**Language / Tools:** Python, Jupyter Notebook, pandas, NumPy, Matplotlib, Seaborn, Plotly (optional), Streamlit/Dash (optional)

---

## Project Overview

This repository contains an end-to-end analysis of COVID-19 data for India. The goals are to:

- Clean and preprocess the dataset.
- Perform exploratory data analysis to reveal temporal trends and state-wise variation.
- Calculate key epidemiological metrics (mortality rate, recovery rate).
- Create static and interactive visualizations to communicate insights.
- Provide reproducible code and instructions to re-run the analysis.

---

## Files in this repo

- `data/` - raw dataset CSV(s) (download from Kaggle and place here)
- `notebooks/covid_analysis.ipynb` - main Jupyter notebook (cleaning, EDA, plots)
- `requirements.txt` - Python dependencies
- `README.md` - this file
- `slides/` - (optional) presentation summarizing insights
- `app/` - (optional) Streamlit / Dash app for interactive exploration
- `outputs/` - exported images / figures / sample CSV outputs

---

## Setup & Requirements

Create a virtual environment (recommended):

```bash
python -m venv venv
source venv/bin/activate      # macOS / Linux
venv\Scripts\activate         # Windows
pip install -r requirements.txt
