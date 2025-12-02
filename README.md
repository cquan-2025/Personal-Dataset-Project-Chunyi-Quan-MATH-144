# Personal-Dataset-Project-Chunyi-Quan-MATH-144
Airline Safety Analysis

Introduction

For my personal dataset, I decided to focus on analyzing airline safety. Apart from land routes and railways, air traffic is one of the most popular and dominating transportation in the world, especially for long-distance and international travel. Therefore, airline safety becomes the most important indicator for customers booking flights for their travels. In this project, we will use the ‘airline-safety’ dataset, which includes available seat kilometers flown each week, the total number of incidents, the total number of fatal accidents, and the total number of fatalities from 1985 to 2014, to evaluate the safety of the world’s major airlines today.

Data Processing

In this dataset, I did not remove the rows and columns with 0 because these are indications of zero flight accidents, which is an important parameter to evaluate the total level of safety for different airlines. On top of the dataset, I created three new columns (fatal_accidents_total, incident_total, and fatalities_total) to combine the separated columns for the period 1985-1999 and 2000-2014. Therefore, we can investigate the differences in two equally long periods and overall flight safety.
