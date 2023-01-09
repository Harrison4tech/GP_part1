# Overview:

The database to be used includes data from:
General Practice Prescribing Data Extract for Wales: This database contains information on what medications GP practices in Wales prescribe. It includes all prescribing results uo to 2015, combined in Wales.

QOF Results for Wales: This is a database of how each GP practice performed according to the Quality and Outcomes framework. It further includes counts of how many people at each practice were diagnosed with certain diseases, as well as some performance measures.

The goal of this script is to design and implement an R program that reports some information. The database hosting these dataset would be queried in SQL and the database would be connected to R for further analysis.

# Project 1: First part analysis of GP Practice in Wales

Allow the user to select a GP practice.
(a) What five drugs does the practice spend the most money on?
(b) What region is this practice in?
(c) How does this practice’s rate of smoking compare to Wales as a whole, as well as other
practices in its region?
(d) Smoking is associated with a number of chronic diseases. Use statistical analysis to show the relationship (if any) between the rate of smoking at practices and the rates of the following diseases: asthma, cancer, coronary heart disease, dementia, hypertension. If you find statistically significant relationships, what disease is most strongly associated with smoking?
(e) Do practices with higher rates of smoking spend more or less on medications?

# Project 2: Health Board Analysis in Wales

(a) What is the total prescriptions from April 2013 to December 2015?
(b) Find out information about the prescription by health boards in Wales
(c) What is the total items prescribed for therapeutic classes
(d) Analyse and visualise the number of items prescribed/percentage time change from the top 2 largest therapeutic classes ('Cardiovascular System' and 'Endrocrine System') between April 2013 and December 2015.
(e) Find the rate of diabetes in all the different local Health Boards in Wales
(f) Find the statistical relationship between the rate of dementia vs the rate of smoking and diabetes
