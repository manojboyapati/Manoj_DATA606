# Cancellation prediction of Hotel booking

## Introduction 
### Advance reservation systems are extremely beneficial to hotels. This may be both a positive and a terrible thing for hotels. The good news is that hotels are currently receiving more reservations than usual as a result of the convenience of booking. The bad news is that, due to the present competitive market, hotels must offer a simple cancellation policy for visitors. This makes it difficult for hotels to evaluate real demand and predict demand. Reservations are cancelled at a rate of 24% on average. Cancellations have an impact on the hotel's revenue since they lose prospective revenue consumers who do not cancel.
## Research questions

1. Which months have higher and lower reservations

2 Which day in a week has more reservations

3 Source of reservation

4 What is the average stay of a customer 
## Dataset
No. of rows – 36,275

No. of columns – 19

Total number of values - 689,225

### This dataset has no null values, which is quite unusual for a dataset in the actual world. I requested this dataset from Microtel BWI; the absence of null values might be due to this dataset being given over by Wyndham's data management team.

## Features
0   Booking_ID                    - object 

 1   no_of_adults                 - int64  
 
 2   no_of_children               - int64  
 
 3   no_of_weekend_nights         - int64  
 
 4   no_of_week_nights            - int64  
 
 5   type_of_meal_plan            - object 
 
 6   required_car_parking_space   - int64  
 
 7   room_type_reserved           - object 
 
 8   lead_time                  - int64  
 
 9   arrival_year               - int64  
 
 10  arrival_month               -  int64 
 
 11  arrival_date                -  int64  
 
 12  market_segment_type         -  object 
 
 13  repeated_guest              -  int64 
 
 14  no_of_previous_cancellations - int64 
 
 15  no_of_previous_bookings_not_canceled - int64 
 
 16  avg_price_per_room           -  float64
 
 17  no_of_special_requests       -   int64 
 
 18  booking_status                -  object 
## Classification Models

1.Logistic Regression

2.Random Forest

3.Gradient Boosting

4.Decession Tree

## Outcome
### The main objective of this project is to develop a model that identifies reservations that are more likely to be cancelled.
