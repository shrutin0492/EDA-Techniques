# EDA-Techniques
Assignment as part of the Explainable Artificial Intelligence course in the 3rd year of my undergrad.

Below is the formatted README file for your GitHub repository based on the provided code and descriptions:

---

# EDA Techniques for Olympic Games Data

This repository contains an Exploratory Data Analysis (EDA) notebook focusing on 120 years (1896 to 2016) of Olympic games data. The notebook explores various techniques for data examination and visualization using Python libraries such as Pandas and Seaborn.

## Contents

1. [Introduction](#introduction)
2. [Objective](#objective)
3. [Dataset Description](#dataset-description)
4. [Techniques Used](#techniques-used)
5. [Results](#results)

---

## Introduction

The notebook `xai_eda_eng21am0120.ipynb` is part of an assignment on Explainable AI (XAI) focusing on EDA techniques. It explores the Olympic games dataset, analyzing athletes' information and medal results over time.

---

## Objective

The primary objective of this analysis is to:

- Examine and clean the dataset
- Explore distributions of single numerical and categorical features via statistics and plots
- Explore relationships between multiple features via statistics and plots

---

## Dataset Description

The dataset used in this analysis is sourced from Kaggle and contains information within `athlete_events.csv`. Each row corresponds to an individual athlete competing in an Olympic event, with columns including ID, Name, Sex, Age, Height, Weight, Team, NOC, Games, Year, Season, City, Sport, Event, and Medal.

[Original dataset source](https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results)

---

## Techniques Used

The notebook utilizes various techniques and libraries, including:

- Data importation using Pandas
- Data imputation using IterativeImputer from sklearn
- Statistical analysis using describe method
- Visualization techniques such as histograms, boxplots, scatterplots, pairplots, count plots, and heatmap using Seaborn

---

## Results

The analysis yields insights into the Olympic games dataset, including:

- Distribution of athlete ages and identification of outliers
- Popular sports for young and older athletes based on age outliers
- Unique values and counts for different columns such as Team, Sport, and Event
- Correlation analysis between Age, Height, and Weight
- Trends over time regarding athlete ages, gender distribution, and seasonal variations

---

Feel free to explore the notebook for a detailed walkthrough of the analysis.

**GitHub Repository:** [EDA Techniques](https://github.com/shrutin0492/EDA-Techniques)

**Colab Notebook:** [xai_eda_eng21am0120.ipynb](https://github.com/shrutin0492/EDA-Techniques/blob/main/xai_eda_eng21am0120.ipynb)

--- 

This README provides a structured overview of your analysis notebook, highlighting the key sections, objectives, techniques used, and results obtained. You can copy and paste this content into your GitHub repository's README.md file.
