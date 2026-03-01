🏏 IPL 2023 Auction Data Analysis

📌 Project Overview

This project analyzes the IPL 2023 Auction Dataset using Python for data cleaning, preprocessing, visualization, and correlation analysis.

The goal is to explore player pricing, team distribution, player types, and prepare the dataset for further machine learning tasks.

📂 Dataset

Dataset used:

IPL_Squad_2023_Auction_Dataset.csv

Main Features:

Player's List

Base Price

COST IN ₹ (CR.)

Cost IN $ (000)

TYPE (Player Role)

Team

2022 Squad

🛠️ Technologies Used

Python 🐍

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

🔎 Data Preprocessing Steps

1️⃣ Data Cleaning

Removed duplicate rows

Handled missing values

Dropped unnecessary column: Unnamed: 0

Converted price columns to numeric format

2️⃣ Missing Values Handling

Filled price NaN values with 0

Filled missing 2022 Squad with "None"

3️⃣ Feature Scaling

Applied MinMaxScaler on:

Base Price

COST IN ₹ (CR.)

Cost IN $ (000)

4️⃣ Encoding Categorical Features

Used LabelEncoder for:

TYPE

Team

2022 Squad

📊 Exploratory Data Analysis (EDA)

✔ Team Distribution

Countplot visualization of number of players per team.

✔ Player Type Distribution

Analysis of:

Batsman

Bowler

All-rounder

Wicketkeeper

✔ Correlation Analysis

Generated correlation matrix to examine relationships between numerical features.

📈 Sample Visualizations

Team Count Plot

Player Type Count Plot

Correlation Matrix
