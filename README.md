# 🧮 Rent Calculator

## Overview

This is a simple Python-based Rent Calculator application that allows users to calculate the monthly rent payments based on various parameters such as the total rent amount, lease duration, and additional expenses. The project demonstrates basic Python programming concepts and offers a practical utility for anyone looking to manage or estimate their rental payments.

## Features

* Calculate monthly rent based on the total rent amount and lease duration.
* Option to add additional expenses (e.g., utilities, maintenance fees).
* User-friendly input prompts to guide through calculations.
* Clear and simple output display with a breakdown of costs.
* Error handling to ensure valid input from users.

## Prerequisites

* Python 3.x or higher
* Basic knowledge of Python (variables, functions, loops, conditionals)

## Installation

To get started with the Rent Calculator project, follow the steps below:

1. Clone this repository to your local machine using the following command:

   ```bash
   git clone https://github.com/beharabhuvanasri/rent-calculator.git
   ```

2. Navigate to the project folder:

   ```bash
   cd rent-calculator
   ```

3. No additional dependencies are required as this project uses only Python’s built-in libraries.

## Usage

To run the Rent Calculator, simply execute the `rent_calculator.py` script from your terminal:

```bash
python rent_calculator.py
```

### Example Interaction

```bash
Welcome to the Rent Calculator!

Please enter the total rent amount: 12000
Please enter the lease duration (in months): 12
Would you like to add any additional expenses? (yes/no): yes
Enter additional expense amount (e.g., utilities): 150

Your total monthly rent (including expenses) will be: 1075.00
```

### Input Parameters

* **Total Rent Amount**: The total rent for the entire lease period (e.g., for a 12-month lease).
* **Lease Duration**: The number of months for the lease.
* **Additional Expenses**: Optional additional costs such as utilities, parking, or maintenance fees.

### Output

The program calculates and outputs:

* The **base monthly rent**.
* The **total monthly cost** (base rent + additional expenses).

## Code Explanation

### rent_calculator.py

1. **Function `calculate_monthly_rent(total_rent, lease_duration)`**:

   * Calculates the base monthly rent by dividing the total rent by the lease duration.

2. **Function `add_expenses(expenses)`**:

   * Adds any additional expenses to the monthly rent.

3. **Function `get_user_input()`**:

   * Handles user input, validates that input is valid (e.g., numerical values), and returns values for the calculation.

4. **Main Execution Block**:

   * Manages the overall flow of the program, guides the user, and outputs the final result.

## Contributing

If you'd like to contribute to the project, feel free to fork the repository, create a feature branch, and submit a pull request. Contributions are always welcome!

### Steps to Contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Submit a pull request.

### Enhancements / Future Ideas

* Add a feature to handle different payment plans (quarterly, semi-annual).
* Incorporate a graphical user interface (GUI) using Tkinter or PyQt.
* Store rent and expense history in a text file or database.
* Allow for discount or rent increase scenarios (e.g., early payment discount, rent increase after a certain number of months).

---

### Acknowledgements

Special thanks to the Python community for their support and resources.

---

This should be a good starting point for your GitHub README! If you have any specific changes or additions you’d like to make, feel free to let me know!
