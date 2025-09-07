# 🚕 Chicago Rideshare Analysis  
*Data-driven recommendations for Zuber’s rideshare market strategy in Chicago.*  

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)  
![pandas](https://img.shields.io/badge/pandas-EDA-green?logo=pandas)  
![numpy](https://img.shields.io/badge/numpy-Numerical-blue?logo=numpy)  
![matplotlib](https://img.shields.io/badge/matplotlib-Visualization-orange)  
![plotly](https://img.shields.io/badge/plotly-Graphing-blue?logo=plotly)  
![scipy](https://img.shields.io/badge/scipy-Stats-lightblue?logo=scipy)  
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)  
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)  

---

## 📌 Overview  
Zuber, a rideshare company, is looking to strengthen its presence in the Chicago market and expand to additional metropolitan areas. This project analyzes competitor trip data, drop-off locations, and weather conditions to provide strategic recommendations for neighborhood targeting, competitive positioning, and pricing strategy.  

---

## 📊 Dataset  
- **Sources:**  
  - Chicago taxi trip drop-off data  
  - Competitor company trip counts  
  - Weather data for November 2017 (rain vs. non-rain days)  
- **Data Preparation:**  
  - Cleaned and standardized column names  
  - Addressed duplicates in hourly ride data (kept to preserve accuracy)  
  - Validated datatypes and ensured datasets were analysis-ready  

---

## ⚙️ Methods & Tools  
- **Libraries:** pandas, matplotlib, scipy  
- **Techniques:**  
  - Exploratory data analysis (EDA) of neighborhoods and companies  
  - Pareto analysis of competitor rides  
  - Hypothesis testing (`scipy.stats.ttest_ind`) to measure weather’s effect on ride duration  

---

## 📈 Results  
- **Top Neighborhoods:** Loop, River North, Streeterville, and West Loop dominate drop-off demand → critical areas for Zuber presence.  
- **Competitor Analysis:** Flash Cab leads with ~19.5k rides on the Nov. 15th weekend, nearly double its closest competitors (Taxi Affiliation Services, Medallion Leasing, Yellow Cab).  
- **Weather Impact:** Hypothesis testing showed that **rainy weather significantly increases average ride duration** from Loop to O’Hare Airport on Saturdays.  

---

## 💡 Key Insights  
- **Neighborhood Targeting:** Prioritize Zuber presence and incentives in Loop, River North, Streeterville, and West Loop.  
- **Competitive Strategy:** Study Flash Cab’s pricing/marketing closely; consider undercutting fares or offering driver/rider incentives to capture share.  
- **Weather Opportunity:** Demand shifts in rainy conditions — more riders call taxis from further away to avoid transit or unsafe driving.  
  - Consider **driver bonuses** for operating in rainy conditions.  
  - Explore offering **larger, AWD-equipped vehicles** as a premium option during inclement weather.  

---

## 🗂 Repo Structure  
```
chicago-rideshare-analysis/
├── notebooks/ <- Final cleaned Jupyter notebook
├── data/ <- Trip, company, and weather data
├── requirements.txt <- Dependencies
├── LICENSE <- MIT License
└── README.md <- This file
```

---

## 🚀 How to Run  
1. Clone the repo:  
   ```bash
   git clone https://github.com/Flamingo-Rocker/chicago-rideshare-analysis.git
   cd chicago-rideshare-analysis
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
3. Open the notebook in `/notebooks` to explore the workflow.

---

## 📦 Requirements
```
pandas==2.3.2
numpy==2.2.5
numpy-base==2.2.5            
numpydoc==1.9.0            
matplotlib==3.10.5           
matplotlib-base==3.10.5           
matplotlib-inline==0.1.6        
plotly==6.3.0           
mpmath==1.3.0            
sphinxcontrib-jsmath==1.0.1            
scipy==1.16.0           
mkl_random==1.2.8
```

---

## 🙏 Acknowledgment
Developed as part of the TripleTen Data Science Bootcamp, applying exploratory data analysis and hypothesis testing to inform rideshare strategy.