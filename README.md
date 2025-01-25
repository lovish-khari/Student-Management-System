## Project Demonstration
![Project](https://vimeo.com/1050328928?share=copy)

# Student Management System

This is a desktop application built with Python that utilizes the Tkinter library for the graphical user interface (GUI) and MySQL for backend data storage. The application is designed to manage student report cards, allowing users to perform various operations such as adding, editing, deleting, and searching for student records.

## Features
- **Add New Student Entries**: Users can add new student records to the `report_card` table in the MySQL database.
- **Edit Existing Records**: Users can edit student records based on admission numbers.
- **Delete Student Records**: Users can delete student records from the database.
- **Search for Student Records**: Users can search for student records using various criteria.
- **Import Data from Excel**: Users can import student data from Excel files into the database.
- **Generate Report Cards**: Users can generate report cards for students.

## Setup Instructions
1. Ensure you have Python installed on your machine.
2. Install the required libraries:
   ```bash
   pip install mysql-connector-python openpyxl pillow
   ```
3. Set up a MySQL database and create a table named `report_card` with the appropriate fields.
4. Update the MySQL connection details in the `main.py` file:
   ```python
   mydb = mysql.connector.connect(user='your_username', password='your_password', host='localhost', database='your_database')
   ```
5. Run the application:
   ```bash
   python main.py
   ```

## Security Considerations
- Ensure that SQL queries are parameterized to prevent SQL injection attacks.
- Regularly update your MySQL user credentials and restrict access to the database.

## Author
- Lovish Khari
- Email: lovishkhari6411@gmail.com
