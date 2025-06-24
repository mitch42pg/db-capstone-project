#  Little Lemon Booking System

This project is part of the final assessment for the Meta Back-End Developer Professional Certificate. It involves building a functional booking system for the fictional restaurant *Little Lemon*, using MySQL, Python, and Tableau.

---

##  Project Structure

- `/sql/LittleLemonDB.sql` — SQL script to create and populate the database
- `/python/booking_procedures.py` — Python scripts for interacting with the database
- `/images/` — Screenshots of the ER diagram, terminal output, and Tableau dashboards
- `/tableau/LittleLemon_Analysis.twbx` — Tableau workbook containing data analysis
- `README.md` — This file

---

##  Tools Used

- **MySQL Workbench** — Database design and data modeling
- **Python (mysql.connector)** — Database procedures and automation
- **Tableau Public** — Data visualization and insights
- **GitHub** — Project version control and submission

---

##  Entity-Relationship (ER) Diagram

![ER Diagram](images/ER_Diagram.png)

---

##  Python Procedures

-  `GetMaxQuantity()` — Finds the highest quantity ordered
-  `ManageBooking()` — Adds, updates, or deletes bookings based on input
-  `UpdateBooking()` — Updates a booking date
-  `AddBooking()` — Adds a new booking for a customer
-  `CancelBooking()` — Removes a booking by ID

**Output Screenshot:**
![Python Terminal](images/Python_Procedure_Execution.png)

---

##  Tableau Reports

Key dashboards include:
- Total Bookings by Date
- Revenue by Menu Item
- Cancellations Trend
- Most Frequent Customers

![Dashboard](images/Tableau_Dashboard.png)

---

##  Insights

- Bookings peak during weekends
- Top menu item: Grilled Salmon
- Booking cancellations increase during holidays
- Top 3 customers account for 42% of bookings

---

##  How to Run

1. Run `LittleLemonDB.sql` in MySQL Workbench
2. Open `booking_procedures.py` and run from your terminal
3. Open `LittleLemon_Analysis.twbx` in Tableau

---

##  Author

Your Name  
GitHub: [YourGitHubProfileLink]  
LinkedIn: [Optional]
