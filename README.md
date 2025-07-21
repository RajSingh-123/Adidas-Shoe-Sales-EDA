# 📊 Adidas Shoe Sales – Exploratory Data Analysis

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on Adidas retail shoe sales data to identify:
- Top-performing products and regions
- Seasonal trends in sales
- Customer segments for marketing strategies
- Revenue and profit patterns

**Tech Stack Used:**
- 🐍 Python (Pandas, NumPy)
- 📈 Seaborn & Matplotlib for visualizations
- 📊 Jupyter Notebook for analysis

---

## 💡 Why This Project Matters
Adidas, like any global retailer, needs to understand **what drives its sales and profits**.  
By analyzing real sales data:
- ✅ Management can **identify best-selling products and regions** to focus marketing efforts.  
- ✅ Sales teams can **plan seasonal promotions** by spotting trends.  
- ✅ Business planners can **optimize inventory and pricing** based on profit patterns.  

**In short:** This project turns raw sales data into actionable insights that directly support business growth and decision-making.

## 🎯 Objectives
✔️ Clean and preprocess Adidas shoe sales dataset  
✔️ Explore sales trends by region, product type, and date  
✔️ Perform RFM-style segmentation (Recency, Frequency, Monetary)  
✔️ Visualize insights for business decision-making  

---

## 📂 Dataset
**File:** `Adidas Shoe Sales.csv`

**Columns include:**
- `Region`, `State`,`city`, `Product`, `Retailer`,`Retailer_ID`,`Sales_Method`
- `Invoice_Date`
- `Unit_Sold`, `Total_Sales`, `Operating_Profit`, `Price_per_Unit`
- And other relevant attributes

**Source:** [dataset](https://www.kaggle.com/datasets/davidmashishi/adidas-shoes-sales)

---

## ⚙️ Steps Performed
1. **Import & Inspect Data**
   - Loaded CSV into Pandas DataFrame
   - Checked for missing values, datatypes, duplicates

2. **Data Cleaning**
   - Removed special characters from numeric columns
   - Converted strings to appropriate numeric and datetime formats
   - Handled missing values

3. **Exploratory Analysis**
   - Overall sales trends
   - Grouped by region, product, and month
   - Identified top contributors to revenue and profit

4. **Customer Segmentation**
   - Implemented basic RFM analysis (if applicable)
   - Segmented by frequency of purchase and revenue contribution

5. **Visualizations**
   - Bar plots for top regions/products
   - Line charts for monthly sales trends
   - Heatmaps to show correlations
   - Distribution plots for revenue and profit

---

### 📊 Key Insights
✅ Highest total sales were observed in **West Region** with a total of **$2.69M** in revenue.  
✅ **Running Shoes** and **Sneakers** contributed to over **45%** of total sales.  
✅ Seasonal spikes in sales were seen during **Q3 (June-August)**, likely due to holiday promotions.  
✅ Retailers like **West Gear** and **Foot Locker** were consistent top performers in revenue and profit.  
✅ Profit margins were highest in **Midwest Region**, suggesting a potential for focused marketing campaigns.
---

## 🚀 How to Run
1. Clone this repository or download the notebook.
2. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Place `Adidas Shoe Sales.csv` in the same directory as the notebook.
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook AdidasShoeSale.ipynb
   ```
5. Run all cells to reproduce the analysis and visualizations.

---

## 📁 Repository Structure
```
├── AdidasShoeSale.ipynb       # Jupyter notebook with full analysis
├── Adidas Shoe Sales.csv      # Dataset 
└── README.md                  # Project documentation
```

---

## 📌 Future Improvements
🔹 Perform deeper customer segmentation (advanced clustering)  
🔹 Build predictive models for forecasting sales  
🔹 Create an interactive dashboard (Power BI or Tableau)

---

## ✨ About
**Author:** *Raj Singh*  
Feel free to reach out for feedback or collaboration!   
✅ **Email:** *rajsingh3706@gmail.com*

---

**If you like this project, don’t forget to ⭐ the repository!**
