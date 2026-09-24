# KLHB-FED-26-10-18-HOTEL-BOOKING-AND-OCCUPANCY-MANAGEMENT
Project Title - Hotel Booking And Occupancy Management
Team No - KLH/PSPJAVA/T
TEAM MEMBERS NAMES WITH ID NUMBERS -
1.2620030179 - JASWANTH
2.2620030184 - ARUN
SUPERVISORS NAME - DR K.RAJESH 
Abstract - 
The **Hotel Booking and Occupancy Management System** is a Java-based software application developed to facilitate the systematic management of hotel reservations and room occupancy. The primary objective of the system is to automate essential hotel operations, including room availability management, customer registration, reservation processing, check-in and check-out, booking modification, and billing. The application maintains structured records of customers, rooms, and reservations, thereby enabling efficient retrieval and management of information. It provides real-time identification of available, occupied, and reserved rooms, contributing to effective utilization of hotel resources. The system reduces dependence on manual record-keeping and minimizes the possibility of errors associated with conventional management practices. The implementation incorporates fundamental Java programming concepts, including classes and objects, methods, arrays, conditional statements, loops, and user input handling. The proposed system demonstrates the practical application of object-oriented programming principles to a real-world management problem and provides a structured, reliable, and efficient approach to hotel reservation and occupancy management.
Project structure - 
## Project Structure

### 1. Introduction

This section introduces the Hotel Booking and Occupancy Management System, its purpose, significance, and the problems associated with traditional hotel reservation and occupancy management.

### 2. Problem Statement

The project addresses the limitations of manual hotel management, such as maintaining booking records, checking room availability, tracking occupancy, and calculating billing accurately.

### 3. Objectives

* To develop a computerized hotel booking system.
* To maintain customer and room records systematically.
* To provide accurate room availability information.
* To manage check-in and check-out operations.
* To calculate booking costs based on room type and duration.
* To reduce errors associated with manual record management.

### 4. System Requirements

**Software Requirements:**

* Java Development Kit (JDK)
* Java IDE such as IntelliJ IDEA, Eclipse, or VS Code
* Operating System: Windows/macOS/Linux

**Hardware Requirements:**

* Computer/Laptop
* Minimum 4 GB RAM
* Minimum 1 GB available storage

### 5. System Modules

**Module 1 – Customer Management**

* Add customer details
* Store customer information
* Search and display customer records

**Module 2 – Room Management**

* Display room details
* Identify available and occupied rooms
* Manage different room categories

**Module 3 – Booking Management**

* Create new reservations
* Modify booking information
* Cancel reservations
* Assign rooms to customers

**Module 4 – Occupancy Management**

* Track vacant, reserved, and occupied rooms
* Update room status during check-in and check-out
* Monitor overall hotel occupancy

**Module 5 – Billing Management**

* Calculate room charges
* Calculate total cost based on duration
* Generate the final bill

### 6. System Workflow

**Customer Registration → Room Availability Check → Room Selection → Booking Confirmation → Check-in → Occupancy Update → Check-out → Bill Calculation → Room Status Updated**

### 7. Java Concepts Used

* Classes and Objects
* Encapsulation
* Methods
* Arrays
* Conditional Statements
* Loops
* `Scanner` for user input
* Constructors
* Exception Handling
* Basic Object-Oriented Programming principles

### 8. Data Management

The system maintains structured information regarding:

* Customer ID and personal details
* Room number and room type
* Booking ID
* Check-in and check-out details
* Room availability status
* Total booking amount

### 9. Testing

The application is tested using different scenarios, including successful booking, unavailable-room selection, booking cancellation, check-in, check-out, and bill calculation, to verify the correctness and reliability of the system.

### 10. Expected Outcome

The proposed system provides a systematic and efficient approach to hotel reservation and occupancy management. It reduces manual effort, improves information accuracy, and enables efficient monitoring of hotel rooms and bookings.

### 11. Future Scope

The system can be further enhanced by integrating:

* Database connectivity using MySQL
* Graphical User Interface (GUI)
* Online payment facilities
* Email/SMS booking notifications
* User authentication
* Online hotel reservation
* Automated room check out
Execution Instructions -
## Sample Input and Output

### 1. Main Menu

**Output:**

```text
========================================
 HOTEL BOOKING AND OCCUPANCY MANAGEMENT
========================================
1. Add Customer
2. View Available Rooms
3. Book Room
4. View Bookings
5. Check-In
6. Check-Out
7. Generate Bill
8. Exit

Enter your choice: 1
```

### 2. Customer Registration

**Input:**

```text
Enter Customer ID: 101
Enter Customer Name: Rahul
Enter Phone Number: 9876543210
```

**Output:**

```text
Customer registered successfully!
```

### 3. View Available Rooms

**Input:**

```text
Enter your choice: 2
```

**Output:**

```text
Available Rooms:
Room No.    Type          Price/Day
101         Single        Rs. 1500
102         Double        Rs. 2500
103         Deluxe        Rs. 3500
```

### 4. Room Booking

**Input:**

```text
Enter your choice: 3
Enter Customer ID: 101
Enter Room Number: 102
Enter Number of Days: 3
```

**Output:**

```text
Booking confirmed successfully!

Booking Details
------------------------------
Customer ID : 101
Customer Name : Rahul
Room Number : 102
Room Type : Double
Duration : 3 days
Rate/Day : Rs. 2500
Total Amount : Rs. 7500
------------------------------
```

### 5. View Booking Details

**Input:**

```text
Enter your choice: 4
```

**Output:**

```text
Current Bookings:
--------------------------------
Booking ID : B001
Customer ID : 101
Customer Name : Rahul
Room Number : 102
Duration : 3 days
Status : Reserved
--------------------------------
```

### 6. Check-In

**Input:**

```text
Enter your choice: 5
Enter Booking ID: B001
```

**Output:**

```text
Check-in completed successfully!
Room 102 is now occupied.
```

### 7. Check-Out and Bill Generation

**Input:**

```text
Enter your choice: 6
Enter Booking ID: B001
```

**Output:**

```text
Check-out completed successfully.
Room 102 is now available.
```

**Bill:**

```text
================================
           HOTEL BILL
================================
Customer Name : Rahul
Room Number   : 102
Room Type     : Double
Duration      : 3 days
Rate/Day      : Rs. 2500
--------------------------------
Total Amount  : Rs. 7500
================================
Thank you for staying with us!
```

### 8. Invalid Room Booking

**Input:**

```text
Enter your choice: 3
Enter Customer ID: 105
Enter Room Number: 102
```

**Output:**

```text
Room 102 is currently occupied.
Please select another available room.
```

### 9. Exit

**Input:**

```text
Enter your choice: 8
```

**Output:**

```text
Thank you for using the Hotel Booking
and Occupancy Management System!
Program terminated successfully.
```


