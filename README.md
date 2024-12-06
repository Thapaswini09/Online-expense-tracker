Online Expense Tracker


An Online Expense Tracker to help users manage and monitor their expenses efficiently. This project demonstrates a web-based application that utilizes servlets, data access objects (DAO), and other backend functionalities to track and manage expenses.

Features

Add, edit, and delete expenses.
View a summary of expenses.
User authentication and personalized tracking.
Backend integration using DAOs for efficient data handling.


Technologies Used
Programming Language: Java
Backend: Servlets (e.g., DeleteExpenseServlet,.....)
Data Access Layer: DAO Pattern (ExpenseDao, UserDao)
Database: (MySQL)
Frontend: (HTML, CSS, JavaScript)
Server: (Apache Tomcat)


Project Structure

src/
├── dao/
│   ├── ExpenseDao.class        # Handles database operations related to expenses
│   ├── UserDao.class           # Handles database operations related to users
├── servlet/
│   ├── DeleteExpenseServlet.class  # Deletes a user's expense entry
and many...


How to Run
Clone the repository:

git clone https://github.com/yourusername/online-expense-tracker.git
cd online-expense-tracker


Set up the database:
Configure your database connection in the config file.


Deploy the application:
Use a Java-based web server like Apache Tomcat.


Access the application:
Open a web browser and go to http://localhost:8080/online-expense-tracker.
