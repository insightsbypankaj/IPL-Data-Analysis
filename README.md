**IPL Data Analysis (Python)**

This project performs Exploratory Data Analysis (EDA) on IPL datasets using Python.
It analyzes team performance, player statistics, match outcomes, and key insights from ball-by-ball and match-level data.

**Data Sources**

The data is loaded directly from GitHub via working URLs:

deliveries = pd.read_csv("https://raw.githubusercontent.com/Shivaae/IPL-DATA-/main/deliveries.csv")

matches = pd.read_csv("https://raw.githubusercontent.com/Shivaae/IPL-DATA-/main/matches.csv")

**Tech Stack**

      Python: Pandas, NumPy
      Visualization: Matplotlib, Seaborn
      Notebook: Jupyter
      
**Analysis Performed**

  Teams With Most Wins
  
     matches['winner'].value_counts().head(5)

**Top Teams:**
     
Mumbai Indians – 120
Chennai Super Kings – 106
Kolkata Knight Riders – 99
Royal Challengers Bangalore – 91
Kings XI Punjab – 88

      
