# Google-Play-Store-Data-Analysis-using-Pandas
This project analyzes a dataset of Google Play Store applications using Python and Pandas. The workflow includes data cleaning, handling missing values, feature transformation, and performing exploratory data analysis to discover insights about app ratings, reviews, installs, and genres.
Dataset

Dataset: Google Play Store Apps Dataset

File used: google-play-store.csv

Columns include:

App title

Genre

Reviews

Ratings

Score

Price

Release date

Minimum installs

Ratings per day

In-app purchase support

Technologies Used

Python

Pandas

Jupyter Notebook / VS Code

Data Processing Steps

Loaded dataset using Pandas

Converted released column from string to datetime

Handled missing values using median grouped by genre

Replaced missing categorical values in genre

Created cleaned DataFrame for analysis

Analysis Performed

Average ratings per genre

Median ratings per day by genre

Top apps by number of reviews

Paid apps performance analysis

Apps supporting ads and in-app purchases

Total installs by genre

Oldest and newest release dates

Correlation between reviews and ratings

Weighted average rating per genre

Top app per genre based on score-to-rating ratio

Key Insights

Some genres receive significantly higher daily ratings

Paid apps show different rating behavior than free apps

Strong correlation exists between reviews and ratings in some genres

Certain genres dominate in total installs
Installation

To run this project locally:

pip install pandas
How to Run

Download the dataset

Place google-play-store.csv in the project folder

Run the Python script or notebook

Author

Aya Abd El Nasser
Data Engineering Track
