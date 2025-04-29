# Sales-Management-System-
This project is a web-based sales management system built using Python (Flask) and SQLite, designed to manage a network of stores with their respective products, customers, employees, and orders. It provides a clean, responsive user interface to perform CRUD operations and generate order summaries per customer.

🚀 Features 🧑 Customer Management Add, edit, view, and delete customer details including name, address, and email.

🧑‍💼 Employee Management Manage employee records and contact information.

🏬 Store Management Maintain a list of stores and assign products to them.

📦 Product Management Track product names, prices, and store associations. Includes price validation.

📋 Order Management Place, edit, and delete customer orders linked to products.

💰 Customer Order Summary View total amount spent and full order history for each customer.

✅ Form Validations

Ensures product price is positive

Validates customer/employee email format

🗃️ Tech Stack Frontend: HTML5, Bootstrap 5, Jinja2

Backend: Python 3, Flask

Database: SQLite (with SQLAlchemy ORM)

🧠 How It Works Each order is linked to a product and a customer

Products are associated with stores

Orders are displayed with price and date, and totals are calculated per customer

Admin users (you!) can manage all records via a clean UI
