
# SkyReserve: Airplane Ticket Reservation System

SkyReserve is a console-based airline ticket reservation system built in C++ that enables users to:
- Enter and manage customer details.
- Book flights across multiple international destinations.
- Generate and display tickets with flight details and charges.

The application uses standard C++ libraries for I/O operations and file handling to simulate a real-world ticket booking system.

## Features

- **Customer Management:**  
  Capture customer information such as ID, name, age, address, and gender.

- **Flight Registration:**  
  Book flights to destinations including Dubai, Canada, UK, USA, Australia, and Europe through an interactive menu.

- **Ticket Generation:**  
  Generate a ticket with the selected flight details and charges, which is then saved to a file (`records.txt`).

## Technologies Used

- **C++**  
  The project is implemented using C++ with standard libraries:
  - `<iostream>`
  - `<fstream>`
  - `<iomanip>`
  - `<cstdlib>`

## Getting Started

### Prerequisites

- A C++ compiler (e.g., `g++`).

### Installation and Running

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/AkshayTiwari27/SkyReserve.git
   cd SkyReserve
   ```

2. **Compile the Code:**

   ```bash
   g++ -o SkyReserve main.cpp
   ```
   *Replace `main.cpp` with your source file name if different.*

3. **Run the Application:**

   ```bash
   ./SkyReserve
   ```

   Follow the on-screen prompts to add customer details, register for flights, and generate tickets.

## Project Structure

```
SkyReserve/
├── main.cpp        # Main source file containing the application code
├── records.txt     # File to store ticket records (generated after booking)
└── README.md       # This file
```

## Usage

Upon running the application, you will be presented with a main menu offering the following options:
- **1:** Add Customer Details  
- **2:** Flight Registration  
- **3:** Generate Ticket and View Charges  
- **4:** Exit

Select an option and follow the interactive prompts to complete your booking.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- Developed as a demonstration of C++ programming and file handling.
- Inspired by real-world airline reservation systems.
