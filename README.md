# Banking System Prototype

## Overview
This project is a prototype that replicates the backend of a banking system using Python. The system enhances security through OTP verification and supports various banking transactions, with real-time updates reflected in an Excel sheet.

## Features
- **User Authentication**: Verifies user credentials using One Time Password (OTP) sent to the user.
- **Security Measures**: Allows three attempts for OTP validation before blocking the account to prevent unauthorized access.
- **Transaction Management**: Enables users to perform desired transactions post successful login.
- **Real-time Updates**: Updates the final total balance in an Excel sheet after each transaction.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)

## Installation
To get started with the project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/banking-system-prototype.git
    ```
2. Navigate to the project directory:
    ```bash
    cd banking-system-prototype
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
To run the project, execute the following command:
```bash
python main.py
