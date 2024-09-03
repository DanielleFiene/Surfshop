# Surf Shop Testing Suite

This project is a testing suite for a hypothetical surf shop's shopping cart system. It uses Python’s `unittest` framework to ensure that the `ShoppingCart` class from the `surfshop` module behaves as expected. The suite covers various scenarios, including adding surfboards, applying discounts, and validating checkout dates.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [How It Works](#how-it-works)
- [Usage](#usage)
- [Learning Outcomes](#learning-outcomes)
- [License](#license)

## Project Overview

The Surf Shop Testing Suite is designed to test the functionality of a shopping cart system in a surf shop application. It ensures that functionalities like adding surfboards to the cart, applying discounts, and setting checkout dates work correctly. The tests use Python's `unittest` module to automate the testing process.

## Features

- **Add Surfboards**: Test if surfboards are added correctly to the cart with varying quantities.
- **Apply Discounts**: Verify if the locals' discount is applied correctly.
- **Checkout Date Validation**: Ensure that invalid checkout dates raise appropriate errors.
- **Error Handling**: Check if appropriate errors are raised when adding too many surfboards.

## Technologies Used

- **Python**: The core programming language used.
- **unittest**: Python's built-in module for creating and running tests.
- **datetime**: For handling and testing date and time-related functionality.

## Setup and Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/surfshop-testing-suite.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd surfshop-testing-suite
   ```

3. **Install dependencies**:

   Ensure you have Python installed. The project does not require additional dependencies beyond Python's standard library.

## How It Works

1. **Test Initialization**: Each test case initializes a new `ShoppingCart` instance before running individual tests.
2. **Adding Surfboards**: Tests ensure that surfboards are added correctly and handle varying quantities.
3. **Applying Discounts**: Tests check if applying a locals' discount works as intended.
4. **Error Handling**: Tests verify that errors are raised when invalid actions, such as adding too many surfboards or setting an invalid checkout date, occur.

## Usage

- **Run the tests** to ensure the shopping cart system functions as expected:

   ```bash
   python -m unittest discover
   ```

   or

   ```bash
   python tests.py
   ```

## Learning Outcomes

Through this project, you will:

- **Understand Unit Testing**: Learn how to use Python's `unittest` module to create and run tests for your code.
- **Test Different Scenarios**: Gain experience in testing various scenarios, such as adding items to a cart, applying discounts, and handling errors.
- **Error Handling in Tests**: Learn how to handle and test for exceptions and errors in your code.
- **Parameterization and Skipping Tests**: Understand how to use `subTest` for parameterized tests and how to skip or expect failures in tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
