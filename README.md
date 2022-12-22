# EDA-Hotel-Booking-Analysis

- Introduction
- Problem Statement
- Objective
- Project Files
- Approach
- Data Analysis
- Solution to Business Objective
- Conclusion

# Introduction:

Hotel Bookings Analysis project consists with the real - world data record of hotel bookings of a city hotel and a resort hotel for the period 2015 - 2017 respectively. The project data record consists of information such as type of hotel booked, average daily rate, booking details, arrival date, length of the stay, the number of adults, children, and / or babies booked, customer country, meal preferences, type of the customer, parking space details, reservation status, channels used for booking, booking cancellation details, booking lead time details, among other details.

# Problem Statement:
This data set contains booking information for a city hotel and a resort hotel and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. We need to find out the some insites which help to stake holders

# Objective:

- To identify the best time to book a hotel.
- To identify most common customer type.
- To find the most preferred length of stay in each hotel.
- To understand the peak season.
- To know the meal preferences.
- Identify which hotel has highest bookings cancellation.
- Find which country customers have highest bookings.
- Study the relation between ADR and length of stay.
- Most prepered Distrubution chanel for bookings.

# Project Files:

Executable File: All theexecutions and data analysis is performed in Python using Google's cloud platform Colaboratory, https://colab.research.google.com/drive/1YEKAEEp7RCfziizvqm-l_puI5A8z9moP?usp=sharing this file contains data analysis, exploration, visualisations and conclusion. Data File: The repository contains the CSV file, which has hotel bookings data.

# Approach:

1. Understanding the business case.
2. Importing relevant Python libraries and dataset.
3. Data inspection and cleaning.
4. Performing Exploratory Data Analysis to identify factors govern hotel bookings.
5. Document insights and conclusions drawn deom data analysis

# Data Analysis:

- Data Analysis of hotel bookings is done in order to answer the business objectives. The analysis is carried our in 3 steps:

# Univariate Analysis:

- In this analysis, we use the data of one variable to analyze the pattern in it.In this project, we have done analysis on:

1. Most preferred meal type by the customers.
2. Bookings percentage of each hotel.
3. Most preferred distribution channel for hotel bookings.
4. Most bookings from customer origin country.

# Bivariate Analysis:

- In this analysis,we use the data of two variables to analyze the relationship between them. In this project,we have done analysis on:

1. To find most preferred length of stay in each hotel.
2. To identify which room type is in most demand and which room type generate the highest adr.
3. Study the relation between Waiting time and Booking cancellation

# Correlation Analysis:
In this analysis, we have performed correlation heatmap to understand correlation on variables. Correlation analysis computes the level of change in one variable due  to the change in the other. In this dataset, we have performed correlation analysis using a correlation heatmap with the variables, 'lead_time', 'adr', 'total_guests', 'total_stays_in_nights', 'previous_cancellations', 'booking_changes', 'days_in_waiting_list', 'required_car_parking_spaces', 'total_of_special_requests' and 'previous_bookings_not_canceled

# Solution to Business Objective

 i.   Anyone is thinking to start new Hotel business can opt to city hotel over to resort hotel as they get more cutomers.

ii.  As Most customers prefer Bread & Breakfast (BB) meal , Hotels can give some attractive deal on upon choosing this BB type meal which will hepl to attract more customers.
 
iii.  August is the busiest month followed by july interms of number of visitors in this case hotel owner can make his team ready to give optimum service to customer and can also encash this high demand of hotel rooms to make more profit Hotel owners can give exlusive offers at low demand time to atract more number of customers to ensure his business to run steadily.

iv.  Most visiotors are from Portugal and other European contries so its better to hotel managment to enusre that facilities according to their requirment also can do good marketing at that contries to enhance business.

v.  Roomtype A is the most demanded rooms by the customer while booking, whereas room types H,G,C are generating more adr respectively Hotel management sholud try to increase room types A, to ensure no customer is missed because of unavialability of specific type of rooms. as room type H generating more revenue can give some addon facility to for H type room in order atracts more customer for this specific room type.

vi.  We saw more number of bookings are done by using distrubution chanel TA/TO where Hotel has to share its revenue in terms of comisssion The hotel management can offer discounts, complimentary services and offers on direct bookings as the hotel doesn’t pay commissions to third parties and maintains a direct relationship with the customer when a customer books the hotel directly.

vii.  Most preferred stay in hotels is 3 days, hotel management should introduce loyalty service, offers, tourism package in order to increase the stay of customers and to generate more revenue.

# Conclusion

1. August and July are the busiest month in terms of hotel busniness so we can anticipate high rates of hotel rooms, where Junary is slack season we can expect lower  2. rates for hotel rooms
3. Most of the bookings are for City Hotel compared to Resort Hotel .
4. Most customers prefer Bread & Breakfast (BB) meal
5. Most preferred distribution channel by customers is Travel Agent / Tour Oprator (TA/TO) to make hotel booking.
6. Most of the customers are from Portugal.
7. Most preferred stay in hotels is 3 days
8. Cancelation and confirmation frequency lies between waiting time range 0-150 days so we can conclude that cancellation has no relation with waiting time.
