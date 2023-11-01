# COVID-19 VACCINES ANALYSIS 
This project involves an analysis of a dataset containing information about covid vaccine that is distributed across the world. The dataset includes details like country,country ISO code, date, total vaccinations,people vaccinated,people fully vaccinated,daily Vaccinations, people vaccinated per hundred,daily vaccinations per million. In this README, you'll find information about the project, how to run the code, and a brief summary of the analysis.

## Table of Contents

- [Project Description](#project-description)
- [Dataset](#dataset)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Data Overview](#data-overview)
- [Data Analysis](#data-analysis)
- [Conclusions](#conclusions)

## Project Description

This project is a Python-based data analysis of covid world vaccination progress.  It conducts an in-depth analysis of COVID19 vaccine data, including efficacy, distribution, and adverse effect, to provide insights that aid policy makers and health organizations in optimizing vaccine deployment strategies .The analysis aims to provide insights and answer specific questions related to the dataset.

## Dataset

The dataset used in this project contains the following features:
- country
- iso_code
- date
- total_vaccinations
- people_vaccinated
- people_fully_vaccinated
- daily_vaccinations_raw
- daily_vaccinations
- total_vaccinations_per_hundred
- people_vaccinated_per_hundred
- people_fully_vaccinated_per_hundred
- daily_vaccinations_per_million
- vaccines
- source_name
- source_website

## Prerequisites

Before running the code for this project, you should have the following libraries installed:

- pandas
- numpy
- seaborn
- matplotlib
- scipy
- sklearn
- datetime

You can install these libraries using pip:


```bash 
pip install pandas numpy seaborn matplotlib scipy sklearn
```

## Getting Started

To get started with this project, follow these steps:

Clone the repository to your local machine.
Install the required libraries as mentioned in the prerequisites.
Run the Jupyter Notebook containing the Python code.

## Data Overview:
The initial data overview section involves importing the dataset, checking for missing values, and performing data preprocessing. The dataset's structure and summary statistics are also displayed.

## Data Preprocessing:

Data is loaded from two CSV files, country_vaccinations.csv and country_vaccinations_by_manufacturer.csv.
Missing values are handled, especially for the 'total_vaccinations' column, which is adjusted using 'people_vaccinated' and 'people_fully_vaccinated'.
Time-related features like day, month, week of the year, and day of the week are derived from the 'date' column.
Missing values are filled using related columns or previous values from the same country.

## Data Analysis:

Box plots are created to identify data distribution and potential outliers.
A correlation matrix and heatmap are generated to visualize relationships between variables.
A t-test is performed to check for significant differences between two groups based on 'total_vaccinations'.
A histogram illustrates the distribution of 'daily_vaccinations'.
A count plot shows the distribution of 'daily_vaccinations_per_million'.
A line plot displays the change in 'people_vaccinated' over time.

## Results:

The box plots reveal data spread and potential outliers.
The correlation matrix and heatmap identify variable relationships.
The t-test checks for significant differences between two groups in terms of total vaccinations.
The histogram displays the distribution of daily vaccination rates.
The count plot visualizes vaccination rates per million people.
The line plot illustrates how the number of people vaccinated changes over time.

## Conclusions
The Covid Vaccine Analysis offers a comprehensive exploration of global vaccination data, presenting insights through meaningful visualizations and graphs. It answers specific questions about the dataset and identifies outliers.

For any questions or further information, please feel free to contact Me @ sreelekha.s2021@kgkite.ac.in


