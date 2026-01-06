#  Netflix Exploratory Data Analysis (EDA)

##  Project Overview
This project performs Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset to uncover insights about content distribution, genres, ratings, release trends, and country-wise availability.  
The goal is to understand how Netflix’s content strategy has evolved over time using data analysis and visualization.

---

##  Dataset Information
- Dataset: Netflix Movies and TV Shows
- Source: Kaggle
- Records: Movies & TV Shows available on Netflix
- Key Columns:
  - title
  - type (Movie / TV Show)
  - director
  - cast
  - country
  - date_added
  - release_year
  - rating
  - duration
  - listed_in (genre)
  - description

---

##  Tools & Technologies Used
- Python
- Pandas – Data cleaning & manipulation
- NumPy – Numerical operations
- Matplotlib & Seaborn – Data visualization
- Jupyter Notebook

---

##  Key Analysis Performed
- Data cleaning (handling missing values & duplicates)
- Distribution of Movies vs TV Shows
- Content added over the years
- Most common genres on Netflix
- Country-wise content availability
- Rating-wise content distribution
- Duration analysis of movies and TV shows

---

##  Key Insights
- Netflix has increasingly focused on TV Shows in recent years.
- Majority of content is produced in the United States.
- Drama and International content dominate Netflix’s library.
- A significant rise in content addition is observed after 2015.
- Most movies fall within the 90–120 minutes duration range.

---

##  Project Structure
Netflix/
│
├── data/
│ └── netflix_titles.csv
│
├── notebooks/
│ └── netflix_eda.ipynb
│
├── images/
│ └── charts_and_plots.png
│
├── README.md
└── requirements.txt


---

##  How to Run the Project
1. Clone the repository
   ```bash
   git clone https://github.com/aharnish1/Data-Ananlysis-Projects.git
   
2. Navigate to the project folder
   cd Netflix

3. Install dependencies
   pip install -r requirements.txt

4. Open Jupyter Notebook
   jupyter notebook

5. Open netflix_eda.ipynb and run all cells.

---

## Future Enhancements

- Build an interactive dashboard using Power BI or Tableau

- Perform sentiment analysis on content descriptions

- Apply machine learning for content recommendation

- Forecast Netflix content growth using time-series models

---

## Author

**Aharnish Parekar**
- Aspiring Data Analyst
- Skills: Python | SQL | Power BI | Data Analysis

---

## Acknowledgements

Netflix Movies and TV Shows dataset from Kaggle

Open-source Python libraries
