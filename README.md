# Data correlation analysis
 Data Correlation Analysis with Pandas, Seaborn, and Matplotlib

This repository contains a Python script that performs exploratory data analysis (EDA) on a sample dataset using pandas, seaborn, and matplotlib. The script covers essential steps in data analysis, such as loading, cleaning, and visualizing relationships among features, and includes tools for data inspection and correlation analysis.

## Features
* Load and inspect dataset statistics and structure.
* Remove duplicate rows.
* Calculate and visualize correlations with a heatmap.
* Generate pairwise scatter and regression plots to explore relationships between features.

## Prerequisites
Ensure you have Python installed (preferably version 3.6 or later) along with the following libraries:
* pandas
* seaborn
* matplotlib

You can install these libraries using pip:

pip install pandas seaborn matplotlib


## Setup
1. Clone this repository to your local machine:

git clone https://github.com/your-username/data-analysis.git


2. Navigate to the project directory:

cd data-analysis

3. Place your dataset in CSV format within this directory, and rename it as example_dataset.csv (or modify the code to use your dataset’s name).

## Usage
Run the script using Python:

python script.py


The script will:

1. Load the dataset from the CSV file.
2. Display basic information about the dataset, including column data types, missing values, and initial statistics.
3. Remove any duplicate rows, if present.
4. Display a correlation heatmap, showing relationships among numerical features.
5. Display a pairwise plot with regression lines to visualize relationships between each pair of features.

## Code Breakdown
The main steps in the script include:

* _Data Loading and Inspection_: The dataset is loaded into a pandas DataFrame, and describe(), info(), and head() are used to display initial statistics and structure.
* _Duplicate Removal_: Duplicate rows, if any, are removed to ensure data integrity.
* _Correlation Analysis_: A correlation matrix is calculated and visualized with a seaborn heatmap to highlight correlations among numerical columns.
* _Pairwise Plotting_: Pairwise scatter and regression plots are generated to analyze relationships and trends in the data.

## Example Output
The script generates several visualizations, including:
1. A correlation heatmap for numerical features.
2. A pairwise plot with regression lines to show linear relationships.
3. A pairwise scatter plot for feature comparison.


## Conclusion
Based on the script, you can identify correlations and trends within your dataset. If additional data analysis is required, you can modify the script by adding further transformations, filtering, or custom visualizations as needed.

## Troubleshooting
* File Not Found Error: Ensure your dataset file is named example_dataset.csv or update the script with the correct file path.
* Library Import Error: Ensure all necessary libraries (pandas, seaborn, matplotlib) are installed.