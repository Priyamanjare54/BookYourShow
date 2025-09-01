# Movie Ticket Booking System  

This project is a **C++ application integrated with MySQL** to simulate a movie ticket booking system.  
It allows users to reserve seats, view availability, and update reservations in a database.  

##  Features  

###  Database Integration  
- Uses **MySQL** to store seat availability (`Ticket` table).  
- Automatically creates the table if it does not exist.  

###  Seat Reservation  
- Displays a seating chart (5 rows × 10 seats).  
- Reserved seats are marked with **X**, available seats with **-**.  
- Prevents double booking by checking seat status before reserving.  

###  Persistent Data  
- Seat reservations are stored in MySQL.  
- Data remains consistent across multiple runs.  

###  User-Friendly Menu  
- Reserve a ticket.  
- Exit the system.  
