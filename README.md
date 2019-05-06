### Heinz 95-845: Overdose Death Prediction Pipeline (Group 1)

The repository contains csv, LaTeX, docx, pdf, Rmd, and image files relevant to our project. 

Our data files are:

demographic.csv - contains the demographic data for 120,650 individuals

opiate_prescription_fills.csv - contains the prescription fills data for the individuals

program_activity.csv - contains the Allegheny County DHS program usage for the individuals 

The data dictionary is in description_of_files.docx.

The project proposal is the S19-aamlp-projectproposal-group1.pdf. The pertinent LaTeX files are also included. 

Our project code can be found in project_code.Rmd.

Steps to run the code:

Replace the file directory to the directory where you have the data stored. As explained above three data sources (demographic, opiate prescription, and program description) are required for this analysis. Columns have to be named similar to the code as we are doing preprocessing based on column names (not dynamic in nature).

Installation

No need to explicitly install packages for the analysis. The code takes care of the installation of the required packages.

Usage

The code currently split the data into train and test split with 50-50%. Change the split ratio based on the quantity of the data you have. The code is calculating metrics based on a threshold of 0.3. Change threshold to your use case.

Authors 

Lauren Roast, Nikita Setia, Mridul Singh Gangwar

