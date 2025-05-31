
🏌️‍♀️ Golfer & Club Management System
This is a console-based Golf Management System written in C++ that manages golfer and golf club records. It allows users to register, view, search, and update data for golfers and clubs, with persistent storage using binary files.

✨ Features
Golfer Management
Register new golfers with:

ID

Name

Phone

Age

Ranking

Handicap

Club name

Search golfers by:

ID

Name

Handicap

Ranking

Update golfer information (name, password, age, phone, ranking, handicap, club name)

Display all golfers

Club Management
Register new clubs with:

ID

Name

Location

Password

Email

Rating

Member count

Search clubs by:

ID

Name

Location

Rating

Update club information (name, password, location, rating, email)

Display all clubs

Authentication
Login system for golfers and clubs using ID and password

Allows users to access and manage their own data

Persistent Storage
Uses binary file I/O (golfer.dat and club.dat) to store and retrieve data

Menu-Driven Interface
Easy-to-navigate menus with options for adding, searching, modifying, and displaying data

🛠️ Technical Highlights
Object-Oriented Design:
Encapsulates data and methods in golfer and club classes

Binary File I/O:
Reads and writes objects to files for persistent storage

User Input:
Reads input from the console using cin

String Handling:
Uses strcpy() and strcmpi() for string operations

🚨 Limitations
Uses outdated Turbo C++ libraries (<conio.h>, clrscr(), getch())—may need modernization for newer compilers

Passwords stored in plain text—no encryption

Minimal error handling for file corruption or invalid input

Console-based interface only (no GUI)

📂 Typical Use Case
Register a new golfer or club

Login with ID and password

Search, view, or update your details

Display lists of all registered golfers or clubs

📝 Summary
This project demonstrates fundamental file I/O, class design, and console-based UI skills. It’s a complete system that simulates managing golfers and clubs, complete with registration, login, search, update, and reporting features.

🚀 Getting Started
Compile and run the program in a C++ environment that supports <conio.h> and binary file I/O (e.g. Turbo C++ or DOSBox with Turbo C++). For modern compilers, you may need to update or remove clrscr() and getch() calls.

👩‍💻 Author
Ananya Barthakur
LinkedIn | GitHub
