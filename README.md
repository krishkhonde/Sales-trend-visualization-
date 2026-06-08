# Sales-trend-visualization-


**Intern ID: CITS1317**

**Name: Krish khonde**

**Organization: Codtech IT Solutions Pvt. Ltd**

**Internship Period: 20 May 2026 - 17 June 2026**

---

This is my second internship project. I analyzed 6 months of sales data to find trends across products, categories, regions and salespersons. Also built a prediction model for next month sales.

---

## Tools and Libraries Used

- Python 3
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## Dataset

I created a dummy sales dataset with 90 records covering January to June 2024.

Columns:
- Date
- Product (Laptop, Mobile Phone, Tablet, etc.)
- Category (Electronics, Furniture)
- Units_Sold
- Unit_Price
- Total_Sales
- Region (North, South, East, West)
- Salesperson

---

## Steps I Followed

**1. Data Loading**
Loaded CSV using pandas and checked the data.

**2. Data Cleaning**
- Converted Date to datetime format
- Extracted month and week number
- Checked for null values — none found
- Removed duplicates

**3. Analysis**
- Calculated total and monthly sales
- Found top products and categories
- Compared region wise and salesperson wise performance

**4. Visualization**
Made 6 charts:
1. Monthly sales trend (line chart)
2. Sales by category (bar chart)
3. Top 5 products (horizontal bar chart)
4. Region wise distribution (pie chart)
5. Salesperson performance (bar chart)
6. Units sold vs total sales (dual axis chart)

**5. Prediction Model**
Used Linear Regression to predict July 2024 sales.

---

## Results

- Total sales in 6 months: Rs. 1,32,52,100
- Total units sold: 1399
- Best category: Electronics
- Top product: Laptop
- Best region: North
- Top salesperson: Rahul
- Predicted July 2024 sales: Rs. 33,18,173
- Model R2 Score: 0.8477

---

## Files in this Project

- sales_data.csv — dataset
- sales_trend.py — main python code
- sales_visualizations.png — all 6 charts
- sales_prediction.png — prediction chart
- README.md — this file

---

## How to Run

```
pip install pandas matplotlib seaborn scikit-learn
python sales_trend.py
```
