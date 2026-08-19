# Processed E-commerce Dataset — Day 9

This project processes the provided **Orders, Customers, and Products** CSV files using Pandas.

## Requirements demonstrated

- Loading CSV files with `pandas.read_csv()`
- Combining related datasets with `merge()`
- Demonstrating DataFrame combination with `concat()`
- Creating useful columns with `apply()` and lambda functions
- Converting order dates with `pd.to_datetime()`
- Extracting year, month, month name, day, and day of week
- Creating an order value using quantity × unit price
- Exporting the final dataset to CSV

## Project structure

```text
Day9_Processed_Ecommerce/
├── data/
│   ├── Orders.csv
│   ├── Customers.csv
│   ├── Products.csv
│   └── processed_ecommerce_dataset.csv
├── Processed_Ecommerce_Dataset_Day9.ipynb
└── README.md
```

## Dataset summary

- Customers: 30 rows
- Orders: 120 rows
- Products: 20 rows
- Final processed dataset: 120 rows × 22 columns

## Final dataset

The processed dataset combines order, customer, and product information and includes derived fields such as:

- `Order_Value`
- `Order_Value_Category`
- `Order_Year`
- `Order_Month`
- `Order_Month_Name`
- `Order_Day`
- `Order_Day_of_Week`

## How to run

Open `Processed_Ecommerce_Dataset_Day9.ipynb` in Jupyter Notebook, JupyterLab, VS Code, or Google Colab. Keep the `data` folder in the same project directory so the relative file paths work correctly.
