# Data Cleaning and EDA

## What this project does
This project takes a raw Netflix Movies and TV Shows dataset (from Kaggle) and:
- Loads it using Pandas
- Identifies missing values, duplicate rows, and incorrect data types
- Cleans the data (fills or drops missing values with justification, removes duplicates, fixes date type)
- Produces summary statistics (Movie vs TV Show counts, release year mean/median, top countries)
- Creates visualizations (histogram of release years, bar chart of content type) using Matplotlib and Seaborn

## Dataset
[Netflix Movies and TV Shows Dataset](https://www.kaggle.com/datasets/sunil123kumar/netflix-movies-and-tv-shows-dataset) from Kaggle.

## How to run this notebook
1. Install Python from [python.org](https://python.org) if you don't already have it.
2. Install the required libraries:
   ```
   pip install pandas matplotlib seaborn jupyter
   ```
3. Download the dataset CSV from the Kaggle link above and place it in this same folder.
4. Launch Jupyter Notebook:
   ```
   jupyter notebook
   ```
5. Open `netflix_analysis.ipynb` and run the cells in order (Shift + Enter).

## Files in this repository
- `netflix_analysis.ipynb` — the main notebook with all code, comments, and charts
- `netflix_titles.csv` — the raw dataset (or a link to it if the file is too large for GitHub)
- `README.md` — this file
