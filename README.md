# R Clinical Data Wrangling
Basic data wrangling skills applied to fake clinical trial data using R.

![Screenshot 2024-11-16 at 5 (4)](https://github.com/user-attachments/assets/c9b3a620-bb3b-4833-bde4-5fade9c87dbf)

## Overview

This R Markdown document aims to show basic data wrangling skills applied to fake clinical trial data. This serves as an example of real-world clinical data wrangling, based on a simplified dataset that has a similar structure to what can be found in data extraction files of EDC systems to implement the eCRF of clincial phase l-lV clinical trials. 

## Data

This example is based on an excel file ('fake-clinical-data.xlsx') that is made up of fake clinical data of 20 subjects and 40 varibles, structured across five excel sheets. In a real clinical trial, these files are significantly larger, include more subjects, variables, and sheets, in some cases including thousands of rows per sheet and dozens of sheets. They can also be found in .xlsx or .csv file formats, depending on the EDC platform implemented. 

## Objective

Every clinical trial will be different, depending on it's primary and secondary objectives, variables, treatments implemented, clinical tests, and other eCRF considerations. 

In this example, the goal is to take the previously mentioned excel file, load the different sheets into R as dataframes, explore, and transform the data into a new dataframe that includes the variables of interest, simplifying statistical analysis, data review, and descriptive analysis of the data and it's use by technical and non-technical users involved in the clinical trial. 

## RMarkdown (PDF)
https://github.com/sebasquirarte/R-Clinical-Data-Wrangling/blob/main/clinical-data-wrangling.pdf
