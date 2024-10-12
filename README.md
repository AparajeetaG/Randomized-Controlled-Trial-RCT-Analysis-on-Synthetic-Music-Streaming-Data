# Randomized-Controlled-Trial-RCT-Analysis-on-Synthetic-Music-Streaming-Data
This project simulates user behavior on a music streaming platform and evaluates the impact of a marketing campaign using a Randomized Controlled Trial (RCT). By creating a synthetic dataset, the analysis explores how campaign exposure affects user engagement, measured through time spent on the platform and user retention rates.
# Synopsis
The primary objective of this project is to demonstrate how to conduct an RCT using synthetic data to assess the effectiveness of a marketing campaign. The analysis includes data simulation, statistical testing, effect size calculation, regression analysis, and various visualizations to provide comprehensive insights into user behavior and campaign impact.

# Features
Synthetic Data Generation: Creates a realistic dataset simulating user interactions.
Randomized Controlled Trial: Compares treatment and control groups to assess campaign impact.
Statistical Testing: Utilizes T-tests and Chi-Square tests to determine significance.
Effect Size Calculation: Measures the magnitude of campaign effects.
Regression Analysis: Controls for confounding variables to isolate campaign impact.
Data Visualization: Includes bar plots, box plots, histograms, and interaction effect plots for insightful data representation.

# Dataset
The synthetic dataset includes the following features:

user_id: Unique identifier for each user.
region: Geographic region of the user (North America, Europe, Asia, South America).
campaign_exposure: Binary indicator (1 = exposed to the campaign, 0 = not exposed).
time_spent_before: Time (in minutes) spent streaming music before the campaign.
time_spent_after: Time (in minutes) spent streaming music after the campaign.
retained: Binary indicator (1 = retained, 0 = not retained) representing user retention post-campaign.
