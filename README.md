ADA Class Project

Description Of The Project:

This is a data analysis project for the class focusing on the analysis of the survey data
The project involves working with a dataset from a GitHub repository titled "Class 1 Survey Fall 2024". 
The project involves;

Data Importation: The survey data is imported from a GitHub link and loaded into a data frame named “C1Survey”.
Basic Data Exploration: The project calculates the number of observations (survey respondents) and the number of variables (survey questions).
Renaming Variables: Column names are renamed to more descriptive and concise labels.
Data Type Exploration: The code aims to identify the types of variables in the dataset i.e. (factors, integers, numeric, or characters).

Description Of The Code:

Setup: The document sets up the environment using “knitr:opts_chunk$set(echo = TRUE)”  to control code chunk options.
Data Import: 
“C1Survey <- read.csv("https://raw.githubusercontent.com/kijohnson/ADA-2024/main/Class%201%20(Getting%20started%20and%20RR%20I)/Lab/Class%201%20Survey%20Fall%202024_di.csv")”
The code imports the survey data directly from the provided URL.
Renaming Columns: 
names(C1Survey)[1:27]<-c("id", "like_cats", "like_dogs", "have_desert", "slogan",
"fav_day", "larkORowl", "fav_food", "fav_drink", "fav_season", "fav_month", "hobby",
"program", "specialization", "stat_software", "R_exp", "coding_comfort", "coding_length",
"top_three","public_health_interest", "fav_num", "bday", "bmonth", "country", "state",
"city", "highest_educ_level")   The dataset's columns are renamed for easier interpretation.

Description Of The Dataset:

The dataset is a survey with responses from various individuals from different disciplines attending the Advanced Data Analysis course. It includes various questions related to preference, personality, and demographic information. The dataset captures both qualitative and quantitative responses
