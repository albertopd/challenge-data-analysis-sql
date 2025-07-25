# Data Analysis with SQL on KBO database

[![Python](https://img.shields.io/badge/Python-3.13%2B-blue?logo=python)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![SQLite](https://img.shields.io/badge/Database-SQLite-lightgrey?logo=sqlite)](https://www.sqlite.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Plotting-11557C?logo=plotly&logoColor=white)](https://matplotlib.org/)

---

This repository contains Jupyter Notebooks for performing data analysis using SQL on a KBO (Kruispuntbank van Ondernemingen) database. The notebooks connect to the database, execute queries, and analyze the data.

---

## 🤔 Questions Answered

### General

- Which percentage of companies are under which juridical situation?
- Which percentage of companies are under which juridical form?
- What is the distribution of company statuses?
- What is the average company age by sector?
- What is the company creation trend over the years?
- What is the distribution of companies per municipality?
- What are the year-over-year growth trends by sector?
- What are the seasonal patterns for company creation?
- Which are the top 3 rising sectors per region in the last 5 years?

### Business Creation Trends During the COVID-19 Pandemic

- How Many Companies Were Created During the Pandemic?
- What Was the Distribution of Company Creations by Region?
- Where Were Companies Created The Most?
- Which Sectors Boomed During the Pandemic?

---

## 📦 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/albertopd/challenge-data-analysis-sql.git
cd challenge-data-analysis-sql
pip install -r requirements.txt
```

Download the kbo_database.db file from [Google Drive](https://drive.google.com/file/d/1QWmV2YQ9dBx3J6asLEb3e_lpjDIrUb-f) and place it in the data folder.

---

## 🧪 Usage

### For General Data Analysis:

Open the Jupyter Notebook `general-data-analysis` and run the cells to perform data analysis:

```bash
jupyter notebook general-data-analysis.ipynb
```

### For COVID Data Analysis:

Open the Jupyter Notebook `covid-data-analysis` and run the cells to perform data analysis:
```bash
jupyter notebook covid-data-analysis.ipynb
```

---

## 🧾 Requirements

Main dependencies include:

- python 3.13+
- sqlite3
- jupyter
- pandas
- matplotlib

All required packages are listed in [`requirements.txt`](requirements.txt).

---

## 👥 Contributors

- [Alberto](https://github.com/albertopd)