# Personal-Dataset-Project-Chunyi-Quan-MATH-144
Airline Safety Analysis

Introduction

For my personal dataset, I decided to focus on analyzing airline safety. Apart from land routes and railways, air traffic is one of the most popular and dominating transportation in the world, especially for long-distance and international travel. Therefore, airline safety becomes the most important indicator for customers booking flights for their travels. In this project, we will use the ‘airline-safety’ dataset, which includes available seat kilometers flown each week, the total number of incidents, the total number of fatal accidents, and the total number of fatalities from 1985 to 2014, to evaluate the safety of the world’s major airlines today.

Data Processing

In this dataset, I did not remove the rows and columns with 0 because these are indications of zero flight accidents, which is an important parameter to evaluate the total level of safety for different airlines. On top of the dataset, I created three new columns (fatal_accidents_total, incident_total, and fatalities_total) to combine the separated columns for the period 1985-1999 and 2000-2014. Therefore, we can investigate the differences in two equally long periods and overall flight safety.

Exploratory Analysis

1. What are the airlines with the most available seats?

To rank the availability of seats, I first get the top 20 airlines with descending values in the column of avail_seat_km_per_week, then made a horizontal box plot to show the number of available seat kilometers per week of each airline. As we can see from this graph, United ranked first place, then Delta, and American. All three top airlines in this indicator are from the US, and they are significantly larger than the other airlines with lower rankings. Also, another interesting observation is that, in the top 20 airlines, most of the companies originate in North America and Europe. There are fewer airlines from Asia and the Middle East, but the size is not comparable.

(I used AI to help me improve my code. For example, to make the bar plots appearto be horizontal.)

<img width="1222" height="755" alt="image" src="https://github.com/user-attachments/assets/f02374bc-0c45-4997-bf2e-b615f68722ae" />

