# Capstone_1_Flight_Delays
Capstone project to predict delays in flights. 

# Project Proposal
Airline customers are constantly being surprised by delays and cancellations. If they new how likely a flight was to be delayed
before they left for the airport, or even before they booked, they may be able to plan better, or be less upset when their 
flight is delayed. With this project I’d like to find trends as to what causes a flight to be delayed, and determine whether 
certain factors about previous flights can help predict whether or not a flight will be delayed. 

The client for this project is an airline. They can use this analysis to alert customers of potential delays early, and even 
possibly prevent future delays. Another potential client would be travel agents and companies that sell airline tickets, they 
can suggest flights for their clients based on how likely a flight is to get delayed (for example, if a certain afternoon 
flight is often delayed, maybe suggest an earlier flight to their client). 

I will be using data from kaggle.com, found here for this project. It contains flight information from 2015, along with airline
and airport information in the form of csv files.

To solve this problem, I plan on manipulating the table to connect flights with the flight that was directly before them. Using
that data, along with the data already provided in the table on delay times and reasons, I’ll find the most common delay 
reasons and determine whether previous flights have any bearing on whether a future flight (by the same plane on the same day) 
will be delayed. Then, using linear regression on a training set of the data, I’ll see if I can predict whether a flight in a 
testing set will be delayed.    

All code will be publicly listed on github in a jupyter notebook. The project will be presented at office hours, or an uploaded
recorded presentation will be posted when complete. 
