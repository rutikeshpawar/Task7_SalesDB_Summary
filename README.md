# Task 7 - Sales Summary from SQLite using Python

## 🎯 Objective
The objective of this task is to:
- Connect Python to a small SQLite database
- Run SQL queries to calculate **total quantity sold** and **total revenue** per product
- Load the results into pandas for easy manipulation
- Visualize the data in a simple bar chart using matplotlib

---

## 📂 Dataset
A small, self-created SQLite database file: **`sales_data.db`**

## 🛠 Tools Used
- **Python** (sqlite3, pandas, matplotlib)
- **SQLite** (built-in to Python)
- **Jupyter Notebook**

## 📂 Files in this Repository
- **Task7.ipynb** → Jupyter Notebook with all the steps:
  1. Create a small SQLite database (`sales_data.db`) with a `sales` table
  2. Insert sample sales data
  3. Run an SQL query to get total quantity and revenue per product
  4. Load results into pandas DataFrame
  5. Plot a simple bar chart and save it as `sales_chart.png`
- **sales_data.db** → SQLite database file with the `sales` table and sample data.
- **sales_chart.png** → Bar chart showing revenue by product.
- **README.md** → Project description and instructions.


## 🚀 How to Run
1. Clone this repository or download the files.
2. Open `Task7.ipynb` in Jupyter Notebook.
3. Run all cells in order.
4. The notebook will:
   - Create `sales_data.db` if it doesn't exist
   - Query the data and display results
   - Generate and save the bar chart as `sales_chart.png`


## 📊 Key Insights
- The highest revenue product in the sample data is **Notebook**.
- SQL’s `GROUP BY` was effective in aggregating sales data by product.
- Pandas provided a simple way to load SQL results into a DataFrame for easier manipulation.
- Visualizing revenue using a bar chart made it quick to identify top-selling products.
- Combining SQL and Python allowed for efficient data analysis in a single workflow.

---

## 📦 Deliverables
- **Task7.ipynb** → Jupyter Notebook containing all code and outputs for the task.
- **sales_data.db** → SQLite database file with the `sales` table and sample data.
- **sales_chart.png** → Bar chart image showing revenue by product.
- **README.md** → Documentation explaining the objective, dataset, steps, insights, and deliverables.


## ✍ Author
Rutikesh Pawar 
