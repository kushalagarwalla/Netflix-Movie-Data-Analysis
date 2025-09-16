# Netflix Data Analytics Project 🎬📊

## 📌 Project Overview
Netflix is widely recognized for leveraging **data science, AI, and ML** to enhance user experience through personalized recommendations and predictive algorithms.  

In this project, we explore a dataset of **9,000+ movies** available on Netflix to answer key business questions. The analysis helps uncover insights about **genres, popularity trends, votes, and yearly production patterns**, enabling data-driven decision-making for improving user engagement and content strategy.

---

## 🎯 Business Problem
Given a dataset of Netflix movies, the objective is to analyze and answer the following questions:

1. **What is the most frequent genre of movies released on Netflix?**  
2. **Which movie has the highest votes (Vote_Average column)?**  
3. **What movie has the highest popularity, and what is its genre?**  
4. **What movie has the lowest popularity, and what is its genre?**  
5. **Which year recorded the highest number of movie releases?**

---

## 📊 KPIs
- **Most Frequent Genre** → Helps identify which type of content dominates Netflix.  
- **Top-Voted Movie** → Captures audience appreciation and quality perception.  
- **Highest & Lowest Popularity Movies** → Provides insights into audience engagement and discoverability.  
- **Most Productive Year** → Highlights the peak periods of Netflix's movie releases.  

---

## 📈 Methodology
1. **Data Cleaning & Preprocessing**  
   - Handled formatting issues.  
   - Dropping columns that are not relevant.
   - Ensured correct data types for date and numeric columns.  

2. **Exploratory Data Analysis (EDA)**  
   - Genre frequency distribution.  
   - Identification of highest/lowest vote averages.  
   - Popularity trends across movies.  
   - Yearly movie release analysis.  

3. **Visualization (using Matplotlib / Seaborn)**  
   - Bar charts for genre frequency.  
   - Line chart for movie releases over years.  
   - Highlight plots for most/least popular movies.  

---

## 🔑 Insights & Business Impact
- The **most frequent genre** provides insights into Netflix’s dominant content strategy.  
- Movies with **highest votes and popularity** highlight what audiences value the most.  
- Identifying the **least popular movies** helps assess gaps in marketing or genre appeal.  
- The **most productive year** shows periods of high content investment.  

---

## 🛠️ Tools & Technologies
- **Python (Pandas, NumPy, Matplotlib, Seaborn)** for analysis & visualization.  
- **Jupyter Notebook** for interactive exploration.   

---

### 📂 Repository Structure  
```plaintext
Netflix-Movie-Data-Analysis/
│-- data/mymoviedb.csv   					   	 # Dataset
│-- Netflix Movie Data Analysis.ipynb            # Jupyter notebook
│-- README.md               				   	 # Project documentation
