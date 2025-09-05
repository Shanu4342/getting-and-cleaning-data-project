# Getting and Cleaning Data - Course Project

This repository contains the R script and documentation for the Coursera "Getting and Cleaning Data" course project.

## Files
- `run_analysis.R`: R script that processes the UCI HAR Dataset and creates a tidy dataset.
- `tidy_data.txt`: Final tidy dataset created by the script.
- `CodeBook.md`: Description of variables and transformations.

## How to Run
1. Download and unzip the **UCI HAR Dataset** from:
   [UCI HAR Dataset Link](https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)
2. Place the folder `UCI HAR Dataset` in your R working directory.
3. Run the script:
   ```R
   source("run_analysis.R")
   ```
4. The output file `tidy_data.txt` will be created in the working directory.
