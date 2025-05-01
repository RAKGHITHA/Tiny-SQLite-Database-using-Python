Objective
Create a tiny SQLite database and use Python to:
- Run basic SQL queries (e.g., total quantity and revenue by product)
- Display results using print and a simple bar chart

 Tools Used
- Python (in Google Colab)
- `sqlite3` for database handling
- `pandas` for data manipulation
- `matplotlib` for data visualization
Dataset
A manually created SQLite database `sales_data.db` with one table:

**Table Name:** `sales`

| Column   | Type    |
|----------|---------|
| id       | INTEGER (Primary Key) |
| product  | TEXT    |
| quantity | INTEGER |
| price    | REAL    |
