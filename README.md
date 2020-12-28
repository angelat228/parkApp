# parkApp

Registration:
If you are a new user, you need to register. There are required fields like name, surname, username and password. 
MainActivity:
The activity where you can log in with your username and password. 
DBHelper: 
Class for connecting with the database, where are defined the tables and the neccessary methods.
Cities:
Activity where is defined the list of cities available for parking. Actually a RecyclerView, connected with a adapter and  the database of course.
Reservation:
Here is also shown  a landscape layour, beside the one for a portrait mode. You can easily choose the date and the time for your parking reservation. 
ResFrag1:
Here we have the datePicker
ResFrag2:
Time spinner 
ParkingPlaces:
Activity where is defined the list of parkings. For every item of the RecyclerView it has defined green and red button for free and taken parking places. 
Confirmation:
A confirmation form, defined through two layouts.
MyReservations:
Contains the max 3 activities per user. 
