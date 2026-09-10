# End-to-End Academic Performance Prediction & Analytics

An end-to-end Machine Learning project for analyzing and predicting student academic performance.
The project covers the complete Data Science and Machine Learning lifecycle — from data ingestion and exploratory data analysis to data transformation, model training, experiment tracking, and application deployment.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📌 Project Overview

Student academic performance can be influenced by several demographic, educational, and socioeconomic factors.

This project analyzes student performance data and builds a machine learning pipeline to understand these relationships and predict academic outcomes.

The dataset contains information such as:

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Mathematics Score
- Reading Score
- Writing Score

The dataset contains **1,000 student records and 8 original features**.

During feature engineering, additional metrics such as:

- Total Score
- Average Score

are derived from the subject-level scores.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🎯 Objectives

- Perform exploratory data analysis on student performance data
- Understand relationships between student characteristics and academic performance
- Clean and transform raw data
- Build a reusable machine learning pipeline
- Train and evaluate machine learning models
- Track experiments using MLflow and DagsHub
- Version data and pipeline artifacts using DVC
- Organize the project using a modular Python structure
- Containerize the application using Docker

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🏗️ Project Architecture


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🔄 Machine Learning Pipeline

Raw Data
   ↓
Data Ingestion
   ↓
Data Validation
   ↓
Data Transformation
   ↓
Feature Engineering
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Experiment Tracking
   ↓
Model Artifact
   ↓
Prediction

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📊 Exploratory Data Analysis

The EDA process includes:

Dataset shape and structure analysis
Missing-value analysis
Duplicate-value detection
Data type analysis
Unique-value analysis
Statistical summary
Numerical feature analysis
Categorical feature analysis
Subject-wise score analysis
Total score calculation
Average score calculation
Visualization of student performance patterns

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📈 Experiment Tracking

MLflow

MLflow is used for experiment tracking and machine learning lifecycle management.

It can be used to track:

Model parameters
Evaluation metrics
Training runs
Model artifacts
Experiment history
DagsHub

DagsHub is integrated with the project to provide experiment and project tracking alongside MLflow.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🗂️ Data Version Control (DVC)

The project uses DVC (Data Version Control) to manage data and machine learning artifacts.

DVC helps separate large datasets and generated artifacts from Git source-code versioning while maintaining reproducible versions of the data pipeline.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

⚙️ Installation

1. Clone the repository

``bash``
  git clone https://github.com/GauravBidaeet/Data-science-project.git
  cd Data-science-project
``bash``
