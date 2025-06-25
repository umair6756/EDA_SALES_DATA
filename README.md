
# 🛒 Superstore Sales and Profit Analysis

This project performs **Exploratory Data Analysis (EDA)** on a retail **Superstore** dataset using Python libraries like **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**. The aim is to understand sales and profit trends across different categories, regions, and years.



## 📂 Dataset Information

The dataset used is `Superstore.csv`, which contains customer orders including:

- 📅 Order Date
- 🏷️ Category, Sub-Category
- 🌍 Region, Country
- 💵 Sales, Profit, Discount
- 📦 Quantity, Ship Mode



## 🛠️ Technologies Used

| Tool/Library       | Purpose                                |
|--------------------|----------------------------------------|
| Python             | Programming language                   |
| Pandas             | Data manipulation and cleaning         |
| NumPy              | Numerical operations                   |
| Matplotlib & Seaborn | Data visualization                  |
| Jupyter Notebook   | Interactive development environment    |



## 📊 Project Features

### ✅ Data Cleaning
- Handled null values and duplicates
- Converted `Order Date` to datetime
- Created new `Year` column for time-based analysis

### ✅ Outlier Detection
Boxplots are used to detect outliers in `Sales` and `Profit`.

### ✅ Profit Analysis by Category, Region, Country
Pie charts to visualize profit distribution.

### ✅ Time-based Analysis
Profit and Quantity are analyzed year-wise using bar charts.


## 📈 Sample Visualizations

- Outliers in Sales & Profit
- Pie charts for Profit by Category, Region, Country
- Bar charts for Year-wise Profit and Quantity


## 📌 Key Insights

- Some categories or countries may lead to losses even if sales are high.
- South and West regions performed well in terms of profit.
- Profitability varies year to year; quantity does not always mean higher profit.
- Some outliers in sales and profit can significantly affect total results.



## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/superstore-analysis.git
cd superstore-analysis
```

2. Install required libraries:
```bash
pip install pandas numpy matplotlib seaborn
```

3. Run the notebook:
```bash
jupyter notebook superstore_analysis.ipynb
```



## 📁 File Structure

```
📦 superstore-analysis
 ┣ 📄 Superstore.csv
 ┣ 📄 superstore_analysis.ipynb
 ┗ 📄 README.md
```



## 🙋‍♂️ Author

**Hafiz Umair**  
*Data Science Student | Devops Engineer*  
GitHub: [@umair6756](https://github.com/umair6756)



## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
