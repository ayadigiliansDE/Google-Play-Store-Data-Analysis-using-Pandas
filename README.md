# Google Play Store Data Analysis using Pandas

## Project Overview

This project analyzes a dataset of Google Play Store applications using **Python** and **Pandas**.
The workflow includes **data cleaning, handling missing values, feature transformation, and exploratory data analysis (EDA)** to discover insights about app ratings, reviews, installs, and genres.

---

## Dataset

**Dataset:** Google Play Store Apps Dataset

**File used:**
`google-play-store.csv`

### Columns include:

* App title
* Genre
* Reviews
* Ratings
* Score
* Price
* Release date
* Minimum installs
* Ratings per day
* In-app purchase support

---

## Technologies Used

* Python
* Pandas
* Jupyter Notebook / VS Code

---

## Data Processing Steps

1. Loaded dataset using **Pandas**
2. Converted `released` column from **string** to **datetime**
3. Handled missing values using **median grouped by genre**
4. Replaced missing categorical values in **genre**
5. Created a cleaned DataFrame for further analysis

---

## Analysis Performed

* Average ratings per genre
* Median ratings per day by genre
* Top apps by number of reviews
* Paid apps performance analysis
* Apps supporting ads and in-app purchases
* Total installs by genre
* Oldest and newest release dates
* Correlation between **reviews and ratings**
* Weighted average rating per genre
* Top app per genre based on **score-to-rating ratio**

---

## Key Insights

* Some genres receive significantly higher **daily ratings**
* Paid apps show different rating behavior than free apps
* A noticeable correlation exists between **reviews and ratings**
* Certain genres dominate in **total installs**

---

## Installation

To run this project locally:

```bash
pip install pandas
```

---

## How to Run

1. Download the dataset
2. Place `google-play-store.csv` in the project folder
3. Run the Python script or notebook

---

## Author

**Aya Abd El Nasser**
Data Engineering Track
