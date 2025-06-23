# Smart-Service-Manager

📌 Project Title

    Smart Service Manager – A Modular Python CLI (Command Line Interface) Application


💡 Skills Takeaway from This Project
        
         Python Scripting
         Object-Oriented Programming
         File Handling (JSON/CSV)
         Email Automation (smtplib, yagmail)
         CLI Interface Development
         Modular Coding & Documentation
         Unit Testing (optional: pytest)

🧭 Domain
        
        Enterprise Automation / Service Operations

🧭 Problem Statement
        
        Design and develop a menu-based Python CLI application that manages service operations using modular programming principles. The system must support:

                    1. Creating and managing customer records
                    2. Logging and tracking support tickets
3. Generating service summary reports
4. Sending email alerts for overdue or critical tickets
5. Providing a unified CLI dashboard for user interaction
The system will be built using OOP principles, with individual modules owned and developed by different contributors, and integrated via a shared GitHub workflow.
🧭 Approach
1. CLI Interface with Menu System
The dashboard will serve as a navigation panel to access all modules:
 Manage Customers
 Manage Tickets
 Generate Reports
 Send Alerts
 Exit
Each option routes to a separate Python class/module using imports and function calls.
2. Customer Data Management
 Uses classes to define Customer entities.
 Stores customer data in a JSON file.
 Supports CRUD operations (Create, Read, Update, Delete).
 Search by ID or email.
3. Service Ticket Tracker
 Define a Ticket class linked to a customer.
 Stores ticket info: issue, date, status, priority.
 Track ticket updates and status transitions.
 Stores data in CSV or JSON format.
4. Email Notification Module
 Sends email reminders for open/overdue tickets.
 Uses smtplib or yagmail for secure email handling.
 Schedules and triggers alerts using Python logic.
5. Reporting Module
 Reads customer and ticket data.
 Calculates: open tickets per customer, resolution stats, top issues.
 Optional: Use pandas for easier CSV handling.
 Exports summary to CSV.
6. Integration Dashboard
 One CLI file to tie all modules.
 Uses try-except and user-friendly prompts.
 Maintains logs or status messages.
🛠️ Technology Stack
 Language: Python 3.9+
 Editor: VS Code
 Version Control: Git + GitHub
 File Types: JSON, CSV
 Optional Libraries:
o pandas
o yagmail
o inquirer or rich for CLI UX
 Testing: pytest (optional)
