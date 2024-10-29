# HepsiEmlak Data Scraping and Analysis

This repository contains scripts for web scraping and data analysis on HepsiEmlak real estate listings.

## Project Structure

- **`HepsiEmlakWebScraping/Hepsi_Emlak_Web_Scraping.ipynb`** - Notebook for scraping property data from HepsiEmlak.
- **`HepsiEmlakDataAnalysis/Hepsi_Emlak_Data_Analysis.ipynb`** - Notebook for data cleaning, analysis, and preparation.
- **`Hepsi_Emlak_Data_Cleaned.xlsx`** - Final cleaned dataset in Excel format.

## How to Use

### Prerequisites

Install the required libraries:
``bash
pip install requests beautifulsoup4 pandas numpy

## Steps

- **Scrape Data**: Run `Hepsi_Emlak_Web_Scraping.ipynb` to collect property listings and save them to `Hepsi_Emlak.xlsx`.
- **Analyze Data**: Use `Hepsi_Emlak_Data_Analysis.ipynb` to clean, analyze, and prepare the data. Results are saved as `Hepsi_Emlak_Data_Cleaned.xlsx`.

## Key Features

- **Web Scraping**: Collects property details like price, location, and amenities from multiple pages.
- **Data Cleaning & Analysis**: Handles missing data, feature engineering, and provides summary statistics.

## Notes

- **Error Handling**: Basic handling is in place to skip missing or malformed entries.
- **Delays**: Adds pauses to avoid server overload.

