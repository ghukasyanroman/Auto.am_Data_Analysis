# Auto.am Data Analysis Project

This repository contains a project developed by our group as part of the "Programming for Data Science" course at our university. The project involves scraping vehicle data from the [auto.am](https://www.auto.am) website, followed by data cleaning and preprocessing, and finally, visualizing the data and generating an HTML report using R.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
  - [Running the Scraper](#running-the-scraper)
  - [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
  - [Data Visualization](#data-visualization)
- [Disclaimer](#disclaimer)

## Overview

The Auto.am Data Analysis Project is designed to collect and analyze data about vehicles listed on the auto.am website. The project is divided into three main parts:
1. **Scraping**: Collecting raw data from the website.
2. **Data Cleaning and Preprocessing**: Cleaning and structuring the scraped data.
3. **Visualization**: Using R to visualize and analyze the cleaned data.

## Features

- Scrapes vehicle data, including make, model, year, price, and more.
- Cleans and preprocesses the data for analysis.
- Visualizes data using R language.

## Installation

To get started with the project, follow these steps:

1. Ensure you have installed all necessary drivers and packages for Selenium as the scraping was done using Selenium.
2. Install the Pandas library by running the command `pip install pandas`.
3. Install the required R packages by running the following R code:
    ```r
    install.packages(c("ggplot2", "dplyr", "scales", "ggwordcloud", "corrplot", "ggrepel", "tidyverse"))
    ```

## Usage

### Running the Scraper
To run the scraper and collect data from auto.am, after successfully installing all necessary drivers and packages, execute the `auto_scrap.ipynb file`. Please note that the generated dataset (`final_dataset.csv`) will be saved in the same location as the `auto_scrap.ipynb` file.

### Data Cleaning and Preprocessing
Since you have installed the Pandas package, you can run the `data_cleaning.ipynb` file. Make sure that both this file and the `final_dataset.csv` generated in the previous step are located in the same folder. After successfully running this file, it will generate three new cleaned datasets: `Final_Project_Dataset.csv`, `Not_Electric.csv`, and `Electric.csv`.

### Data Visualization
Once you have installed all the mentioned R packages and ensured that all files are located in the same folder, you can then run the `Project_Vis.Rmd` file. 

## Disclaimer

This scraper is for educational and research purposes only. Make sure to review and comply with the terms of service of the auto.am website. The author is not responsible for any misuse of this tool.


