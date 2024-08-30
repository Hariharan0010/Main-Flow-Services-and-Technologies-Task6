# Main Flow Services And Technology-Internship-Jupyter-Lab-TASK-06

#  Restaurant Management System Billing Software Application

## Overview

This repository contains the code and documentation for Task 6 of my Python Developer internship at **Main Flow Services and Technologies**. The task involved developing a billing software application with a user-friendly graphical user interface (GUI) using Python. The application manages customer transactions, generates invoices, and tracks sales, handling everything from product details and pricing to customer information.

## Project Description

The goal of this task was to create a comprehensive billing software application that can be used by businesses to manage their billing processes efficiently. The application features a GUI built with Tkinter and includes forms for product entry, customer details, billing, and invoice generation. The application also includes a database to store and manage all the relevant information.

## Learning Objectives

- **Environment Setup:** Install and configure Python and necessary libraries (e.g., Tkinter for GUI).
- **Database Design:** Create a database schema to store product, customer, and transaction details.
- **GUI Design and Development:** Develop an intuitive and user-friendly interface for the application, including all necessary forms and controls.

## Tools and Technologies

- **Python 3.x**
- **Tkinter (for GUI)**
- **SQLite (for database management)**
## API Key Website
To get the API You need to sign up the website to get the own API for free https://www.fast2sms.com

## How to Run the Application

### Prerequisites

Ensure that Python 3.x is installed on your machine. The following Python libraries are required:

- Tkinter (usually included with Python)
- SQLite (comes with Python)
- Any additional libraries specified in `requirements.txt`

You can install any additional required libraries using pip:

```bash
pip install -r requirements.txt
```

### Running the Application

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Dj-gamer007/billing-software.git
   cd billing-software/src
   ```

2. **Run the Application:**

   ```bash
   python main.py
   ```

3. **Using the Application:**

   - **Product Entry:** Add new products with details such as name, price, and SKU.
   - **Customer Details:** Input customer information to create new transactions.
   - **Billing and Invoices:** Generate and print invoices based on customer transactions.
   - **Sales Tracking:** Track all sales made through the application.

## Example Code Snippet

Here’s a small snippet demonstrating how the application handles billing:

```python
def calculate_total(products):
    total = 0
    for product in products:
        total += product['price'] * product['quantity']
    return total

def generate_invoice(customer, products):
    total = calculate_total(products)
    invoice = f"Customer: {customer['name']}\nTotal: ${total:.2f}\n"
    # Additional invoice formatting and printing logic
    return invoice
```

## Features

- **User-Friendly Interface:** Intuitive GUI for managing all aspects of billing.
- **Product and Customer Management:** Easily add and update product and customer information.
- **Invoice Generation:** Generate, view, and print invoices for customer transactions.
- **Sales Tracking:** Maintain records of all sales made through the software.
