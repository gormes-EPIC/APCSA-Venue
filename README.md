
# 2D Array Walkthrough Activity: Concert Seating

A new class `Venue` represents a new concert venue in the area. The venue has one instance variable `seating` which is a 2D integer array. In the array a "1" represents a seat that is already taken and "0" represents a seat that is available. The venue also has an instance variable `price` which represents the ticket price. 

1. Create a class `Venue` with instance variables `seating` and `price`. Add a constructor that takes two integers representing the number of rows and the number of columns of the seats and one double representing the ticket price. 

A new class `VenueRunner` contains your main method. 

2. Create a new venue with seats organized into 15 rows of 10 seats each and a ticket price of 15. 

In `Venue`, create a method `fillSeats()` which has a String variable as a parameter representing the filename where the ticket information is stored. 

3. Create `fillSeats` and run it on `tickets.txt` to populate your `seating` array.

`tickets.txt`
```
0,1
0,2
0,5
0,6
0,9
1,0
1,3
1,4
1,7
1,9
2,0
2,1
2,3
2,6
3,2
3,4
3,7
3,8
4,0
4,3
4,4
4,5
4,9
5,1
5,2
5,4
5,6
5,7
6,0
6,2
6,5
6,7
6,8
6,9
7,1
7,3
7,5
7,9
8,0
8,3
8,4
8,8
9,2
9,4
9,5
9,6
10,0
10,2
10,4
10,6
10,7
11,1
11,2
11,4
11,5
11,8
12,0
12,1
12,3
12,7
12,8
12,9
13,2
13,3
13,5
13,8
14,0
14,4
14,6
14,9
```

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


