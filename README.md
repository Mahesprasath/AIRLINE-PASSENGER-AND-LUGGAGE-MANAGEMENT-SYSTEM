# Airline Passenger and Luggage Management System

## Overview
The **Airline Passenger and Luggage Management System** is a C++ application designed to streamline the management of airline passengers and their luggage. The system allows users to enter passenger details, check luggage contents, and manage different passenger classes, providing additional services for business class passengers.


## Features

- **Passenger Class Selection**: At the start, the program prompts users to select a passenger type—either Business or Economy. Based on this selection, the system allocates privileges such as extra food and baggage limits for business class passengers.

- **Passenger Details Input**: The application collects essential passenger information, including:
  - Seat Number
  - Ticket Number
  - Gender
  - Name
  - Nationality

- **Cuisine Management**: The system utilizes a vector to store various cuisine names, allowing users to choose their meals based on availability.

- **Baggage Content Verification**: The application checks the contents of the passenger's bag, alerting users if any toxic items are detected, ensuring safety and compliance with airline regulations.

- **Passenger ID Generation**: Upon successful entry of passenger details, the system randomly generates a unique passenger ID. Users have the option to change passenger details if needed.

- **Detail Checking**: Passengers can check their details by entering the generated passenger ID. The system validates the ID and displays the relevant information. 

- **Manager Access**: For managerial oversight, the application includes a secure access feature. Managers can enter a password ("iammanager") to access the complete database of passengers and their details.

## Technical Implementation

- **Object-Oriented Programming (OOP)**: The project employs key OOP principles:
  - **Polymorphism**: Function overriding is utilized to provide specific functionalities for different passenger types.
  - **Inheritance**: Multiple inheritance is used to manage relationships between different classes within the system.

- **Standard Template Library (STL)**: The application makes use of STL containers like `vector` for dynamic data storage and `map` for efficient data retrieval.

## Usage
To use the system, compile the C++ code and run the executable. Follow the on-screen prompts to enter passenger details, check luggage contents, and manage passenger information. 

## Future Enhancements
- User interface improvements for better interaction.
- Database integration for persistent data storage.
- Advanced security measures for sensitive information.

## Conclusion
The **Airline Passenger and Luggage Management System** demonstrates the application of C++ programming principles and techniques in a practical, real-world scenario. This project aims to improve efficiency in airline management processes while ensuring passenger safety and comfort.
