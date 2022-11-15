# Exploration of Ford GoBike System Data 
## by Ewurabena Bainson


## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.
The dataset contains 183412 entries of data on these rides. There is information about the user, including their membership status, year of birth, gender, ride duration amongst others.
For this project the dataset was loaded and some column datatypes changed; the start_time and end_time columns were converted from strings to datetime format,and the member birth year was converted to an integer from a float. 
The dataset can be found in the Project workspace.


## Summary of Findings

From the exploratory analysis, I found out that there were more males than female users in this bike-sharing system. There are more subcribers than customers; and this was true for all gender categories. 

I also dicovered that majority of the users were born between the years 1980 to 2000, however there were some users born as early as before 1940 and some after 2000.
As part of my Exploratory Analysis, I wanted to find out if  ride durations were affected by any of the member characteristics or information.
Most rides were under 6000 seconds, with the peak value within  the 0 to 1000 seconds mark.

I found some relationship between the ride duration and member gender. Though it seemed somewhat minute, we notice that there are more females accounting for lower ride duration than the men. The longest ride duration was also by a male.
There is also an correlation between the member's birth year and ride duration. Those born in later years had a long ride durations as opposed to the older generation.

## Key Insights for Presentation

For the presentation, my focus is on the effect of member gender and birth year on ride duration.

First I introduced the dataset and showed the distribution of the ride duration using a histogram with small bin sizes.
For perspective, I also showed the distribution of the mmember gender and member birth years as pie charts.

The relationship between the ride duration and member gender is shown in a violin plot and  a box plot is used to show the relationship between the member birth years and duration of rides.