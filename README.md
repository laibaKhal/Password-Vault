A simple and secure password manager built with C++, using SQLite for storage and encryption for protecting passwords. The app supports adding, retrieving, editing, and deleting credentials, along with a password generator and master password protection.

 Features

Local SQLite database (vault.db)

AES-based encryption for passwords

Add, view, edit, delete credentials

Master password lock

Password generator (strong random passwords)

Export encrypted backup file

Error handling & validation

⚙ Requirements

Visual Studio (C++ project)

SQLite (sqlite3.c, sqlite3.h)

▶ How to Run

Clone or download the project.

Add sqlite3.c and sqlite3.h to your project.

Build and run in Visual Studio.

Set a master password when starting for the first time.

 Database Schema

site

username

password (encrypted)

notes

 Example
> Add new credential  
Site: Gmail  
Username: laiba123  
Password: ****** (encrypted) # Password-Vault
