# SpaceX_RestAPI

## SpaceX Falcon 9 Launch Data Analysis & Prediction

### Overview
This project explores SpaceX Falcon rocket launch data to analyze mission trends, operational performance, and predict launch outcomes using machine learning classifiers.

Through a blend of SQL data queries, exploratory data analysis (EDA), geospatial mapping, dashboard visualization, and predictive modeling, the project provides actionable insights into commercial rocket launches, highlighting successes, challenges, and the factors influencing mission outcomes.

### Dataset
**Source:** SpaceX Falcon Launches (via SpaceX REST API and open datasets)

Features include:
- Launch date
- Launch site
- Payload mass
- Booster version
- Orbit type
- Landing outcome
- Mission success/failure

### Key Insights

**Florida is the launch hub**
Over half of all SpaceX launches and successes occur at Cape Canaveral's SLC 40 and Kennedy Space Center's LC 39A. Vandenberg's SLC 4E primarily supports polar orbits with lower launch frequency.

**High mission success rate**
Overall launch success exceeds 75%, with the Decision Tree and SVM classifiers achieving the highest accuracy (~0.87) in predicting launch outcomes.

**Failures are rare but informative**
Most failed or misclassified launches are associated with early booster variants or missions at the payload capacity limit.

**Machine learning effectiveness**
Models like Logistic Regression, Decision Tree, and SVM reveal payload mass, launch site, and booster version as the most influential predictors of success.

**Dashboarding and mapping**
Interactive dashboards and maps visualize launch site distribution, success probabilities, and temporal mission trends, aiding in quick strategic assessments.

### Technologies Used
- Python 3
- Jupyter Notebook
- Pandas, NumPy - Data preprocessing and manipulation
- Matplotlib, Seaborn, Plotly - Data visualization
- Scikit-learn - Model training and evaluation
- Folium - Geospatial mapping
- Dash / Plotly Express - Dashboard creation
- SQL / SQLite - Data extraction and querying

### Machine Learning Models

| Model | Accuracy | Key Strength |
|---|---|---|
| Logistic Regression | 0.81 | Fast, interpretable baseline |
| Decision Tree | 0.87 | High accuracy, feature importance |
| SVM (RBF Kernel) | 0.87 | Robust classification |
| KNN | 0.79 | Simplicity, non-parametric |
| Random Forest | 0.85 | Balanced accuracy and robustness |

### How to Run the Project

Clone this repository:
```
git clone https://github.com/<your-username>/SpaceX_RestAPI.git
cd SpaceX_RestAPI
```

Install dependencies:
```
pip install -r requirements.txt
```

Open and run the notebook:
```
jupyter notebook SpaceX.ipynb
```

### Results
- Comprehensive EDA showcasing key operational metrics
- Interactive maps of global launch sites
- Predictive modeling of launch success
- Visual dashboards summarizing model results and insights

### Author
Chris Varghese Koshy
B.Sc. (Hons.) Data Science & Analytics
Ramaiah University of Applied Sciences
