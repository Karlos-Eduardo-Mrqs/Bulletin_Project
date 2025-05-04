# Autumn 🍂

## 📁 Table of Contents

- [Autumn 🍂](#autumn-)
  - [📁 Table of Contents](#-table-of-contents)
  - [✨ About the Project](#-about-the-project)
  - [💡 Usage Example](#-usage-example)
  - [🖥️ Technologies Used](#️-technologies-used)
  - [⚙️ Prerequisites](#️-prerequisites)
  - [🛠️ Installation and Configuration](#️-installation-and-configuration)
    - [1⃣ Configure XAMPP](#1⃣-configure-xampp)
    - [2⃣ Set Up the Database](#2⃣-set-up-the-database)
    - [3⃣ Get the Blueprint](#3⃣-get-the-blueprint)
    - [4⃣ Adjust the Settings](#4⃣-adjust-the-settings)
    - [5⃣ Run the Project](#5⃣-run-the-project)
  - [📈 License](#-license)
  - [🎉 Done!](#-done)

---

## ✨ About the Project

Autumn is a school report card system developed to facilitate the management of grades, absences, and student performance. The system allows teachers, coordinators, and administrators to quickly and securely access academic data, promoting transparency and efficiency in the educational process.

---

## 💡 Usage Example

- A teacher accesses the system to record grades for the 3rd quarter.  
- The coordinator generates a consolidated report of the class averages.  
- Parents consult the online report card to track their child's performance.

---

## 🖥️ Technologies Used

- **Front-End:** HTML, CSS, and JavaScript for the user interface.  
- **Back-End:** PHP for data processing.  
- **Database:** MySQL for storing academic information.  
- **Other Tools:** AJAX for asynchronous communication, Bootstrap/Bulma for responsive design.

---

## ⚙️ Prerequisites

Before getting started, ensure you have the following configured:

- **XAMPP Installed:** Required to run the Apache server and MySQL database.  
  ➡️ [Download XAMPP here](https://www.apachefriends.org/index.html)  
- **Reliable Browser:** Chrome, Firefox, or any other browser that allows you to explore the project.

---

## 🛠️ Installation and Configuration

Follow these simple steps to set up Autumn:

### 1⃣ Configure XAMPP

- Install and start XAMPP.
- In the control panel, activate the **Apache** and **MySQL** modules.

### 2⃣ Set Up the Database

- Open phpMyAdmin by navigating to: [http://localhost/phpmyadmin/](http://localhost/phpmyadmin/)  
- Create a database named **autumn** (or any preferred name).  
- Import the file `database/autumn.sql` located in the project folder to create the tables and initial data.

### 3⃣ Get the Blueprint

You can obtain the project in two ways:

- **Cloning the Repository:**

```bash
  git clone https://github.com/your-repository/autumn.git
```

- **Downloading the ZIP:**  
In the project repository, click on **Code > Download ZIP**.
Extract the contents into the `htdocs` folder of your XAMPP installation.

### 4⃣ Adjust the Settings

- Locate the database configuration file (usually in `config/db.php` or similar).  
- Update the credentials to match your local environment.

### 5⃣ Run the Project

- Start the server in XAMPP.  
- Open your browser and navigate to: [http://localhost/autumn](http://localhost/autumn)

---

## 📈 License

This project is licensed under the **MIT License**. See the `LICENSE` file for more details.

---

## 🎉 Done!

You will see the home page of Autumn.