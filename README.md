````markdown
# Oil Well Production Optimization & Drilling Efficiency Analysis

> **A comprehensive Business Intelligence and Data Analytics project that explores oil production performance, drilling efficiency, geospatial distribution, and machine learning clustering using Python and interactive visualizations.**

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellow)
![GeoPandas](https://img.shields.io/badge/GeoPandas-Spatial%20Analysis-green)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-KMeans-red)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

# Project Overview

The oil and gas industry generates enormous volumes of operational and production data every day. Transforming this information into actionable business intelligence is essential for improving drilling efficiency, maximizing production, reducing operational costs, and supporting strategic field development.

This project combines **production analytics**, **drilling performance analysis**, **geospatial visualization**, and **machine learning** to evaluate historical oil well data and identify patterns that support operational decision-making.

The project was completed as part of a Data Visualization and Business Intelligence coursework using Python and modern data analytics libraries.

---

# Business Objectives

The primary objectives of this project were to:

- Analyze historical oil production trends.
- Evaluate drilling efficiency using operational drilling parameters.
- Identify high-performing wells and production regions.
- Explore spatial distribution of petroleum wells across Ontario.
- Detect operational patterns using Machine Learning.
- Build interactive visualizations that communicate engineering insights.
- Generate actionable business recommendations for field operations.

---

# Data Sources

This project integrates multiple publicly available datasets.

| Dataset | Description | Source |
|---------|-------------|--------|
| **ROP (Rate of Penetration) Dataset** | Drilling operational parameters including ROP, RPM, WOB, Torque, Pump Pressure and drilling logs. | https://www.kaggle.com/datasets/ahmedelbashir99/drilling-log-dataset |
| **Oil Well Production Dataset** | Historical production records used for production trend and reservoir performance analysis. | https://www.kaggle.com/datasets/ruslanzalevskikh/oil-well |
| **Ontario Well Shapefile** | Geographic boundaries and petroleum well locations used for geospatial visualization. | https://open.canada.ca/data/dataset/235fcd04-6632-4cce-a403-556089cc4276/resource/d5fbee67-c36a-4044-997d-ebe809a0073a |

---

# Data Preparation

The datasets were cleaned and transformed before analysis.

The preprocessing workflow included:

- Missing value treatment
- Duplicate removal
- Data type conversion
- Feature engineering
- Date formatting
- Aggregation of production records
- Spatial data integration using GeoPandas
- Dataset merging
- Data normalization for clustering analysis

---

# Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- GeoPandas
- Scikit-learn
- K-Means Clustering
- Ruptures (Change Point Detection)
- Jupyter Notebook

---

# Project Workflow

```
Raw Data
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Production Analysis
      │
      ▼
Drilling Performance Analysis
      │
      ▼
Geospatial Visualization
      │
      ▼
Machine Learning (K-Means)
      │
      ▼
Business Insights
      │
      ▼
Recommendations
```

---

# Analysis Performed

## Production Analysis

- Oil Production
- Gas Production
- Water Production
- Liquid Production
- Water Cut
- Production Trend Analysis

---

## Drilling Performance

The drilling dataset was analyzed using several operational parameters including:

- Rate of Penetration (ROP)
- Weight on Bit (WOB)
- Rotary Speed (RPM)
- Torque
- Pump Pressure
- Mud Flow Parameters

These variables were explored to identify relationships affecting drilling efficiency.

---

## Machine Learning

K-Means clustering was implemented to group drilling operations into similar performance categories.

The clustering analysis identified drilling strategy groups that can support operational optimization and benchmarking.

---

## Geospatial Analysis

Using GeoPandas and the Ontario petroleum well shapefile, petroleum wells were visualized geographically to reveal regional drilling activity and production distribution.

---

## Time Series Analysis

Historical production trends were evaluated to identify:

- Production decline
- Production growth
- Reservoir performance changes
- Long-term operational behavior

---

# Project Visualizations

## Production Dashboard

*(Insert screenshot in `/images/production_dashboard.png`)*

```markdown
![Production Dashboard](images/production_dashboard.png)
```

---

## Drilling Performance Dashboard

*(Insert screenshot in `/images/drilling_dashboard.png`)*

```markdown
![Drilling Dashboard](images/drilling_dashboard.png)
```

---

## Geospatial Dashboard

*(Insert screenshot in `/images/geospatial_dashboard.png`)*

```markdown
![Geospatial Dashboard](images/geospatial_dashboard.png)
```

---

## Clustering Results

*(Insert screenshot in `/images/clustering.png`)*

```markdown
![Clustering Results](images/clustering.png)
```

---

# Key Insights

- Historical production exhibits a gradual decline consistent with mature oil reservoirs.
- Water production increases over time, indicating changing reservoir conditions.
- Drilling operational parameters significantly influence Rate of Penetration.
- K-Means clustering successfully identified distinct drilling performance groups.
- Ontario petroleum wells are spatially concentrated in key production regions.
- Geospatial visualization highlights regional drilling activity and operational density.
- Production analytics provide valuable insight for field optimization and long-term planning.

---

# Business Recommendations

- Continuously monitor production trends to detect early performance decline.
- Optimize drilling parameters based on high-performing drilling clusters.
- Use spatial analytics to support future well placement decisions.
- Apply predictive analytics for production forecasting.
- Expand machine learning models to optimize drilling operations in real time.
- Integrate dashboards into operational monitoring systems for continuous decision support.

---

# Repository Structure

```
Oil-Well-Production-Optimization
│
├── README.md
├── notebooks
│   └── PROJECT FOR DATASET VISUALIZATION FINAL.ipynb
│
├── data
│   └── README.md
│
├── images
│   ├── production_dashboard.png
│   ├── drilling_dashboard.png
│   ├── geospatial_dashboard.png
│   └── clustering.png
│
├── reports
│   └── Business_Intelligence_Report.pdf
│
└── presentation
    └── Presentation.pdf
```

---

# Future Improvements

- Predictive production forecasting
- Deep learning production models
- Interactive Streamlit dashboard
- Real-time drilling monitoring
- Reservoir decline curve analysis
- Advanced drilling optimization models

---

# Author

**Richard Amarachi Chijioke**

**Master of Data Science**

**Mechanical Engineer**

**Data Analytics | Business Intelligence | Machine Learning | Python | SQL | Tableau | Computer Vision**

---

⭐ *If you found this project interesting, feel free to star the repository.*
````

