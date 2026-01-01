# Getting and Cleaning Data Course Project

## Author
Greatness Eyenor

## Project Description
This project is part of the Coursera course **Getting and Cleaning Data**.
The goal of the project is to clean and tidy the Human Activity Recognition
Using Smartphones Dataset so that it is easy to analyze.

The final output is a tidy dataset that contains the **average of each
measurement for each activity and each subject**.

---

## Files in this Repository

- `run_analysis.R`  
  The R script that performs all data cleaning steps.

- `tidy_dataset.txt`  
  The final tidy dataset produced by the script.

- `CodeBook.md`  
  Describes the variables, data transformations, and summaries.

- `README.md`  
  Explains how the analysis was performed.

---

## Data Source
The original dataset used in this project is the **UCI Human Activity
Recognition Using Smartphones Dataset**.

---

## How to Run the Analysis

1. Download and unzip the UCI HAR Dataset.
2. Set the working directory in R to the folder that contains:
   - `features.txt`
   - `activity_labels.txt`
   - `train/`
   - `test/`
3. Run the script:
   ```r
   source("run_analysis.R")
The script will generate a file called:

tidy_dataset.txt

