# SpaceX_RestAPI

# SpaceX Falcon 9 Launch Data Analysis & Prediction

## Overview

This project explores SpaceX Falcon rocket launch data to analyze mission trends, operational performance, and predict launch outcomes using machine learning classifiers. Through a blend of SQL data queries, exploratory data analysis, geospatial mapping, dashboard visualization, and predictive modeling, the project provides actionable insight into commercial rocket launches—highlighting the successes, challenges, and the factors that influence mission outcomes.

---

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Key Insights](#key-insights)
- [Project Structure](#project-structure)
- [How to Run](#how-to-run)
- [Visualization Gallery](#visualization-gallery)
- [Results](#results)
---

## Dataset

- Source: [SpaceX Falcon Launches]("https://api.spacexdata.com/v4/launches/past")
- Features include: Launch date, site, payload mass, booster version, orbit, landing outcome, and more.

---

## Key Insights

- **Florida is the launch hub:** Over half of all SpaceX launches and successes occur at Cape Canaveral’s SLC 40 and Kennedy Space Center’s LC 39A. Vandenberg SLC 4E supports polar orbits and lower traffic.
- **Success rates are high:** Mission success exceeds 75%, with the Decision Tree and SVM models achieving highest accuracy (~0.87) for predicting launch outcomes.
- **Failures are rare but informative:** Most misclassifications or failures are associated with earlier booster variants or missions at the edge of payload limits.
- **Machine learning is effective:** Classification models can robustly predict launch success based on operational features, and reveal influential factors like payload, launch site, and booster version.
- **Dashboarding & Mapping:** Visual dashboards and
