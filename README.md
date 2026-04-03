# EDA-project-netflix
#  Netflix Exploratory Data Analysis (EDA) Project

##  Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset to uncover patterns, trends, and insights related to content distribution, genres, ratings, and growth over time.

The analysis was conducted using Python and visualized through various charts to support data-driven insights.

---

##  Objectives
- Understand the distribution of Movies vs TV Shows
- Analyze content trends over time
- Explore popular genres, ratings, and countries
- Perform statistical analysis to validate patterns
- Generate meaningful business recommendations

---

##  Tools & Technologies
- Python
- Jupyter Notebook
- pandas, numpy
- matplotlib, seaborn
- Git & GitHub

---

##  Dataset
- Source: Netflix Movies & TV Shows Dataset (Kaggle)
- Rows: 8000+
- Columns: 12+
- Includes numerical, categorical, and date features

---

##  Data Cleaning & Preprocessing
- Removed duplicate records
- Converted `date_added` to datetime format
- Handled missing values:
  - `director` → filled with 'Unknown'
  - `cast` → filled with 'Not Available'
  - `country`, `rating` → filled with mode
  - `date_added` → removed missing rows
- Extracted numeric values from `duration`
- Processed `listed_in` by splitting and expanding multiple genres

---

##  Feature Engineering
- Created new features:
  - `year_added`, `month_added`
  - `content_age`
  - `is_movie`
  - `is_recent`
  - `duration_category`

These features improved analysis and helped extract deeper insights.

---

## Exploratory Data Analysis

### 🔹 Univariate Analysis
- Distribution of content type
- Rating distribution
- Release year trends

### 🔹 Bivariate Analysis
- Type vs Rating
- Rating vs Release Year
- Type vs Duration

### 🔹 Time-Based Analysis
- Content added over years
- Trend analysis showing growth and decline

### 🔹 Statistical Analysis
- Chi-square test → examined association between content type and rating
- t-test → compared average duration between Movies and TV Shows
- ANOVA → tested differences in release year across rating categories

---

##  Key Insights
- Movies dominate the platform compared to TV Shows
- Most content is from recent years (post-2015)
- International Movies, Drama, and Comedy are top genres
- Mature content (TV-MA, TV-14) is more common in recent years
- Content additions peaked around 2019 and declined afterward
- Weak negative correlation between release year and duration

---

##  Recommendations
- Focus on producing and adding more recent content
- Strengthen the movie library while increasing TV Shows
- Invest in popular genres like International Movies, Drama, and Comedy
- Continue producing mature content for target audiences
- Maintain a balance in content duration
- Expand globally to improve diversity
- Ensure consistent content addition over time
- Enhance recommendation systems for personalization
- Invest in original content to stand out

---

##  Conclusion
This project demonstrates how data analysis can be used to uncover meaningful insights and support strategic decisions. By analyzing Netflix content data, we identified trends in content growth, audience preferences, and distribution patterns.

---

##  How to Run
1. Clone the repository
2. Install required libraries:
