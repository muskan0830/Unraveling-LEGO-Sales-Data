# Unraveling-LEGO-Sales-Data
This data analyst project aims to analyze data related to LEGO sets, focusing on insights from two main datasets: "lego_sets.csv" and "parent_themes.csv." It encompasses various data analysis tasks that showcase essential skills required for a data analyst job.
(Datasets are sourced from Kaggle)

1. Import Libraries and Read CSV Files:
The project begins with importing the necessary libraries, particularly the Pandas library for data manipulation. The two primary datasets, "lego_sets.csv" and "parent_themes.csv," are loaded for further analysis.

2. Merge Two Files Using `.merge`:
Data from the two datasets is merged based on the common column "parent_theme." This merging process combines information from both datasets and creates a comprehensive dataset for analysis.

3. Calculate Irrelevant Columns Using `.drop`:
Unnecessary or irrelevant columns are identified and removed from the merged dataset. This step streamlines the dataset for further analysis.

4. Start Exploratory Data Analysis (EDA):

a. Percentage of Star Wars Licensed Sets:
In this part of the project, the focus is on licensed LEGO sets. The percentage of sets with a Star Wars theme among all licensed sets is calculated. This helps to understand the popularity of the Star Wars theme among licensed LEGO sets.

b. Group, Change Data Type, Sort, Drop Duplicates, and Find Unpopular Year:
The dataset is grouped by theme and year, and data types are adjusted for accurate analysis. It is then sorted to identify the number of sets each theme has in a given year. Duplicates are removed to find the year when the Star Wars theme was not popular.

5. Find Unique Sets Released Each Year:
A new column is defined to represent unique sets, and it is assigned a value of 1. The data is then grouped by year to count the unique sets. This helps identify the year with the most and least unique sets.

Summary:
This data analyst project involves examining LEGO sets data, parent themes, and licensing. The project highlights several key skills vital for a data analyst job, including data cleaning, merging, filtering, aggregation, and visualization.

The findings from the analysis include the percentage of Star Wars licensed sets, the year when the Star Wars theme was not popular, and the years with the most and least unique sets. These insights demonstrate the ability to extract valuable information from data, make data-driven decisions, and effectively communicate findings.
