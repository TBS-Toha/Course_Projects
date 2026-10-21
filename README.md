# Python-Based Ticket Booking System

A console-based ticket booking system developed using Python for a Data Structures and Algorithms (DSA) lab project. The system manages booking requests, passenger information, seat reservations, and payment verification through an interactive menu.

## Features

- Add and manage passenger booking requests
- Process a selected booking request from the queue
- Display available and booked seats
- Book seats from a 40-seat layout (10 rows × 4 columns)
- Display all booked tickets
- Search tickets by passenger name or ID
- Simulate payment verification using bKash, Nagad, Rocket, or hand cash
- Validate seat numbers and prevent duplicate seat bookings

## Data Structures Used

- Queue: Stores pending booking requests.
- Singly Linked List: Maintains booked ticket records.
- Matrix: Represents the 10 × 4 seat layout.

## Technologies

- Python 3

## Project Structure

```text
Project2/
├── Project2.py
└── README.md
```

## Requirements

- Python 3 installed on your computer
- A terminal or code editor, such as VS Code

No external Python packages are required.

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/TBS-Toha/Course_Projects.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Course_Projects/DSA_Projects/Project2
   ```

3. Run the program:

   ```bash
   python Project2.py
   ```

   On Windows, you can also use:

   ```powershell
   py Project2.py
   ```

## Menu Options

| Option | Description |
|---|---|
| 1 | Add a booking request |
| 2 | View and choose a pending request to process |
| 3 | Display all booked tickets |
| 4 | Search tickets by passenger name or ID |
| 5 | Show the seat layout |
| 6 | Exit the program |

## Payment Verification

The system provides simulated payment options:

- bKash
- Nagad
- Rocket
- Hand Cash

This is an educational simulation. It does not connect to real payment services or verify actual financial transactions.

## Learning Objectives

- Understand the implementation of queues and linked lists.
- Apply data structures to a real-world-inspired booking scenario.
- Practice searching, insertion, and deletion operations.
- Implement seat management and input validation.
- Develop a menu-driven Python application.

## Limitations

- Booking information is stored in memory and is lost when the program exits.
- Payment verification is simulated.
- The system supports a maximum of 40 booked seats.

## Author

TBS-Toha

## License

This project is intended for educational and academic purposes.
