# Employee Management System CLI

## Overview
This CLI application allows you to manage departments and employees efficiently through a command-line interface.

## Features
- **Department Management:**
  - Create new departments.
  - Delete existing departments.
  - View all departments.

- **Employee Management:**
  - Create new employees.
  - Delete existing employees.
  - View all employees.
  - Filter employees by department ID.

## Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
2. Install dependencies:
   ```bash
   pipenv install

## Usage
1. Navigate to the project directory:

   ```bash
   cd <project_directory>
2. Run the CLI application:

   ```bash
   python lib/cli.py
3. Follow the on-screen prompts to manage departments and employees.

## Requirements
- Python 3.x
- Pipenv
- SQLite3

## Code Overview
### Helpers (lib/helpers.py)
This module contains helper functions for executing and fetching data from the SQLite database.

### Models (lib/models/models.py)
This module defines the Department and Employee classes, including their ORM methods for creating, deleting, and querying records.

### CLI (lib/cli.py)
This module provides the command-line interface for interacting with the application, including menus for managing departments and employees.

## Example Usage
    ```bash
    $ python lib/cli.py

    Welcome to the Employee Management System
    1. Manage Departments
    2. Manage Employees
    3. Exit

    Enter your choice: 1

    Departments Menu:
    1. Create Department
    2. Delete Department
    3. View All Departments
    4. Return to Main Menu

    Enter your choice: 1

    Enter department name: HR
    Department created successfully.

    Departments Menu:
    1. Create Department
    2. Delete Department
    3. View All Departments
    4. Return to Main Menu

    Enter your choice: 4

    Welcome to the Employee Management System
    1. Manage Departments
    2. Manage Employees
    3. Exit

    Enter your choice: 3

    Exiting program...


## Contributing
Contributions are welcome! Please fork the repository, make changes, and submit pull requests.
