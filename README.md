# GB885_DiscussionCodingChallengeRepositories_Assignment_5

# Chef's Choice: Strava Running Activity Data Cleaning

## Project Overview

This project demonstrates the process of inspecting and cleaning a real-world fitness tracking dataset using Python and pandas. Raw data often contains inconsistencies, missing values, duplicate records, and incorrect data types that can reduce the quality of analyses. The goal of this project is to prepare the dataset so it can be reliably used for future exploratory analysis and visualization.

## Business Question

How can a running activity dataset be cleaned and standardized to produce accurate, consistent, and reliable data for analyzing running performance and training habits?

By cleaning the dataset, analysts can confidently answer questions such as:

- How far and how often does the runner train?
- How has running pace changed over time?
- What trends exist in elevation gain, distance, or moving time?
- Which activities should be excluded from running-specific analyses?

## Dataset

This project uses the **Strava Running Activity Data** dataset published on Kaggle by Ajit Jadhav.

The dataset contains personal Strava activity records collected between **March 2022 and December 2023**, including information such as:

- Activity date
- Distance
- Moving time
- Elapsed time
- Elevation gain
- Pace
- Activity type
- Start and end GPS coordinates

## Data Cleaning Performed

The notebook performs several data quality improvements, including:

- Converting date columns to datetime format
- Removing non-running activities
- Removing records with missing latitude/longitude coordinates
- Removing unnecessary columns
- Renaming columns to include measurement units
- Checking for duplicate records
- Verifying data consistency and data types

## How to Run

1. Open the GB885_Assignment_5_Bley_S.ipynb file in GitHub.
<img width="274" height="122" alt="image" src="https://github.com/user-attachments/assets/8621c187-1a5e-4364-bf75-41ff69fb240d" />


2. Click the Open in Colab button at the top.
. <img width="611" height="175" alt="image" src="https://github.com/user-attachments/assets/5c895e63-4484-4750-b768-eef900167c1f" />

3. Click "Run All".
<img width="329" height="89" alt="image" src="https://github.com/user-attachments/assets/ef51c9b9-847d-4fe6-813c-7c618537c595" />
