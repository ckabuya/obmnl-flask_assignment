# Financial Transaction Recording System

## Overview
This project is a hands-on lab designed to demonstrate the implementation of a CRUD (Create, Read, Update, Delete) application using Flask. The system developed is a financial transaction recording system capable of managing transaction entries through a web interface.
This is part of IBM's Course on Coursera - Developing AI Applications with Python and Flask

## Features
- **Create**: Add new transaction entries with date and amount.
- **Read**: Display a list of all recorded transactions.
- **Update**: Modify existing transaction entries.
- **Delete**: Remove transaction entries from the system.
- **Search**: Search transaction entries from the system based on transaction amounts.

## Application Pages
1. **Transaction Records**: Displays all transactions with options to add, edit, or delete entries.
2. **Add Transaction**: Form to create a new transaction entry.
3. **Edit Transaction**: Form to update an existing transaction entry.

## Installation and Setup
1. **Clone the Repository**:
    ```sh
    git clone https://github.com/ckabuya/obmnl-flask_assignment
    ```
2. **Install Dependencies**:
    ```sh
    pip install -r requirements.txt
    ```
3. **Run the Application**:
    ```sh
    flask run
    ```

## Usage
- Navigate to the homepage to view all transaction records.
- Use the "Add Transaction" button to create a new entry.
- Edit or delete existing entries using the corresponding buttons next to each transaction.

## Conclusion
This project provides a practical example of building a CRUD application with Flask, showcasing the handling of routes, requests, and dynamic HTML templates.
