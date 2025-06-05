# Netflix Data Cleaning and Visualization

This project involves analyzing a Netflix dataset by performing data cleaning, basic transformations, and insightful visualizations using Python (Pandas, Matplotlib, Seaborn).

## 📁 Dataset

The dataset contains information about Netflix shows including:
- Show ID, Type (Movie/TV Show), Title
- Director and Cast
- Country of origin
- Date added to Netflix
- Release year, Rating, Duration
- Genre (`listed_in`) and Description

## 🧹 Data Cleaning

Performed the following data cleaning steps:
- Converted `date_added` column to datetime format
- Extracted `year_added` and `month_added` from `date_added`
- Removed duplicate rows
- Handled missing values in critical columns (e.g., `country`, `duration`)
- Ensured correct data types for each column

## 🔁 Transformations

- Added new columns: `year_added`, `month_added` from `date_added`
- Standardized and parsed duration into numeric values if needed

## 📊 Visualizations

1. **Count of Movies vs TV Shows**  
   Bar plot showing how many Movies and TV Shows are in the dataset.

2. **Top 10 Countries by Content Count**  
   Bar chart showing which countries have the most Netflix content.

3. **Monthly Additions Over Time**  
   Line plot showing the number of shows added to Netflix each month.

Additional visualizations can include:
- Most frequent directors or genres
- Distribution of content by rating
- Duration trends for Movies and TV Shows

## 🛠️ Tools Used

- Python 3.11
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

## 📂 Files

- `netflix_data.ipynb`: Jupyter notebook containing code, cleaning steps, and visualizations
