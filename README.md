# SBP-and-NHANES-Data-Visualization

Description: 

This repository contains the files and outputs for a McGill University BIOS640 assignment building on Assignments 2 and 3. The project uses NHANES data to demonstrate reproducible data analysis, data visualization, interactive reporting, dashboard development, and table design using R and R Markdown.

Purpose of the Project: 

The purpose of this project is to build on previous NHANES analyses while applying principles of reproducibility, data visualization, interactive reporting, dashboard design, and table formatting.

The assignment includes three main components:

Exercise 2: Customizing an R Markdown report and creating an interactive HTML report.
Exercise 3: Creating an interactive NHANES dashboard using flexdashboard.
Exercise 4: Creating a formatted PDF report containing descriptive tables of the NHANES dataset and average systolic blood pressure.

Repository Structure

data/
Contains the datasets required for the analyses, including the cleaned NHANES dataset.

figures/
Contains saved figures from previous assignments that are reused in the Exercise 2 report and Exercise 3 dashboard.

exercise-2/
Contains the R Markdown source file and rendered outputs for Exercise 2, including:
The original Assignment 3 R Markdown report.
The original PDF report.
The updated R Markdown report.
The rendered HTML report.

The updated report includes a floating table of contents, tabbed sections, customized HTML formatting, and an interactive DT table of the cleaned NHANES dataset.

exercise-3/
Contains the R Markdown source file and rendered HTML dashboard for Exercise 3.

The dashboard includes:
A visualization describing the NHANES sample.
A gauge showing the percentage of individuals aged 21 years or older.
A value box showing the percentage of individuals with an average systolic blood pressure above 120 mm Hg.
exercise-4/

Contains the R Markdown source file and rendered PDF report for Exercise 4.

The report includes formatted tables describing:
Overall sample size by NHANES wave.
Number and percentage of males by wave.
Number and percentage of participants in each ethnicity category by wave.
Summary statistics for average systolic blood pressure by wave.
Reproducibility

This repository is organized so that the analyses can be reproduced by cloning the repository.

All file paths in the R Markdown files use here() or relative paths rather than computer-specific absolute paths.

Rendered outputs are committed alongside their corresponding R Markdown source files so that the results can be viewed without rendering the analyses from scratch.

To reproduce the analyses:
Clone this repository.
Open the project in RStudio.
Install the required R packages.
Open the relevant .Rmd file.
Render the document using the appropriate output format.
Software and Packages

This project was completed using R and RStudio.

Packages used include:
tidyverse
here
janitor
skimr
cowplot
ggpubr
DT
flexdashboard
kableExtra
knitr

Data Source

The project uses data from the National Health and Nutrition Examination Survey (NHANES). See bibliography in R Markdown.

NHANES is conducted by the National Center for Health Statistics (NCHS), part of the Centers for Disease Control and Prevention (CDC), and provides health and nutrition data from the United States.

Learning Objectives

This project demonstrates skills in:
Reproducible data analysis.
GitHub repository organization and version control.
R Markdown customization.
HTML reporting.
Interactive data tables using DT.
Dashboard development using flexdashboard.
Data visualization and storytelling.
Descriptive statistical analysis.
Advanced table formatting using kableExtra.
PDF report creation.
Organizing data, code, figures, and rendered outputs for reproducibility.

Author
G Crawford-Gee
McGill University — BIOS640
