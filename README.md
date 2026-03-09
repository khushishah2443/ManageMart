# ManageMart 🛒

**A comprehensive Supermarket Management System designed to streamline inventory tracking, billing, and customer management.**

ManageMart is a robust desktop/web application that simplifies the day-to-day operations of a retail store. It allows administrators to manage stock, generate invoices in real-time, and analyze sales performance through an intuitive interface.

---

## 🚀 Features

* **📦 Inventory Management:** Add, update, and delete product details (ID, Name, Quantity, Price, Category).
* **🧾 Billing System:** Automated invoice generation with tax calculation and discount handling.
* **🔐 User Authentication:** Secure login for Admins (manage stock) and Cashiers (billing only).
* **📊 Sales Reporting:** Generate daily/monthly sales reports to track revenue.
* **📉 Low Stock Alerts:** Visual indicators when product inventory falls below a certain threshold.
* **🔍 Product Search:** Fast search functionality by Product ID or Name.

---

## 🛠️ Tech Stack

* **Frontend/UI:** Java (Swing/JavaFX) 
* **Backend:** Java, SQL
* **Database:** MySQL 
* **Tools:** NetBeans

---

## 💾 Database Schema

The system uses a relational database to ensure data integrity. Key tables include:

1.  **Users:** Stores Admin and Cashier credentials.
2.  **Products:** Stores Item ID, Name, Category, Quantity, and Price per unit.
3.  **Sales:** Records transaction history with timestamps.

---

## 🛠️ Installation & Setup

Follow these steps to run the project locally.

### Prerequisites
* [Java JDK](https://www.oracle.com/java/technologies/downloads/) 
* [MySQL Server](https://dev.mysql.com/downloads/installer/)

### Steps

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/candelatesla/ManageMart.git](https://github.com/candelatesla/ManageMart.git)
    cd ManageMart
    ```

2.  **Database Setup**
    * Open your SQL Workbench (e.g., MySQL Workbench).
    * Create a database named `managemart_db`.
    * Import the `database.sql` file provided in this repository to create tables and dummy data.

3.  **Configure Connection**
    * Open the source code (e.g., `Connection.java` or `db_config.py`).
    * Update the `username` and `password` to match your local SQL configuration.

4.  **Run the Application**
    ```bash
    # If using Java
    javac Main.java
    java Main

    # If using Python
    python main.py
    ```

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

```bash
# 1. Fork the Project
# 2. Create your Feature Branch
git checkout -b feature/AmazingFeature

# 3. Commit your Changes
git commit -m 'Add some AmazingFeature'

# 4. Push to the Branch
git push origin feature/AmazingFeature

# 5. Open a Pull Request
```
-----

## 🔗 Connect

<p align="left">
<a href="https://www.linkedin.com/in/shahkhushi9" target="blank"><img align="center" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Yash Doshi" /></a>
<a href="mailto:khushi.shah@tamu.edu"><img align="center" src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>
