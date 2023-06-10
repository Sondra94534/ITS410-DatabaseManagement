# MySQL Database Connection and Data Processing

This repository contains a Python script that connects to a MySQL database and performs data processing tasks. The script retrieves information from the "world_x" database, calculates the median severity of accidents for different types of motorcycles, and inserts the results into the "accident_medians" table.

## Prerequisites

Before running the script, ensure that the following requirements are met:

- Python 3.x is installed on your machine.
- The `mysql-connector-python` package is installed. You can install it by running `pip install mysql-connector-python`.

## Setup

1. Clone this repository to your local machine or download the code as a ZIP file.
2. Make sure you have a MySQL server installed and running.
3. Import the "world_x" database into your MySQL server. You can find the database file in the repository under `database/world_x.sql`.
4. Open the script file `main.py` and update the database connection details in the `connect()` function. Modify the `host`, `database`, `user`, and `password` parameters to match your MySQL server configuration.

## Usage

To run the script and perform the data processing tasks, follow these steps:

1. Open a terminal or command prompt.
2. Navigate to the directory where the script file `main.py` is located.
3. Run the script by executing the command `python main.py`.
4. The script will connect to the MySQL database, retrieve motorcycle types, calculate the median severity of accidents for each type, and insert the results into the "accident_medians" table.
5. The progress and status of the script will be displayed in the terminal.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

