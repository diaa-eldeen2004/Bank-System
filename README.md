🏦 C++ Banking System
This project is a console-based banking system developed in C++, designed to simulate basic banking operations for both admins and clients. It uses file-based storage (Clients data.txt) to persist user data and transactions.

🔧 Features
👨‍💼 Admin Panel
Login with a predefined admin account

Add new clients

Update client information

Display all registered clients

Search for a client by account number

Display VIP clients (based on balance)

Load existing data from file

👤 Client Panel
Login using username and password

View account balance

Deposit and withdraw money

💾 Data Storage
All client data is saved in a text file (Clients data.txt)

Supports persistent data across sessions

🌟 VIP Client Detection
Clients with a balance above a specific threshold are marked as VIPs and can be displayed separately

🛠 Built With
C++ (OOP principles)

Standard I/O and file handling libraries

📂 File Structure
main() calls Client::displaymenu() to start the app

All logic is contained within the Client class

Admin and client interactions are handled via terminal prompts

📌 Note
This project is ideal for beginners in C++ who want to practice:

File handling

Object-oriented programming

Simple data management
