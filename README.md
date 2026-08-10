# Inventory Management System

A professional desktop-based **Inventory Management System** built with **Python and Tkinter**. The application provides a simple and user-friendly interface for managing products, quantities, stock status, and inventory searches.

## Features

* Add new products
* Update product quantities
* Delete products
* Search products
* Display current inventory
* Show product stock status
* Low-stock identification
* Out-of-stock identification
* Inventory summary
* Input validation
* Confirmation before deleting products
* Professional desktop GUI
* Lightweight and easy to use

## Technologies Used

* **Python**
* **Tkinter**
* **ttk**
* **Dictionary** for inventory data management

## Project Structure

```text
Inventory-Management-System/
│
├── inventory_management_system.py
└── README.md
```

## Application Preview

The application provides a dashboard-style interface with:

* Product Management panel
* Add, update, delete, and clear buttons
* Inventory table
* Product search
* Quantity display
* Stock status
* Inventory summary

## How to Run

### 1. Install Python

Make sure Python 3 is installed on your computer.

Check your Python version:

```bash
python --version
```

### 2. Clone the Repository

```bash
git clone https://github.com/sharmariteshkumar/Inventory-Management.git
```

### 3. Open the Project

```bash
cd Inventory-management
```

### 4. Run the Application

```bash
python Inventory_Management.py
```

## How to Use

### Add Product

1. Enter the product name.
2. Enter the quantity.
3. Click **Add Product**.

### Update Quantity

1. Enter an existing product name.
2. Enter the new quantity.
3. Click **Update Quantity**.

You can also click a product in the inventory table to automatically load its information into the form.

### Delete Product

1. Enter or select a product.
2. Click **Delete Product**.
3. Confirm the deletion.

### Search Product

Use the search box in the Inventory section to quickly filter products.

## Stock Status

The application automatically displays stock status based on quantity:

| Quantity | Status       |
| -------: | ------------ |
|      `0` | Out of Stock |
|  `1 - 5` | Low Stock    |
|     `6+` | In Stock     |

## Sample Products

You can test the application with:

| Product        | Quantity |
| -------------- | -------: |
| Laptop         |       10 |
| Wireless Mouse |       25 |
| Keyboard       |       15 |
| USB Cable      |       30 |
| Headphones     |        8 |

## Data Storage

The current version stores inventory data in a Python dictionary while the application is running.

```python
inventory = {}
```

For a future version, the application can be extended with persistent storage such as:

* JSON
* SQLite
* MySQL
* PostgreSQL

## Future Improvements

Possible enhancements include:

* Persistent database storage
* User login and authentication
* Product categories
* Product prices
* Supplier management
* Stock-in and stock-out transactions
* Automatic inventory reports
* Excel export
* PDF reports
* Barcode scanning
* Dashboard statistics
* Multi-user support

## Purpose

This project is suitable for:

* Python projects
* College assignments
* Beginner desktop application development
* Inventory management demonstrations
* Learning Python GUI development

## License

This project is open-source and available for educational and personal use.

---

**Developed with Python and Tkinter.**
