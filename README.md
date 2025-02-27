# Long Drive - Car Rental System in Python

**Long Drive** is a simple car rental system developed in Python. It includes basic CRUD operations, a user-friendly graphical interface created with Qt Designer, and uses SQLite 3 for data storage. This project is designed to manage car rentals efficiently, allowing users to perform operations such as adding, updating, deleting, and viewing car and customer information.

---

## Features

- **CRUD Operations**: Perform Create, Read, Update, and Delete operations for car and customer records.
- **Graphical User Interface (GUI)**: Intuitive and user-friendly interface built with Qt Designer.
- **SQLite 3 Database**: Lightweight and integrated database to store car and rental transaction information.
- **Car Management**: Add, update, and remove cars from the system.
- **Customer Management**: Manage customer information, including name, license number, and contact details.
- **Rental Transactions**: Track car rentals, including rental dates, return dates, and associated costs.

---

## Technologies Used

### Python
- Core logic of the system developed in Python.
- Utilizes the `sqlite3` module for database interaction.
- PyQt5 for integrating the Qt Designer interface.

### Qt Designer
- Visual design tool for creating the user interface.
- Provides a drag-and-drop interface for designing windows, buttons, and other UI components.

### SQLite 3
- Embedded database for storing car, customer, and rental information.
- Lightweight and easy to set up.

---

## Screenshots

| Login Screen | Main Dashboard | Car Management |
|--------------|----------------|----------------|
| ![Login Screen](https://github.com/viniciusmecosta/car-rental_python/assets/127689653/e9207df2-4cba-436a-b6fd-00d135425908) | ![Main Dashboard](https://github.com/viniciusmecosta/car-rental_python/assets/127689653/24095d28-ea0a-47e8-a472-7f1b693b70e9) | ![Car Management](https://github.com/viniciusmecosta/car-rental_python/assets/127689653/98b19591-6a2a-40dd-a3dd-afea3467037e) |

| Customer Management | Rental Transactions | Database View |
|---------------------|---------------------|---------------|
| ![Customer Management](https://github.com/viniciusmecosta/car-rental_python/assets/127689653/48a4b875-c426-47f3-9206-b5fc4401f3a8) | ![Rental Transactions](https://github.com/viniciusmecosta/car-rental_python/assets/127689653/a940206d-aaac-4b1a-9f86-1b7d2c4b4904) | ![Database View](https://github.com/viniciusmecosta/car-rental_python/assets/127689653/d2816916-f667-4e40-b281-fdd2f8b01f6c) |

---

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/viniciusmecosta/car-rental_python.git
   cd car-rental_python
   ```

2. **Set up a virtual environment (optional but recommended)**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**:
   ```bash
   python main.py
   ```

---

## Usage

### Login:
- Use the login screen to access the system. Default credentials can be found in the database.

### Manage Cars:
- Add, update, or remove cars from the system.
- View available cars and their rental status.

### Manage Customers:
- Add or update customer information.
- View customer details and rental history.

### Rental Transactions:
- Rent a car to a customer and track rental details.
- Calculate rental costs based on the number of days and additional fees.

### Database Management:
- View and edit the database directly from the application.