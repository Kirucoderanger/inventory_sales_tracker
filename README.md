🧾 Inventory and Sales Tracker
A Python desktop application for managing inventory and tracking sales, built using Tkinter for the GUI and SQLite for data persistence. The app includes features like product search, sales and restocking entries, date filtering, and exporting reports in CSV or PDF formats.

📦 Features
📋 Product inventory management

➕ Add / Restock items

💰 Record sales with date and quantity

🔍 Search products by name or ID

📅 Filter sales by date range

📤 Export sales reports to CSV and PDF

💾 Local data storage using SQLite

🛠 Tech Stack
Language: Python

GUI: Tkinter

Database: SQLite

PDF Export: ReportLab

CSV Export: Python CSV module

🚀 Getting Started
Prerequisites
Ensure you have Python 3 installed.
Install dependencies:

bash
Copy
Edit
pip install reportlab
Run the Application
bash
Copy
Edit
python app.py
Replace app.py with your actual main file name if different.

📁 Project Structure
java
Copy
Edit
inventory-tracker/
├── app.py
├── database/
│   └── inventory.db
├── modules/
│   ├── inventory.py
│   ├── sales.py
│   └── utils.py
├── exports/
│   ├── report.pdf
│   └── report.csv
└── README.md
📸 Screenshots
Add screenshots here to demonstrate key features and UI (optional but recommended).

💡 Future Improvements
Authentication for secure access

Charts for sales trends

Multi-user support

Dark mode theme

📜 License
This project is licensed under the MIT License.