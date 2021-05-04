Ford GoBike Trips Data Investigations

Project Description
Data set under exploration include a part of information about a bike-sharing system that covering the greater San Francisco Bay area for a period of one month starting from the 1st of February 2019.The dataset covers data such as
• Trip Duration (seconds)
• Start Time and Date
• End Time and Date
• Start Station ID, Name, Latitude, and Longitude
• End Station ID, Name, Latitude, and Longitude
• Bike ID
• User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
• Member Year of Birth
• Member Gender.
• Bike Share for all Trip (Bike Share program for low-income residents)

This project intends to study statistics distributions of the number of trips (count) along the period under investigations in this project. Another target in this investigation is to elucidate and detect variable(s) that may affect the trip duration of the users. Factors such as the age of the user, gender and/or user type are expected to be the most influential variables that may control the number and duration of the trips.

Prequisties:
Before running the codes, you will need to install these:
•	Anaconda
•	Python (Minimum 3)
•	Pandas
•	Numpy
•	Matplotlib
•	Seaborn
•	
Python Notebook and Scripts
Project 3 Ford GoBike analysis.ipynb- Main project file, a IPython Notebook that contains the analysis for the project. 
Project 3 Ford GoBike presentation.ipynb - This IPython Notebook contains starter cells to help organize the slide deck deliverable.

Data Exploration
In this part, we address the main questions that needed to be examined. Here are some questions under invistigations:
1.	When are most trips taken in terms of the time of day or day of the month?
2.	How long does the average trip take?
3.	Does User Type (Subscriber or Customer) affect the duration?
4.	Do Age and gender of the user affect the duration?
5.	Which time of the day/ month affects the duration?
We have utilised different types of characterisations and visualisations tools in our analysis.

Summary of Findings:
In brief, we have studied the Ford GoBike dataset, which includes a part of information about a bike-sharing system covering the greater San Francisco Bay area for a period of one month starting from the 1st of February 2019. After performing analysis, we have the following findings:

1.	Distributions of the trips along the day hour show two prominent peaks at 8 AM and 5 PM, confirming that the bike share system is busiest during rush hours. For the days of the month, we found that users ride more on workdays, whilst during the weekends, the number of trips falls down. There is an irregularity in the data of some days, which can be attributed to holidays or disturbances in the weather on such days.

2.	Most of the bikes rides are taken low time durations, and very few are taken long durations. The mean value of all duration is about 11.23 minutes, which reinforces the idea that the bikes are often used for short trips. Indeed, 75% of the rides are below 13 minutes, and 50% are below 8 minutes, with the most extended trip is 1409 minutes and the shortest being one minute.

3.	Males represent most users who use the go bike service with a percentage of 74.59%, and after those, females and other genders come with percentages of 23,32% and 2.08%, respectively. The most important result here is that a remarkable percentage of the other genders users spend more time on their trips than males and females for trip durations <50 minutes. For trip durations (>200 minutes), the females and males appear to have similar ride averages, whilst the other genders are barely there.

4.	For all genders, about 50% of users ages range from 27 to 39 years old, with a mean age of approximately 34.19. Further, most of the most extended trips took by users in the age range from 18-30.

5.	Most Ford GoBike users are subscribers (90.53 % of total users) who use the service. However, the customers representing only 9.47 % of the total users spend more time on their trips than the subscriber. Also, the subscribers appear to use the bike on weekdays, but the customer's usage concentrates more on the next half of the month.

6.	For Bike Share program members, the majority of users spend less time on their trips than regular users. Further, there is no remarkable change in the distribution of the bike Share members along the month days, which may be because this program is directed to low-income residents. And so most of them may not have a fixed job.

