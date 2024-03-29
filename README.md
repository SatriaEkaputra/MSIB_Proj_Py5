# MSIB_Proj_Py5

This project demonstrates the use of object-oriented programming (OOP) principles, including basic OOP, inheritance, and polymorphism, to clean and transform marketing data stored in a CSV file. The script utilizes the pandas library for easier data manipulation.

## Project Structure

- `marketing_data.csv`: Sample dataset containing marketing data.
- `Data_Warehouse_Python_Part_5_Project.ipynb`: Jupyter Notebook file implementing the ETL (Extract, Transform, Load) process using OOP principles.
- `transformed_marketing_data.csv`: Output file storing the transformed data after running the notebook.

## Usage

1. Clone the repository:

git clone <repository_url>

2. Install the required dependencies:

pip install pandas

3. Open and run the Jupyter Notebook:

jupyter notebook Data_Warehouse_Python_Part_5_Project.ipynb

This will open the notebook in your web browser. Follow the instructions within the notebook to execute the code cells and perform the ETL process.

## Classes

### `MarketingDataETL`

- **Methods**:
  - `extract()`: Reads data from a CSV file (`marketing_data.csv`).
  - `transform()`: Performs basic cleaning and transformation on the data.
  - `store(output_file)`: Stores the transformed data into a CSV file.

### `TargetedMarketingETL`

- **Inherits**: `MarketingDataETL`
- **Additional Methods**:
  - `segment_customers()`: Groups customers based on specified criteria (e.g., total spending, product category).

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

