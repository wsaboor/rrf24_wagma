# Reproducible Research Fundamentals 2024 - Stata

Welcome to the **Reproducible Research Fundamentals 2024** training repository. This repository will guide you through all the exercises across the following stages:

- **0. GitHub Workflow**: Gain essential GitHub skills, including how to create branches, commit changes, and open pull requests.
- **1. Data Processing**: Learn to clean and tidy your datasets in preparation for analysis.
- **2. Data Construction**: Build indicators and variables from the processed data.
- **3. Data Analysis**: Conduct analyses using the constructed data.
- **4. Reproducibility Package**: Package all work into a reproducible format for sharing and validation.

Feel free to update this README as you progress through the sessions and customize it to reflect the details of your project. For more details on the elements required for a reproducibility package, refer to our [README template](https://github.com/worldbank/wb-reproducible-research-repository/blob/main/resources/README_Template.md), which you will cover in the **Reproducibility Package** session.

Instructions for Replicators
To replicate the analysis and results, follow these steps:

Download the data:

Place the dataset in the folder: Data/Final.

Set up directory paths:

Update the file paths in the following Stata do-files to match your local directory structure:
main_dofile.do
01_cleaning.do
02_analysis.do

Run the analysis:

Run the main script main_dofile.do to execute all stages of the data analysis and produce the necessary outputs.
List of Exhibits
The following tables and figures are generated from the analysis:

All tables and figures in the report can be reproduced using the provided code.
Exhibit name	Output filename	Script	Note
Table 1: Districts	DistrictTable.xlsx	01_cleaning.do (line 24)	Data/Final
Figure 1: Schools	SchoolPlot.png	02_analysis.do (line 32)	Outputs/figures/
Figure 2: Medical Facilities	MedicalPlot.png	02_analysis.do (line 40)	Outputs/figures/

Code Description
The following do-files are used to complete the analysis:

main_dofile.do: Runs the entire workflow, including data processing, construction, and analysis. This is the primary file to execute.
01_cleaning.do: Handles cleaning of the raw data, addressing missing values, and preparing the dataset for analysis.
02_analysis.do: Contains the statistical analysis, including generating tables and figures for the report.


Additional Notes
All data manipulation and analysis steps are well-documented in the code.
Make sure to have all required software installed and properly set up before running the code.