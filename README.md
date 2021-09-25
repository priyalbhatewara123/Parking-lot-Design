# Parking-lot-Design for N Cars🚗
## 📌 Problem Statement
We own a parking lot that can hold up to ‘n’ cars at any given point in time. Each slot is given a number starting at one increasing with increasing distance from the entry point in steps of one. We want to create an automated ticketing system that allows our customers to use our parking lot without human intervention.
When a car enters the parking lot, we want to have a ticket issued to the driver. The ticket issuing process includes:- 
1. We are taking note of the number written on the vehicle registration plate and the age of the driver of the car.
2. And we are allocating an available parking slot to the car before actually handing over a ticket to the driver (we assume that our customers are kind enough to always park in the slots allocated to them).

The customer should be allocated a parking slot that is nearest to the entry. At the exit, the customer returns the ticket, marking the slot they were using as being available.
Due to government regulation, the system should provide us with the ability to find out:-
* Vehicle Registration numbers for all cars which are parked by the driver of a certain age,
* Slot number in which a car with a given vehicle registration plate is parked. 
* Slot numbers of all slots where cars of drivers of a particular age are parked.

We get the input by reading input.txt directly (you’ll have to create it in your environment) .The file will contain a set of commands separated by a newline, we need to execute the commands in order and produce output.

## 📌 Sample Input
Create_parking_lot 6

Park KA-01-HH-1234 driver_age 21

Park PB-01-HH-1234 driver_age 21

Slot_numbers_for_driver_of_age 21

Park PB-01-TG-2341 driver_age 40

Slot_number_for_car_with_number PB-01-HH-1234

Leave 2

Park HR-29-TG-3098 driver_age 39

Vehicle_registration_number_for_driver_of_age 18

## 📌 Sample Output
Created parking of 6 slots

Car with vehicle registration number "KA-01-HH-1234" has been parked at slot number 1

Car with vehicle registration number "PB-01-HH-1234" has been parked at slot number 2

1,2

Car with vehicle registration number "PB-01-TG-2341" has been parked at slot number 3

2

Slot number 2 vacated, the car with vehicle registration number "PB-01-HH-1234" left the space, the driver of the car was of age 21

Car with vehicle registration number "HR-29-TG-3098" has been parked at slot number 2

## 📌 Code files Structure
* main.cpp file is from where we read input and prints the output to console after executing each command.
* ParkingLot.h file acts as a header file where the classes are defined for further usage.
* ParkingLot.cpp is the cpp file where the entire logic for all the methods is given and explained .

## 📌 How to run the code on Repit ⁉
1. Go to this [link](https://replit.com/join/wkyuzitoop-priyalbhatewara)
2. Click on Run button at the top of the page.
3. Type  ***./a.out***  on Console and hit enter.
4. You'll see the ouput on the console.
5. To give different input, type the commands in input.txt




### Happy Coding!❤
