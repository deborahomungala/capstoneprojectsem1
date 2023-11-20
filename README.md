# capstoneprojectsem1
This project a basic implementation of a bus reservation system in C. Here's a breakdown of what it does:

Includes: The code includes standard C libraries like <stdio.h>, <stdlib.h>, and <string.h> for input-output operations, memory allocation, and string manipulation respectively.

Global Variables:

Arrays are declared to store bus routes (ch), passenger names (name), seat numbers (number), and an array for counting available seats (num1).
Variable trno is used to store the selected bus number.
Functions:

main(): The main function contains a menu-driven system that allows users to view available buses, book tickets, cancel bookings, check the status of buses, and exit the system.
bus(): Displays a list of available bus routes.
booking(): Allows users to book tickets by selecting a bus and seat number. It manages seat availability and stores passenger names and seat numbers in files.
name_number(): Records passenger names and seat numbers in files.
read_number() and read_name(): Reads booked seat numbers and passenger names from files respectively.
status() and status_1(): Display the status of booked and available seats for a specific bus.
cancel(): Cancels a booked ticket by removing the passenger name and seat number from the file.
Login Functionality:

The login() function asks for a username and password to access the system.
This program maintains bus seat bookings by storing passenger details and seat numbers in separate files for each bus.
