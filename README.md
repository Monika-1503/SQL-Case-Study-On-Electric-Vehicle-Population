# 🚗 Electric Vehicle Population - SQL Case Study

This project analyzes the **Electric Vehicle Population** dataset using **MySQL Workbench**. The case study includes SQL queries for data retrieval, aggregation, ranking, and performance optimization.

## Features
- Retrieving and filtering data based on conditions
- Aggregating data (count, sum, average, etc.)
- Ranking electric vehicles using **Window Functions & CTEs**
- Performance optimization using **Indexes**
- Data cleaning with `UPDATE` and `DELETE` queries

## 📂 Dataset Columns
| Column Name                        | Description |
|-------------------------------------|-------------|
| `VIN`                               | Vehicle Identification Number |
| `County`                            | County of registration |
| `City`                              | City of registration |
| `State`                             | State of registration |
| `Postal Code`                       | Postal code of registration |
| `Model Year`                        | Year of the vehicle model |
| `Make`                              | Manufacturer (e.g., Tesla, Nissan) |
| `Model`                             | Vehicle model |
| `Electric Vehicle Type`             | Type of EV (BEV/PHEV) |
| `CAFV Eligibility`                  | Clean Alternative Fuel Vehicle eligibility |
| `Electric Range`                    | Maximum electric range (in miles) |
| `Base MSRP`                         | Manufacturer's Suggested Retail Price |
| `Legislative District`              | Legislative district of registration |
| `DOL Vehicle ID`                    | Department of Licensing Vehicle ID |
| `Vehicle Location`                  | Geospatial location of vehicle |
| `Electric Utility`                   | Electricity provider |
| `2020 Census Tract`                 | Census tract for the vehicle |

## Requirements
- MySQL Workbench
- Python (optional, for analysis with Pandas)
- MySQL Server

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/electric-vehicle-sql.git
   ```
2. Open **MySQL Workbench** and connect to your database.
3. Import the dataset and run the queries from `queries.sql`.

## License
[MIT LICENSE] 

## Author 
Monika Mahala

