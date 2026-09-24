# Python Restaurant 🍴

Python Restaurant is a simple command-line based food ordering program made using Python. It allows a customer to view the available menu, select food items, and get the total amount of their order.

## What This Project Does

The program provides a small restaurant menu with different food items and their prices. The customer can:

* View the available food items and prices
* Select an item to order
* Check whether the selected item is available
* Add a second item to the order
* Get the total amount to be paid

## Requirements

Before running the project, make sure you have:

* Python 3 installed on your computer
* A terminal/command prompt or any Python IDE such as VS Code, IDLE, or PyCharm

No external Python libraries are required for this project.

## Setup Instructions

### 1. Install Python

Download and install Python 3 if it is not already installed on your computer.

During installation on Windows, make sure to enable the **"Add Python to PATH"** option.

### 2. Download or Clone the Repository

Download this repository to your computer, or clone it using Git:

```bash
git clone <repository-url>
```

Then open the project folder.

### 3. Check Python Installation

Open Command Prompt or Terminal and run:

```bash
python --version
```

If Python is installed correctly, its version number will be displayed.

### 4. Dependencies

This project does not use any external packages or libraries.

There is no need to run `pip install`.

The program only uses basic Python features such as dictionaries, input, conditional statements, and arithmetic operations.

### 5. Run the Project

Open the project folder in Command Prompt or Terminal and run:

```bash
python restaurant.py
```

If your computer uses `python3` instead of `python`, use:

```bash
python3 restaurant.py
```

## How to Use

After starting the program:

1. The restaurant menu will be displayed.
2. Enter the name of the food item you want to order.
3. The program will check if the item is available.
4. You can choose whether you want to add another item.
5. Finally, the program will display the total amount of your order.

Enter item names exactly as they appear in the menu, for example:

```text
Pizza
Pasta
Burger
Salad
Coffee
```

## Example

```text
Welcome to PYTHON Restaurant
Pizza: Rs40
Pasta: Rs50
Burger: Rs60
Salad: Rs70
Coffee: Rs80

Enter the name of item you want to order = Pizza
Your item Pizza has been added to your order

Do you want to add another item? (Yes/No) Yes
Enter the name of second item = Coffee
Item Coffee has been added to order

The total amount of items to pay is 120
```

## Project Structure

```text
Python-Restaurant/
│
├── restaurant.py
└── README.md
```

`restaurant.py` contains the main Python program, while `README.md` contains the project documentation and instructions.

## Configuration

No special configuration is required. The menu items and their prices are already defined inside the Python program.

## Note

This is a beginner-level Python project created to practice basic programming concepts and build a simple real-world application.
