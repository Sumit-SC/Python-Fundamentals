# COVID-19 Vaccination Exploratory Data Analysis (EDA) Project

This repository contains an exploratory data analysis (EDA) project related to COVID-19 vaccination data. The project aims to analyze and visualize vaccination trends, patterns, and insights based on available COVID-19 vaccination data.

## Table of Contents

- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Analysis Overview](#analysis-overview)
- [Data Sources](#data-sources)
- [Getting Started](#getting-started)
- [Directory Structure](#directory-structure)
- [Suggestions](#suggestions)

----

### Introduction

Welcome to the COVID-19 Vaccination Exploratory Data Analysis (EDA) project. This project focuses on analyzing and visualizing data related to the COVID-19 pandemic, aiming to gain insights into the spread, trends, and impacts of the virus.

### Project Overview

The primary objective of this project is to conduct a thorough exploratory analysis on COVID-19 vaccination data to understand vaccination rates, distribution, demographics, and other key factors influencing the vaccination process. The analysis includes data exploration, visualization, and insights to provide a comprehensive view of the vaccination landscape.

#### Key Features

- Exploratory data analysis (EDA) on COVID-19 Vaccination.
- Visualization of COVID-19 Vaccination trends using various charts and graphs.
- Interpretation of the analysis results to derive meaningful insights.

#### Analysis Overview

From the observation of the analysis of the given dataset we have come across the various impacts of covid-19 pandemic around the different parts of the world including live case count,number of deaths,vaccination details etc. For our analysis we focused on the India by segregating the data for the country in a new dataframe from the overall datasource.
>
The result of the analysis are given inside the report and demonstrated in the notebook files look through it for more indepth analysis.

#### Data Sources
The data used in this project is sourced from reputable sources, including government health departments, public health organizations, and trusted repositories.

[Country_Vacccination](../data/processed/country_vaccinations.csv)

#### Getting Started

##### 1. Prerequisites:

- Python (with necessary libraries like Pandas, NumPy, Matplotlib, Seaborn, etc.).
- Jupyter Notebook or any preferred Python environment.
- Download the dataset csv file from the [Source Link](#data-sources) given above if you want to make your own analysis by looking at the code.

##### 2. Installation:

1. Clone this repository: `git clone https://github.com/Sumit-SC/Python-Fundamentals.git` to your local machine.
>
2. Open and run the Jupyter notebooks in the `notebooks/` directory to perform the analysis and generate visualizations.

##### 3. Usage:

- Navigate to the repository and open the provided Jupyter notebooks.
- Run the cells in the notebooks to perform the analysis and generate visualizations.

> If some library are missing uncomment the 1st line of code for installation or run the requirements txt file in the previous directory(`/src`) to download all the necessary library files.

#### Directory Structure :

--------

    ├── notebooks/                              <- # Jupyter notebooks for analysis
    ├── data/
    │   └──processed/                           <- # Data used in the analysis
    ├── src/
    │   └──visualization/                       <- # Visualizations generated during the analysis
    ├── reports/                                <- # Report made on the EDA
    ├── references/
    │   └──Covid19_Vaccination_Sources.md       <- # Sources and case study on vaccination dataset and reports made by government bodies and individuals.
    └── docs
        └──Covid19_Vaccinations-EDA_info.md     <- # Project README file
    

---------

#### Suggestions

As a beginner to data science & analytics field i am bound to make silly mistakes in my code or can improve a lot on my visualization , if anyone wants to add a suggestion they can create an issue to point my mistakes.
>
Every suggestion is valuable for beginners in the learning process.