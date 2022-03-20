






























# EDA-hotel_booking_analysisHotel booking analysis
 
 
 
     Manmohan Madhu
     Dhanraj
     D.N Raghavendra
                        
 
 
 
 
 
 
 
 
 
 
 
ABSTRACT :
Hotel booking analysis data has booking 
information for Resort hotels and a go for city 
hotels and includes information such as when 
the booking was made, length of Stay, the 
number of adults, boys and girls, and or 
babies, and the number of available parking 
spaces, among other things. All personally 
making out information 3 has been taken away 
from the data. We will do exploratory data 
analysis able to get the power of seeing from 
the data. The data has been taken with a 
comparison of resort hotels and city hotels 
which people prefer the most in it. Exploratory 
data analysis has been done on hotel booking 
analysis with python.
Hotel booking analysis, information for a city hotel and a resort hotel and it includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has from the data.
We will perform exploratory data analysis
Introduction:
     Hotels have become a part of our life every day we use this book online system so, it has become closer to customers this may be done on manual bookings and also even in online system .this made hotel bookings became closer to every person. As we use the Internet, which has made our living society closer for each and everything we are using some hotel tourism apps also like make my trip,goibibo made easy to boo and cancellation part much easier way so that even elders above 60 years also easily can use. Hotels booking is one making a journey for pleasure agent  which provides the facilities for booking hotels, events, travelers, houses, holiday apartments and other accommodations ' for persons getting support or goods. They operate their business in Resorts or top-class Hotels for their business meetings. Any customers need to book hotel, or rooms in another's house they need to go to their office which is for checking the ability to use as well as business discussion. lately, they have decided to change their booking pattern  from manual  to an online system. It will help them to manage the customers booking easily and also to keep the customer's data safer. It will also help staff to keep in track  their person getting support or goods' online request as well as easy to answer take-back to the guest or customers.
 
  
 
 
 
 
 
 
 
 
 
 
 
Problem statement
   As hotels booking has a manual  booking system, they are facing some problems issuing booking requests of persons getting support or goods. All the necessary bookings put tightly into, made full of are being done in hard copy. so it  becomes much hard for staff to keep the records brought up to the current state all the time. For example, if the customers need to change the check-in time-stamp it becomes hard for them to get out the customer booking details for bringing up to the current state as there are so many customers booking records. Again, regarding the current system customers can not give take-back online, and also working groups can not answer to them promptly. in addition, persons making a journey for pleasure from others  need to name directly for booking purposes. So they cannot get the chance to view their rooms in another's house rooms or hotels rooms before they make a book.
 
hotels booking is a one-making journey for pleasure agent  which provides facilities for booking hotels, events, travels, houses, holidays enjoyment and other accommodations ' for persons getting support or goods. they operate their business in KSA Any customers need to book the hotel or rooms in another's house they need to go to their office which for checking the ability to use as well on basis of discussion. lately, they have  decided to change their booking pattern from manual  to the online system. It will help them to manage the customers booking easily and also to keep the customer data safer will also help staffs to keep it safer will also help staffs to keep in track  their person getting support or goods' online booking request as well as easy to answer take-back to the customer or Guests.
 
 
We will try to answer the following Questions
The optimal length of stay in order to get the best daily rate?
What is the booking ratio between Resort Hotel and City Hotel?
What is the percentage of booking for each year?
Which is the busiest month for hotels?
From which country do most guests come?
 
      
           
 
Exploratory data analysis of Hotel Booking analysis: 
Tools and libraries
analyzing the data
selecting the data
 
 
 
                                                                                                                                We have answered the following questions:
How Many Bookings Were Cancelled?
What is the booking ratio between Resort Hotel and City Hotel?
What is the percentage of booking for each year?
Which is the busiest month for a hotel?
From which country do most guests come?
How Long Do People Stay in the hotel?
Which was the most booked accommodation type (Single, Couple, Family)?
what is the percentage of Hotels in the market segment?
 
                                                                                                                                
                                                                          
Tools and Libraries Used
We have used Python 3 to its following packages:
 
        1. Pandas
        2. Matplotlib
3. Seaborn
4. NumPy
 Python code, documentation and visualization
 
 
 
          
 
 
 
 
 
 
 
 
 
 
 
Hotel_bookings.csv: Our dataset file has 119390 rows and 32 columns
Dataset file contains the following features:
hotel
is_canceled
lead_time
arrival_date_year
arrival_date_month
arrival_date_week_number
arrival_date_day_of_month
stays_in_weekend_nights
stays_in_week_nights
adults
children
babies
meal
country
market_segment
distribution_channel
is_repeated_guest
previous_cancellations
previous_bookings_not_canceled
reserved_room_type
assigned_room_type
booking_changes
deposit_type
agent
company
days_in_waiting_list
customer_type
adr
required_car_parking_spaces
total_of_special_requests
reservation_status
reservation_status_date
 
 
 
 
 
 
 
 
 
 
 
 
Result
We learned that
Almost 35% of bookings were canceled.
More than 60% of the population booked the City hotel.
More than double bookings were made in 2016, compared to the previous year. But the bookings decreased by almost 15% next year.
Most bookings were made from July to August. And the least bookings were made at the start and end of the year.
Portugal, the UK, France, Spain, and Germany are the top countries from most guests come, more than 80% come from these 5 countries.
Most people stay for one, two, or three. -> For Resort hotels, the most popular stay duration is three, two, one, and four days respectively. -> For City hotels, the most popular stay duration is one, two, seven(week), and three respectively
A couple (or 2 adults) is the most popular accommodation type. So hotels can make arrangement plans accordingly
 
 
 
Summary:
              City hotels value 2/3s of all booking, go to for help hotels value for 1/3.about 50% of all booking are canceled showed the highest rate of hotel booking. (data  from 2015-2017)The highest daily rates occurred in the summer (June, July, and August) more bookings occurred on weekdays vs weekends. Most people book with children or babies booked at places gone for pleasure at the highest rate. United Kingdom, France, and Portugal booked the most hotel Stays worldwide. The majority of hotel bookings booking-bookings booking did not have to need a deposit. Most bookings came from Independent, transient guests or customers are 90% of bookings were not profitable.
              
 
 
                                                                                                                                                    
 
Discussion:                                                                                                                                                                                                                                                                       
 
 Analysis of this knowledge unit highlights a few key take-aways First, there is a disproportionate value of crossing-outs on hotel booking (~50%). bookers are not                                   needed to send in a change in the most booking which could give an account of the upper rate of crossing-outs. There are increasingly booking on week-days, this data suggests that hotel business of a trader could be got more out of by selecting working journeyers or getting more out of daily rates for week-days. Although places went to for pleasure only value for 1/3 of all booking, they compete for town hotels when there is food and drink in the booking group. go to for help hotels could target young families with these knowledge customers looking for a safe, family atmosphere. Europe has an upper value of journeyers that put letters together for printing both go to for help and town hotels. European business of a trader representatively has increasingly a time of rest from work time resting from work time for workers and warlike marketing operations could be made in this region to control this market. go to for help hotels have a sloping sharply rise in price during used in exchange for payment summer time divisions, having knowledge of this information town hotels would possibly lift their daily rate (So long as they are not taking part in a competition against each other). lastly, most bookings came from self-supporting journeyers and there is an important low rate of profit (<10%). hotels should take efforts to make up to the day relationships with customers or target past guests for profit Stays.
 
 

   
 
