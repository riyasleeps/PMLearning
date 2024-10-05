# Project Title: Predictive Modeling with R

## Overview
This project aims to build predictive models using data from the **PML** (Practical Machine Learning) course. The analysis focuses on predicting the class of activities based on sensor data. The project uses both Decision Tree and Random Forest models.

## Directory Structure
project/ │ ├── data/ │ ├── pml-training.csv │ └── pml-testing.csv │ ├── PML.Rmd # R Markdown file containing the analysis ├── PML.html # Generated HTML output of the R Markdown └── README.md

## Required Libraries
To run this project, the following R packages are needed:
- `caret`: For data partitioning and model evaluation
- `randomForest`: For building random forest models
- `ggplot2`: For data visualization
- `rpart`: For creating decision trees
- `rpart.plot`: For visualizing decision trees

You can install these packages using the following command in R:
```r
install.packages(c("caret", "randomForest", "ggplot2", "rpart", "rpart.plot"))
Data Sources
The datasets used in this project are:
Training Data
Testing Data
Analysis Steps

## Load Required Libraries:
The necessary libraries are loaded at the beginning of the R Markdown file.
Set File Paths: Paths and URLs for the training and testing datasets are defined.
Create Directories: Necessary directories for data storage are created if they do not exist.
Set Seed for Reproducibility: A random seed is set to ensure that results can be reproduced.
Read and Clean Data: The datasets are read, missing values are handled, and unnecessary columns are removed.
Split the Data: The training data is split into training and validation sets.
Build Models: Decision Tree and Random Forest models are built and evaluated using confusion matrices.
Visualize Results: The structure of the decision tree is visualized.
