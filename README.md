# World Cup Database

This project is a shell scripting solution for managing and analyzing FIFA World Cup data using PostgreSQL. The scripts provided allow you to populate a database with teams and games information, and then perform various queries to extract meaningful statistics from the data.

## Features

- **Data Insertion:**  
  The `insert_data.sh` script reads data from a CSV file (such as `games.csv`) and inserts it into the PostgreSQL database, creating records for teams and games.
- **Statistical Queries:**  
  The `queries.sh` script executes a series of SQL queries to provide useful statistics, including:
  - Total and average goals by teams
  - Most goals in a single game
  - Teams who played in specific rounds or years
  - Champions by year
  - List of unique teams, and more

## Technologies Used

- Bash/Shell scripting
- PostgreSQL

## Usage

1. **Setup:**  
   Make sure PostgreSQL is installed and the required database and tables exist.
2. **Insert Data:**  
   Place your `games.csv` file in the project directory and run:
   ```sh
   ./insert_data.sh
   ```
3. **Run Queries:**  
   Fetch statistics by running:
   ```sh
   ./queries.sh
   ```

## File Overview

- `insert_data.sh` – Script to load data from `games.csv` into the database.
- `queries.sh` – Script containing SQL queries for analyzing the World Cup data.

## License

For educational use. All rights reserved © 2025.

---
