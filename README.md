# Fraud-Analysis-Project-2

## Supervised Fraud Classification on Application Data
- Start with a DQR
- Clean: treat the frivolous fields (SSN, Address, Phone, DOB)
- Create all variables
- Scale all variables (typically z scale)
- Separate data into modeling/Out of Time (OOT)
- Use the modeling data (trn,tst) for feature selection
- Select 20 – 30 best variables
- Build a baseline linear model (logistic regression)
- Build several nonlinear models, tune parameters (neural net, boosted trees (try a few different versions), random forest
- For each ML model, start with minimum complexity. Increase complexity until you observe overfitting
- Select your favorite model, fine tune the parameters
- Build the final performance tables with your final, best model
- Write report

## Repositiory File description

Project report - Contains the full description of the project
Feaure Engineering - Python Jupyter notebook containing the full code with proper comments.
DQR (Data Quality Report) - Contains the data visualisations and initial analysis of data for fully understanding the given data.
DQR code - Contains the python code for data quality report.

## Dataset Description

Dataset Name: Applications Data Description: This dataset contains the information of the people who filled their applications for a product. It contains fields like Social security number, name, address, phone no., and date of birth. It also contains a fraud label field which tells whether the application is good or bad. Time Period: 1 January 2016 – 31 December 2016 No. of Fields: 10 No. of Records: 1,000,000 Size of Dataset file: 83 MB


