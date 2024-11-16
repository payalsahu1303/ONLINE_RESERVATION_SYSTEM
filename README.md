# Online Reservation System  

## Project Overview  
The Online Reservation System is a Java-based desktop application designed to simplify and manage reservation operations. It allows users to make, view, and cancel reservations efficiently. The system includes a login mechanism and offers an intuitive user interface with functionalities for reservation and cancellation, ensuring a seamless booking experience.  

## Features  
- User login system with credential validation.  
- Make a reservation with detailed input fields (e.g., train name, class type, date of journey, source, destination).  
- Generate a unique PNR for each reservation.  
- Cancel reservations using the PNR.  
- Administered via a database backend for user and reservation management.  

## Technologies Used  
- **Java**: For application logic and GUI.  
- **MySQL**: For backend database management.  
- **JDBC (Java Database Connectivity)**: For connecting the application to the database.  
- **Swing**: For the graphical user interface.  

## Installation Instructions  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/payalsahu1303/ONLINE_RESERVATION_SYSTEM.git 
2. Set up the MySQL database:
   - Create a database named online_reservation_system.
   - Import the provided SQL script to initialize the database with required tables.
3. Configure the database connection in the code:
   - Update username and password in the setupDatabase() method.
4. Compile the Java files using an IDE or command line.
5. Run the application.
   
## Usage
1. Launch the application.
2. Log in with valid credentials.
3. Use the main menu to perform the following actions:
   - Make a Reservation: Fill in the required details and generate a PNR for your reservation.
   - Cancel a Reservation: Provide the PNR to cancel an existing reservation.
   - Exit: Close the application.
4. Enjoy an easy-to-use interface for managing reservations.
