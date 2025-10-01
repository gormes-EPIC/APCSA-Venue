
# 2D Array Walkthrough Activity: Concert Seating

A new class `Venue` represents a new concert venue in the area. The venue has one instance variable `seating` which is a 2D integer array. In the array a "1" represents a seat that is already taken and "0" represents a seat that is available. The venue also has an instance variable `price` which represents the ticket price. 

1. Create a class `Venue` with instance variables `seating` and `price`. Add a constructor that takes two integers representing the number of rows and the number of columns of the seats and one double representing the ticket price. 

A new class `VenueRunner` contains your main method. 

2. Create a new venue with seats organized into 15 rows of 10 seats each and a ticket price of 15. 

In `Venue`, create a method `fillSeats()` which has a String variable as a parameter representing the filename where the ticket information is stored. 

3. Create `fillSeats` and run it on `tickets.txt` to populate your `seating` array.


# 2D Array Walkthrough Activity: Concert Seating

A new class `Venue` represents a new concert venue in the area. The venue has one instance variable `seating` which is a 2D integer array. In the array a "1" represents a seat that is already taken and "0" represents a seat that is available. The venue also has an instance variable `price` which represents the ticket price. 

1. Create a class `Venue` with instance variables `seating` and `price`. Add a constructor that takes two integers representing the number of rows and the number of columns of the seats and one double representing the ticket price. 

A new class `VenueRunner` contains your main method. 

2. Create a new venue with seats organized into 15 rows of 10 seats each and a ticket price of 15. 

In `Venue`, create a method `fillSeats()` which has a String variable as a parameter representing the filename where the ticket information is stored. 

3. Create `fillSeats` and run it on `tickets.txt` to populate your `seating` array.

Add a `toString()` method to your class `Venue` which prints out the seating chart and the ticket price.

```
0,1,1,0,0,1,1,0,0,1
1,0,0,1,1,0,0,1,0,1
1,1,0,1,0,0,1,0,0,0
0,0,1,0,1,0,0,1,1,0
1,0,0,1,1,1,0,0,0,1
0,1,1,0,1,0,1,1,0,0
1,0,1,0,0,1,0,1,1,1
0,1,0,1,0,1,0,0,0,1
1,0,0,1,1,0,0,0,1,0
0,0,1,0,1,1,1,0,0,0
1,0,1,0,1,0,1,1,0,0
0,1,1,0,1,1,0,0,1,0
1,1,0,1,0,0,0,1,1,1
0,0,1,1,0,1,0,0,1,0
1,0,0,0,1,0,1,0,0,1

Ticket Price: $15.00
```

4. Create your `toString()` method now then call it on your `Venue` from the `VenueRunner` class.

Write a method that gets the value of a specific row and column of the seating chart. 

5. Create the method and answer the question is the seat at row 7, column 3 taken? 

Create a method inside `Venue` to calculate the number of available seats across the whole venue.

6. Create the method and display the number of empty seats. 

Now create methods inside `Venue` to calculate the number of available seats in a given row and a given column. 

7. Create the two methods, then use them to calculate the number of empty seats in row 1 and column 5. 

Create a method `profits()` which returns the total number of tickets sold times the ticket price

8. Create `profits()` and display the profits for the `Venue`. 

Create another method called `printSpaceSaver()` which prints the seating chart rotated to the left 90 degrees(the rows and columns are flipped).

9. Use the method to print out the `Venue` in column-major order.

Create a method `seatsTogether()` which returns the number of groups of two or more consecutive seats. 

10. Create the method and answer how many groups of two or more seats are open consecutively?

Create a method `seatsTogether()` which returns the number of groups of two or more consecutive seats. 

10. Create the method and answer how many groups of two or more seats are open consecutively?


