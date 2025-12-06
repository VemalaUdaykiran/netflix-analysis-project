🎬 Netflix Data Cleaning & Analysis

This project involves cleaning and analyzing the Netflix Movies & TV Shows dataset.
The goal is to prepare the data for further exploratory analysis and visualization by removing errors, handling missing values, and standardizing the dataset.

📂 Project Files
File	Description
netflix.ipynb	Jupyter Notebook containing all steps for data cleaning and analysis
netflix_titles.csv	Original dataset (if uploaded)
README.md	Project documentation
🧹 Data Cleaning Steps

The notebook performs the following data cleaning operations:

✔ 1. Load and inspect the dataset

Read CSV file using pandas

Display shape, columns, info, and initial rows

✔ 2. Handle missing values

Identify NaN or empty values

Replace missing values in:

Categorical columns → "Unknown"

Numerical columns → mean/median (if any)

Remove rows with excessive missing values

✔ 3. Remove duplicates

Drop duplicate rows

Re-check dataset size after removal

✔ 4. Fix inconsistent formatting

Convert text to lowercase for consistency

Standardize country names, categories, etc.

Strip unwanted spaces

✔ 5. Convert data types

Convert date_added → datetime format

Extract year, month for later analysis

✔ 6. Clean specific columns

Split multiple genres

Clean duration column (remove “min” or “seasons”)

Ensure numeric duration values

📊 Data Analysis Performed

After cleaning, the notebook explores:

Number of movies vs TV shows

Most common genres

Content added over the years

Countries with most content

Ratings distribution

(You can also add plots/screenshots if needed.)

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib / Seaborn

Jupyter Notebook

🚀 How to Run This Project

Clone the repository:

git clone https://github.com/<username>/<repo-name>.git


Install dependencies:

pip install -r requirements.txt


Open the notebook:

jupyter notebook netflix.ipynb

📌 Project Summary

This project transforms a raw Netflix dataset into a clean, consistent, and analysis-ready dataset.
It provides insights into Netflix content trends, genres, ratings, and global distribution.
