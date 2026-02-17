# Gpa-Calculator
# Build by using PostgreSQL Database Node.js Sql 

About This Project

This is a web-based GPA Calculator developed using HTML, CSS, JavaScript, Node.js, and a Neon PostgreSQL database.
The system allows users to enter an academic year and view the GPA of all students from that year. It calculates GPA using course credits and grade ranges stored in the database.
This project was developed to practice backend development, SQL querying, and frontend-backend integration.

What This System Does

Accepts a year as input
Fetches all students from that academic year
Converts marks into percentages when required
Assigns grades based on defined ranges
Calculates weighted GPA using course credits
Displays all students with their calculated GPA

The GPA calculation is performed using SQL queries in the backend for accuracy and efficiency.

Technologies Used

HTML
CSS
JavaScript
Node.js
Express.js
Neon PostgreSQL Database
SQL

How the System Works

The frontend runs on http://localhost:5500 using Live Server.

The user enters a year in the input field.

A request is sent to the backend API.

The backend retrieves marks and course data from the Neon database.

GPA is calculated using weighted average based on credits.

The results are returned as JSON.

The frontend displays all students with their GPA.

API Endpoint
GET /gpa/:year


Example:

GET /gpa/2024


The response contains:

Registration Number

Student Name

Academic Year

Calculated GPA

How to Run the Project

Create a Neon PostgreSQL database.

Import the provided SQL file into the database.

Configure your database connection inside db.js.

Install dependencies:

npm install


Start the backend server:

node server.js


Open index.html using Live Server.

The application will run at:

http://localhost:5500


Enter a year to view GPA results.

Future Improvements

Add semester-wise filtering

Add CGPA calculation

Improve frontend UI

Add authentication system


Author

Gotam Ladkani
Software Engineering Student
