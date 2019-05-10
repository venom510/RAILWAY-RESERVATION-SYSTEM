# RAILWAY-RESERVATION-SYSTEM
This is a dbms project for railway ticket reservation system.
It contains 6 tables - user_info, passenger_info, train, station, timings, ticket.
It contains 4 triggers and 3 sequences.
## Tables
### user_info
contains information of users.
### passenger_info 
contains information of passengers and the user_id with which seat is being booked for that passenger.
### train
information about train and the type of seats in the train (three types of seats - 1,2,3) 
and also about the availabilty of different types of seats in a train, e.g. no_A1 - tells number of available seats of type 1,no_B1 - 
tells number of booked seats of type 1, no_W1 - tells number of seats in waiting of type 1. Similarly there are other 6 columns for type 2 and type 3.
### station
conatins information about stations.
### timings
contains information about which train stops at which station and timing of arrival and departure at a station.
### ticket
information about the ticket.
## Triggers
##### For updating the number of different type of seats in a train when a seat is being booked and also set the status of current seat as booked or waiting according to available seats.
##### For updating the number of seats when a ticket is cancelled.
##### For validating the mail_id entered by user.
##### For calculating age of user using his/her date of birth.
#### Sequences for generating user_id, passenger_id and pnr_no for a passenger.
