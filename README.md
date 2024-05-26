
# Project Title: COVID-19 Data Analysis and Visualization

## Overview
This project aims to analyze and visualize COVID-19 data. It involves loading a dataset, preprocessing it, and creating visualizations to show the number of confirmed cases, recoveries, and deaths over time for various countries as well as worldwide.

## Prerequisites
Python 3
pandas
numpy
matplotlib
scikit-learn

## Installation
Install the required libraries using pip:
```bash
pip install pandas numpy matplotlib scikit-learn
```

Ensure you have the COVID-19 dataset (covid_19_data.csv) in the specified path (C:/Users/KIIT/Downloads/).

## Usage
1. Load and preprocess the data:
  The dataset is loaded and displayed.
  Unnecessary columns (SNo and Last Update) are dropped.
  Columns are renamed for better readability.
  The Date column is converted to a datetime type.
  Missing values are handled using SimpleImputer.

2. Group and Summarize Data:
Data is grouped by Country and Date, and the sums of Confirmed, Deaths, and Recovered are calculated.

3. Visualization:
Scatter plots are created for each country showing the number of confirmed cases, recoveries, and deaths over time.
A global scatter plot is created showing the worldwide number of confirmed cases, recoveries, and deaths over time.

4. View the Plots:
Run the script to view the plots for individual countries and the world.
Each plot will display the number of confirmed cases, recoveries, and deaths over the days since the first reported case.

Example
To run the script, execute the following command:
```bash
python script_name.py
```
Replace script_name.py with the name of your script file.
The script will generate scatter plots for each country, showing the progression of COVID-19 cases, recoveries, and deaths. It will also generate a global scatter plot.


## License
This project is licensed under the MIT License.
