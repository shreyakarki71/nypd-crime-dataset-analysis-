# NYPD Crime Dataset Analysis (2013–2023)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shreyakarki71/nypd-crime-dataset-analysis-/blob/main/Final_Python_Group_assignment.ipynb)

This project analyzes over 8 million NYC crime records from the [NYPD Complaint Data (Kaggle)](YOUR_KAGGLE_LINK), focusing on trends from 2013 to 2023.  
It covers:
- Data cleaning & preprocessing
- Statistical summaries & visualizations
- Predictive modeling using XGBoost

## Dataset Source  
Dataset used in this project:  
[NYPD Complaint Data Historic – Kaggle](https://www.kaggle.com/datasets/aniket0712/nypd-complaint-data-historic) :contentReference[oaicite:2]{index=2}

## Key Findings
- **Crime peaked** between 3–5 PM, especially on Fridays.  
- **Significant drop in 2020**, likely due to COVID-19.  
- **Brooklyn & Manhattan** had the highest incidents; residential areas were most common.  
- **Ages 25–44** made up most victims & suspects; female victims were disproportionately affected.  
- **Over 95% of crimes were completed**; attempted crimes fell from 1.95% in 2013 to 1.44% in 2023.  
- **XGBoost model accuracy:** 67% overall (F1: 0.63) — strong for frequent crime types like *Harassment 2* and *Petit Larceny*.  


## Tools & Libraries
- **Python:** Pandas, Matplotlib, Seaborn, Folium  
- **Machine Learning:** XGBoost, Scikit-learn  
- **Environment:** Google Colab  


## 📂 Additional Files
- [Final Project Summary (PDF)](Final%20Project%20Summary.pdf)  
- [Crime Presentation (PDF)](crime%20presentation.pdf)



## How to Run
1. Click **Open in Colab** above — no installation needed.  
2. Or download the `.ipynb` file and run locally with Jupyter Notebook.


## Team Members
- **Ali Adnan:** Data cleaning, Visualization, Predictive model  
- **Shreya Karki:** Kaggle API, Data Cleaning, Statistics, Visualization  
- **Ayushman Shrestha:** Statistics, Visualization  
- **Hongyan Zhang:** Statistics, Visualization  

## References
- [Pandas Documentation](https://pandas.pydata.org/docs/)  
- [Folium Heatmaps](https://python-visualization.github.io/folium/)  
- [NYC Open Data Portal](https://opendata.cityofnewyork.us/)  
- [XGBoost Documentation](https://xgboost.readthedocs.io/)  



