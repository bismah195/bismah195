✈️ FlyX Airways – Flight Management System

A console-based Flight Booking & Management System built using C++ with Object-Oriented Programming and file handling for persistent data storage.

🚀 Overview

FlyX Airways is a simulation of a real-world airline system where users can:

* View available flights
* Book tickets
* Cancel bookings
* Manage seat availability

The system also includes admin-controlled flight management and secure input validation.


✨ Features

👤 Passenger Management

* Register passenger details
* Unique ticket ID generation
* Seat class selection (Economy, Business, First Class)
* Automatic price calculation

✈️ Flight Management

* Add new flights (Admin only)
* View all flights with details
* Track available seats in real-time

💳 Booking System

* Book tickets with seat validation
* Cancel tickets with seat recovery
* Prevent overbooking

🔐 Security

* Admin password protection
* Input validation (age, seats, etc.)

💾 Data Persistence

* File handling for storing:

  * Flights
  * Passenger bookings
* Automatic data load/save on program start/exit


🛠️ Technologies Used

* Language: C++
* Concepts:
  * Object-Oriented Programming (OOP)
  * Inheritance & Abstraction
  * File Handling (ifstream / ofstream)
  * Input Validation
* **Tools:** VS Code / Dev-C++


🧠 System Design

* Person → Abstract base class
* Passenger → Derived class
* Flight → Flight details management
* FlightSystem → Core system controller


 📸 Sample Functionalities

* Add flights (Admin)
* Book tickets
* Cancel bookings
* View available seats


 ⚠️ Limitations

* Uses fixed-size arrays (can be improved using vectors)
* Basic file structure (can be split into multiple files)
* Console-based UI


🔮 Future Improvements

🔹 GUI version (Qt / Web-based)
🔹 Database integration (MySQL)
🔹 Advanced search & filtering
🔹 User authentication system


👨‍💻 Author

Bismah Sheikh
GitHub: https://github.com/your-bismah195


⭐ Support

If you like this project, give it a ⭐ and consider contributing!
