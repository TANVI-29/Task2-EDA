# Netflix Titles Dataset - Exploratory Data Analysis

This project performs Exploratory Data Analysis (EDA) on the Netflix titles dataset, focusing on understanding content trends, duration, ratings, and release patterns.

## Dataset Overview
- Contains information about movies and TV shows available on Netflix.
- Key columns: `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`.

## EDA Highlights

### Data Preprocessing
- Converted `date_added` to datetime format.
- Dropped rows with null values in selected columns.
- Converted duration (e.g., “2 Seasons” or “90 min”) into a numeric format.

### Univariate Analysis
- Bar plot: Count of Movies vs TV Shows.
- Histogram: Titles released per year.
- Pie chart: Distribution of ratings.

### Bivariate Analysis
- Lineplot: Trend of Movies & TV Shows released over the years.
- Boxplot: Duration by content type.

### Correlation Analysis
- Heatmap of numeric features (e.g., duration vs. release year).

## Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook

## 📌 Conclusion
The EDA provides insights into the growth of Netflix content over the years, content type distribution, and user-preferred ratings.
