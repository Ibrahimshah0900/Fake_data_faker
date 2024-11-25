# E-commerce Transaction Simulator

## Project Description
The E-commerce Transaction Simulator is a Python-based project that generates realistic fake e-commerce transaction data using the **Faker** library. It simulates various details like product information, customer details, purchase dates, and transaction amounts, saving the generated data into a CSV file. Additionally, basic analysis of the data can be performed using **Pandas**.

## Features
- Generate fake e-commerce transactions.
- Include details such as:
  - **Product Name**: Name of the product purchased.
  - **Price**: Cost of the product.
  - **Buyer Details**: Name, email, and address of the buyer.
  - **Purchase Date**: Timestamp of the transaction.
- Save transaction data into a CSV file.
- Perform basic analysis on the generated data:
  - Calculate total revenue.
  - Identify the top-selling product.
  - Analyze transaction trends.

## Technologies Used
- **Python**: Programming language.
- **Faker**: To generate fake data for buyers and timestamps.
- **CSV**: For storing transaction data.
- **Pandas**: For data analysis.

## Setup and Installation
1. Clone the repository or download the project files.
2. Install the required Python libraries:
   ```bash
   pip install faker pandas
   ```
3. Run the main script to generate transactions and save them to a CSV file:
   ```bash
   python ecommerce_transaction_simulator.py
   ```

## Usage
1. Open the script file and adjust the following parameters if needed:
   - `num_transactions`: Number of transactions to generate (default is 100).
2. Run the script. The generated data will be saved as `ecommerce_transactions.csv`.
3. Use a tool like Pandas or a spreadsheet application to analyze the data.

## Example Output
A sample of the CSV file:
| Product Name | Price | Buyer Name | Buyer Email         | Buyer Address         | Purchase Date         |
|--------------|-------|------------|---------------------|-----------------------|-----------------------|
| Laptop       | 1200  | John Doe   | johndoe@example.com | 123 Main St, City     | 2024-11-25 10:30:00   |
| Headphones   | 200   | Jane Smith | janesmith@example.com | 456 Elm St, Town    | 2024-11-20 15:45:00   |

### Basic Analysis
Use the analysis script to:
- Calculate total revenue:
  ```bash
  Total Revenue: $XX,XXX
  ```
- Identify the most sold product:
  ```bash
  Top Selling Product: Laptop
  ```
- Get transaction counts by date.

