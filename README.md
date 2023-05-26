# ProgrammingAssignment
2nd_Assignment_(IntroToBusinessProgramming)_Javed_Ramjaun
Description
This project focuses on extracting, cleaning, analyzing and visualizing email data from a SQLite database. The aim is to extract useful insights such as the most frequent email senders and receivers, and the distribution of emails sent per day.

Getting Started
Dependencies
This project requires Python 3 and the following Python libraries installed:

Pandas
SQLite3
Matplotlib
Seaborn
Files
data_extraction.py: This script contains code for extracting data from the SQLite database using SQL queries.
data_cleaning.py: This script contains code for cleaning the extracted data, dealing with missing and inconsistent values.
data_analysis.py: This script contains code for analyzing the cleaned data.
data_visualization.py: This script contains code for visualizing the analyzed data.
Usage
Run data_extraction.py to extract the necessary data from the SQLite database. The output will be a .csv file containing the extracted data.
Run data_cleaning.py on the extracted .csv file to clean the data. The output will be a cleaned .csv file.
Run data_analysis.py on the cleaned .csv file to analyze the data. The output will be a .csv file containing the analyzed data.
Run data_visualization.py on the analyzed .csv file to generate relevant visualizations.
Visualizations
The generated visualizations include:

A line plot showing the number of emails sent per day over time.
A bar chart showing the top 10 email senders in descending order.
A horizontal bar chart showing the top 10 email recipients in descending order.


License
This project is licensed under the MIT License - see the LICENSE.md file for details.
