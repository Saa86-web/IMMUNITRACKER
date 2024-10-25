# IMMUNITRACKER
Overview
The Immunization Crusader is a database application designed to track the vaccination journey of individuals within communities. It aims to help public health officials and organizations monitor vaccination statuses, ensure timely vaccinations, and promote community health.

Features
Track individuals getting vaccinated.
Record various types of vaccines and their details.
Log vaccination dates and upcoming doses.
Monitor vaccination statuses (e.g., completed, pending).
Store contact information for outreach and follow-up.
Technologies Used
Python
SQLite (for the database)
Getting Started
Prerequisites
Python 3.x
SQLite (included with Python)
Installation
Clone the Repository (or download the files):

bash
Copy code
git clone <repository_url>
cd immunization-crusader
Run the Database Setup Script: Execute the following Python script to create the database and tables:

bash
Copy code
python setup_database.py
Usage
Add an Individual: Use the add_individual function to add a new person to the database.

python
Copy code
add_individual("Jane Smith", 28, "jane@example.com", "Community B", False)
Add a Vaccine: Add a new vaccine type using the add_vaccine function.

python
Copy code
add_vaccine("Flu Vaccine", "Moderna", 1)
Log a Vaccination: Record a vaccination event with add_vaccination.

python
Copy code
add_vaccination(1, 1, "2023-10-01", "2023-11-01")
Track Vaccination Status: Update the vaccination status using add_vaccination_status.

python
Copy code
add_vaccination_status(1, "Pending", "Awaiting second dose.")
Contributing
Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.
For any inquiries or feedback, please contact duboissam65@gmail.com



