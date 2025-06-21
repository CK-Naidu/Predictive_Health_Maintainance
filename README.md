# Predictive Health Maintenance using Decision Trees and Random Forest

This repository contains the implementation of machine learning models to predict machine failure using the [Predictive Maintenance Dataset](https://www.kaggle.com/datasets/hiimanshuagarwal/predictive-maintenance-dataset). The goal is to develop interpretable and efficient classification models for early failure prediction.

-----
# Repository Structure

── decision_tree_random_forest_scratch.ipynb     # Full implementation from scratch
── decision_tree_random_forest_sklearn.ipynb     # Same models using scikit-learn
── decision_tree_pruning.ipynb                   # Decision tree with reduced error pruning
── predictive_maintenance_dataset.csv            # Input dataset
── README.md                                     # Project documentation

----

This project implements machine learning models to **predict equipment failure before it occurs**, using historical sensor data.
The focus is on building interpretable models using **Decision Trees** and **Random Forests**, both from scratch and with `scikit-learn`, along with **tree pruning techniques** to improve generalization.

----

# What is Predictive Health Maintenance (PHM)?

**Predictive Health Maintenance** is a proactive maintenance strategy that uses real-time sensor data, historical performance records, and machine learning to **predict when a machine is likely to fail**. The goal is to perform maintenance just before a failure occurs, minimizing downtime and reducing unnecessary costs.

# Key Concepts:
- **Failure Prediction**: Using metrics such as vibration, temperature, pressure, etc., to forecast when a component might fail.
- **Classification Task**: The model classifies whether a machine is in a **healthy** or **failing** state.
- **Data-Driven Maintenance**: PHM shifts maintenance from fixed schedules to **smart, data-driven decisions**.

Applications of PHM span industries like:
- Manufacturing
- Aerospace
- Automotive
- Power plants
- Industrial IoT (IIoT)
