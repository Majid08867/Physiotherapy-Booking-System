# Physiotherapy Booking System 

A Java-based console application for managing appointments in a physiotherapy clinic. This system allows users to register patients, book or modify appointments, mark treatments as attended, generate reports, and more — all via a user-friendly menu-driven interface.

## Features Implemented

1. **Add Patient** – Register new patients with name, address, and contact details.  
2. **Remove Patient** – Delete a patient’s record from the system.  
3. **Book Appointment** – Schedule treatments with selected patients and physiotherapists.  
4. **Modify Appointment** – Edit existing appointment details such as date or time.  
5. **Attend Appointment** – Mark an appointment as attended and update treatment status.  
6. **Print Report** – Generate summary reports of treatments, bookings, and patients.  
7. **Exit System** – Safely exit the program.

## Technologies Used

- Java 17
- VS Code with Java Extension Pack
- JUnit 5 for testing
- Git & GitHub for version control

## Unit Testing

All core functionalities were unit tested using JUnit. Tests cover:
- Booking logic
- Cancelation rules
- Double-booking failure handling
- Adding treatments to physiotherapists
- Verifying patient-treatment links

## How to Run

1. Clone the repository:
git clone https://github.com/Majid08867/Physiotherapy-Booking-System.git

markdown
Copy
Edit

2. Open the project in **Visual Studio Code**

3. Make sure Java 17 and JUnit 5 are configured

4. Run the program using the green **Run** button above the `main` method

5. To run tests, right-click on `BookingSystemTest.java` → **Run Tests**
