# DSA210 Term Project
Zeynep Su Yaşar 30694

# Project Idea
This is my Data Science (DSA 210 - Introduction to Data Science) term project for the fall term 2024-2025. In this project, what I aim to explore is the relationship between my menstrual cycle and physical activity, specifically my daily step count. The objective is to determine if there are any patterns or correlations between my menstrual cycle days and the count of steps. By doing this, I will understand if my physical activity levels vary during different phases of my cycle. This will provide some insights into my personalized health strategies and plans. Additionally, I will examine both datasets' basic statistics in detail. We'll also look at their internal patterns and structures.

# Dataset
The menstrual cycle data was collected from Apple’s Health Application as a CSV file. This dataset indicates whether a menstrual cycle occurred on a specific date, represented as a binary value. As the dataset includes some unnecessary columns, it will be parsed only to include the dates and the binary values. The “Dates” column indicates the date the data was recorded. The “Cycle Yes/No” column is a binary indicator where 1 represents a menstrual cycle day and 0 represents a non-cycle day. This data contains daily records from 2020 to the present.
The step count data was also retrieved from Apple’s Health Application as a CSV file. The “Dates” column indicates the date the step count was recorded, and the “Step Count” column indicates the total number of steps taken on the corresponding day. This dataset also includes daily records from 2020 to the present.

# Plan
Data Cleaning and Preparation:
Cleaning the step count and menstrual cycle datasets is the first step. In this step, missing or duplicate values will be addressed if there are any. The date column will align the datasets, ensuring proper merging for analysis. Any inconsistencies in data formatting, such as incorrect date formats or missing records, will also be resolved.

Correlation Analysis:
The relationship between step counts and menstrual cycle days will be examined through correlation analysis. The analysis will explore whether there are significant differences in activity levels across various phases of the menstrual cycle.

Exploratory Data Analysis (EDA) and Visualization:
In this part, we will focus on the trends and patterns within the datasets. Descriptive statistics, such as averages, minimums, and maximums, will be calculated for both datasets to provide a summary of their distributions. An initial hypothesis can be formed with these findings. H0 and H1 will be formed. Step counts during menstrual and non-menstrual days will be visualized. This visualization will be done by using line charts, box plots, and histograms to identify the differences. It will play a crucial role in understanding the relationship between my menstrual cycle and step count. 

Machine Learning:
I'll attempt to use machine learning techniques to examine the connection between step counts and menstrual cycle phases. Using the step count, I will try to determine if a particular day is a menstrual cycle day (1) or a non-menstrual day (0).

