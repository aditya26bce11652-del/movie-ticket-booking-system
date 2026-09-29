Movie Ticket Booking System
📌 Project Description
The Movie Ticket Booking System is a console-based Python application designed to manage movie ticket bookings.
The system allows users to view movies, check seat availability, book tickets, calculate ticket prices, cancel bookings, and view booking details.
✨ Features
Display available movies
View movie show timings
View seat layout and seat availability
Book movie tickets
Select multiple seats
Silver and Gold ticket categories
Calculate ticket amount
Apply discount coupons
10% bulk discount for 4 or more seats
5% GST calculation
Generate booking receipts
Cancel bookings
View all bookings
Save booking data in a text file
🛠️ Technologies Used
Python 3
File Handling
Functions
Lists
Dictionaries
Loops
Conditional Statements
Exception Handling
📂 Project Structure
Movie-Ticket-Booking-System/
│
├── main.py
├── README.md
├── .gitignore
└── bookings.txt
bookings.txt is automatically created by the program when bookings are saved.
🎬 Available Movies
ID
Movie
Time
1
Inception (Sci-Fi / Thriller)
10:30 AM
2
Interstellar (Sci-Fi / Drama)
02:00 PM
3
The Dark Knight (Action / Crime)
06:00 PM
4
Avatar: The Way of Water (Adventure)
09:30 PM
💺 Seat Categories
Rows A and B → Silver Seats
Rows C, D and E → Gold Seats
6 seats per row
30 seats per movie
💰 Ticket Prices
Movie
Silver
Gold
Inception
₹150
₹250
Interstellar
₹150
₹250
The Dark Knight
₹150
₹250
Avatar: The Way of Water
₹180
₹280
A 5% GST is added to the ticket amount.
🏷️ Discount
The system supports the coupon code:
CINEMA10
This gives a 10% discount.
A 10% bulk discount is automatically applied when 4 or more seats are booked.
▶️ How to Run
1. Install Python
Make sure Python 3 is installed on your computer.
Check the installation using:
python --version
2. Run the Program
Open the project folder in a terminal and run:
python main.py
📋 Main Menu
The program provides the following options:
1. Display Movies
2. View Seats
3. Book Tickets
4. Cancel Booking
5. Calculate Ticket Amount
6. View Bookings
7. Exit
💾 Data Storage
Booking information is stored in:
bookings.txt
The file is created automatically when a booking is confirmed.
For privacy, do not upload real customer names or phone numbers to a public GitHub repository.
🔮 Future Improvements
Some possible improvements are:
Add a graphical user interface (GUI)
Use MySQL or SQLite database
Add user login and registration
Add online payment
Generate PDF tickets
Add admin panel
Add multiple theatres and screens
Add email or SMS confirmation
👨‍💻 Author
Aditya Raj Tiwari
📄 Purpose
This project is developed for educational purposes to demonstrate Python programming concepts such as functions, file handling, data structures, loops, conditions, and exception handling.
