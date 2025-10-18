PHARMACY MANAGEMENT SYSTEM

“This is a Pharmacy Management System developed in Python using Tkinter for the user interface and SQLite as the database.
It is designed to help small pharmacies maintain their stock, update medicines, handle sales, and manage admin access securely.”

🔹 2. Objectives

Provide a simple and user-friendly interface for pharmacy staff.

Maintain a database of medicines (name, quantity, price).

Support CRUD operations (Create, Read, Update, Delete).

Allow selling of medicines with automatic stock updates.

Ensure security with an admin login system.

🔹 3. Tech Stack

Frontend / GUI → Python Tkinter

Database → SQLite3 (lightweight, file-based database)

Programming Language → Python

Libraries used → tkinter, sqlite3, ttk, messagebox

🔹 4. System Features

Admin Login – Only authenticated users can access the system.

Medicine Management

Add new medicines with name, quantity, and price.

Update details if stock or price changes.

Delete expired/out-of-stock medicines.

Sales Functionality

Sell medicines by reducing stock automatically.

Calculates and shows the total bill amount.

Data Display

All medicines are shown in a Treeview table.

Selecting a row auto-fills fields for easy editing.

User-Friendly GUI

Buttons for Add, Update, Delete, Sell, and Clear.

Search bar (if you implement it) for quick filtering.

🔹 5. Workflow (Demo Explanation)

Step 1: Admin logs in using username & password.

Step 2: Main dashboard opens → shows list of medicines.

Step 3: Admin can add new medicine details.

Step 4: If a customer buys medicine → enter quantity, system reduces stock, and calculates bill.

Step 5: Admin can update or delete records anytime.

🔹 6. Advantages

Easy to use, no complex setup.

Database is stored locally (SQLite).

Reduces manual stock management errors.

Can be extended (e.g., sales history, invoice generation).
