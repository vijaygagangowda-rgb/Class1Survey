# Class 1 Survey Data Analysis
## Project Description
This repository includes the Class 1 survey dataset and R Markdown code used
to analyze it. The project is part of an exercise to practice working with
real-world data in R Markdown using reproducible workflows.

## Files Included
- `Class 1 Survey Fall 2025 2.csv`: Class 1 survey dataset (as provided)
- `Class1survey.rmd`: R Markdown used to import, clean, and analyze the data
- `Class1survey.html`: Knitted HTML output 
- `README.md`: This file

## What the Code Does
- Reads in the survey dataset (from the GitHub raw URL)
- Performs basic data cleaning (e.g., renaming columns)
- Displays variable type counts (factor/integer/numeric/character)
- Checks and cleans `bday` and `bmonth`, then computes their medians
- Creates a `bseason` variable (Northern meteorological seasons) and reports season totals
- Answers a simple question: **Are dogs or cats more popular?** (standardizes yes/no and counts)


## How to Run the Code
1. Download or clone this repository to your computer.
2. Open `Class1survey.rmd` in RStudio.
3. Make sure the required packages are installed/loaded
4. Make sure your working directory is set to the folder where the files are
saved
5. Run the script  


## Author
- Name: Gagan Vijay
- Course: ADA
- Date: MONTH YEAR- 17 Sep 2025
