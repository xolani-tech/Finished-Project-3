# Circuit Central E-Commerce Platform
Circuit Central is an e-commerce platform specializing in high-quality second-hand computers. This platform enables users to browse, purchase, and manage orders efficiently.
![HomePage](https://github.com/xolani-tech/Finished-Project-3/blob/3322d227e856654fc706b95d4e60e675bd586334/project_demo/Screenshot%202025-04-10%20135359.png)

# :flying_disc: Technologies Used
PHP (Backend)
XAMPP (Development Environment)
HTML, CSS (Frontend Structure & Styling)
JavaScript (Interactive Features)
XAMPP (Database Management)

# :bulb: KEY FEATURES
This e-commerce website implements the following key features:

* **User Login and Registration:** Secure user registration and login functionality.
* **Admin Panel:** manages users, products, and orders.
* **Shopping Cart and Order Process:** A functional shopping cart allowing users to add, modify, and checkout with their selected items.
* **Payment System Integration:**Secure Checkout Process
* **My Account Page:** 
* for Order History & Details
* Product Listings with Detailed Descriptions
* Promotions & Discounts Page
* Responsive UI for Various Devices
* Secure Payment Integration
* Search & Filter Functionality
* **Overall System Integration (Front-end and Back-end):** Seamless communication and data flow between the user interface and the server-side logic.

## Setup Instructions
# HOW TO USE?

Follow these steps to run the ReflectaHome website on your local development environment:

1.  **Prerequisites:**
    * Ensure you have PHP and MySQL installed, or  use XAMPP, which provides both.
    * Start XAMPP:
Open XAMPP Control Panel and start the Apache & MySQL Server.
    * Create Database :
The schema file for database setup is located at database/circuit_central.sql.
    * Open phpMyAdmin, create a database named circuit_central, and import the circuit_central.sql file.
    * Project Placement
If using XAMPP, place the downloaded folder inside htdocs.
    * Ensure the directory structure is: C:\xampp\htdocs\CircuitCentral\ with index.php inside.
    * Run the Application
Open a browser and visit: http://localhost/CircuitCentral

2.  **Clone the Repository:**
    ```bash
    git clone [repository URL]
    cd [repository name]
    ```

3.  **Install Dependencies (if using Composer):**
    ```bash
    composer install
    ```

4.  **Database Setup:**
    * Create a new database named `database` in your MySQL server.
    * Import the database schema from the provided SQL file (`database/database.sql` - if applicable). You can do this using a MySQL client (like phpMyAdmin or MySQL Workbench) or the command line:
        ```bash
        mysql -u [your_mysql_username] -p database < database/database.sql
        ```
    * Configure the database connection details in your PHP configuration file (e.g., `config.php`, `.env`):
        ```php
        <?php
        // Example configuration
        define('DB_HOST', 'localhost');
        define('DB_USER', 'your_db_user');
        define('DB_PASS', 'your_db_password');
        define('DB_NAME', 'reflectahome');
        ?>
        ```

6.  **Run the Development Server (Example using PHP's built-in server):**
    ```bash
    php -S localhost:8000 -t public
    ```
    Then, open your web browser and navigate to `http://localhost:8000`.


# :closed_lock_with_key: Default Credentials
|Role                                |Email                                          |Password                          |
-------------------------------------------------------------------------------------------------------------------------
|Admin                               |admin@circuit.comadmin123                      |admin123                          |
|User                                |user@circuit.com                               |user123                           |

## Author

# Names
* Sibabalwe Lingani 
* Xolani Sodam 
* William October.
# Emails
* sibabalwelingani17@gmail.com
* jonathanmicah23@gmail.com 
* jonathanmicah23@gmail.com.
# Git usernames
* Sibabalwelingani7
* xolani-tech
* Spicey-jpg

