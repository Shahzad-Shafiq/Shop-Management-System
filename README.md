# Shop-Management-System

This project is a comprehensive billing system implemented in Python using the Tkinter library for the graphical user interface (GUI). It allows users to manage products, create bills for customers, add items to the bill, edit items, delete items, view bills, and generate cash memos. Additionally, the billing system includes a calculator feature accessible from the GUI.

## Features

- **Manage Products**: Users can manage products by adding, editing, and deleting product details such as name, quantity, and unit price.
- **Create Bills**: Users can create bills for customers by entering their details and adding items to the bill.
- **Edit Items**: Items in the bill can be edited to update their details such as quantity or unit price.
- **Delete Items**: Items can be removed from the bill if they are no longer needed.
- **View Bills**: Users can view bills by searching by bill number, customer name, date range, or listing all bills.
- **Generate Cash Memos**: Users can generate cash memos for bills.
- **Calculator**: The system includes a calculator feature accessible from the GUI.

## Implementation

The project is implemented using object-oriented programming (OOP) principles. Key classes include:

- **BillItem**: Represents items in the bill.
- **BillingApp**: Manages the billing application.

Tkinter is used for the GUI, providing menus for different functionalities like managing products, creating bills, viewing bills, generating cash memos, and accessing the calculator. The database functionality is implemented using SQLite to store product information, bill details, and bill items. Separate modules are used for managing products, viewing bills, and the calculator feature.

## Usage

1. **Launch the application**.
2. **Navigate using the buttons** in the tabs to manage products, create bills, view bills, generate cash memos, and access the calculator.
3. **Manage Products**:
    - Add, edit, or delete product details.
4. **Create Bills**:
    - Enter customer details.
    - Add items to the bill.
5. **View Bills**:
    - Search by bill number, customer name, date range, or list all bills.
6. **Generate Cash Memos** for bills.
7. **Access the Calculator** feature via the GUI.

## Future Improvements

- Support for saving and loading bills to/from files.
- Integration with a database for storing customer information.
- Enhanced error handling and input validation.
- More customization options for the GUI layout and themes.

---

**Presented by**: [@farhansyedali](https://github.com/farhansyedali) [@muqniturrehman](https://github.com/muqniturrehman)

---

### Requirements

- Python 3.*
- Tkinter
- SQLite3

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Shahzad-Shafiq/Shop-Management-System.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Shop-Management-System
    ```
3. Install the required dependencies

### Running the Application

Run the main application file:
```bash
python main.py
