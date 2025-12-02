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

2. Relationship between airline incidents and fatalities

When evaluating the safety of airlines, we can make a plot showing the relationship between airline incidents and fatalities. It shows that there is a positive linear relationship between the two variables, indicating that the total incidents is positively correlated with total fatilities.
<img width="1222" height="755" alt="image" src="https://github.com/user-attachments/assets/58698cfe-e1cd-4126-b50b-dd3858adb609" />

To make it more specific, we labeled each dot with its corresponding airline companies and used the size of the dots to measure the total number of fatal accidents. In this plot, the bigger the dot is, the more total fatal accidents there are. As we can see, there are some significant outliers, such as China Airlines. It has a low number of total incidents, but a very high (in fact, the highest value in the entire dataset) total fatality. This indicates that some very severe air incidents caused the death of a lot of people in China Airlines' history. The issue of Aeroflot is just the opposite, where there are many incidents, and most of them are not extreme severe.

<img width="1222" height="755" alt="image" src="https://github.com/user-attachments/assets/61078fae-9ed8-43da-9294-df9a3a255ac3" />

Short Conclusion

Overall, we can use this dataset to evaluate the relative safety of the dominating airlines in the world. However, limitations still exist. One thing that is noteworthy is that all the airlines included are Full-service airlines, which only make up part of the airline industry. There are also Low-cost carriers and private jets that meet different demands from the customers. Therefore, using this dataset is unable to lead to a comprehensive conclusion. On the other hand, the latest data from this dataset is from 2014, which is almost 12 years ago from today. This could potentially mean that we will fail to make predictions for times after 2014. Also, there are many emerging airlines that are not included, such as Starlux Airlines from Taiwan (founded in 2018).
