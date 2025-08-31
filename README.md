# ☕ Coffee Sales EDA Project

## 📊 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a Coffee Sales dataset to uncover insights into customer purchasing patterns, peak sales periods, and product performance. The analysis covers data cleaning, feature engineering, and detailed visualization to support business decision-making.

---

## 🔍 Business Problem
A coffee shop wants to **understand customer behavior and sales performance** to:
- Identify which products contribute most to revenue.
- Discover the best performing time slots, days, and months for sales.
- Recognize peak customer engagement hours.
- Optimize inventory and staffing accordingly.

---

## 📂 Dataset
- **Source**: Coffee Sales Data (CSV file)
- **Key Columns**:  
  - `transaction_id`  
  - `date`, `time`  
  - `product_category`, `product_type`  
  - `quantity`, `unit_price`, `total_bill`  
  - `payment_method`  

---

## ⚙️ Steps Performed
1. **Data Cleaning**
   - Removed duplicates and null values  
   - Standardized column names  
   - Converted `date` and `time` columns to proper formats  

2. **EDA & Visualizations**
   - Revenue contribution by product  
   - Sales trends by day, month, and hour  
   - Payment method preferences  
   - Heatmaps of sales by weekday & hour  

3. **Business Insights**
   - Top-selling product: **Latte (₹26,875 revenue)**  
   - Dominant payment method: **Card (100%)**  
   - Best performing time: **Night**  
   - Most profitable day: **Tuesday**  
   - Peak month: **March**  
   - Peak purchase hour: **10 AM**  

---

## 💡 Solutions & Recommendations
- Stock more **Latte** and promote it further during peak times.  
- **Tuesday + Night + 10 AM** combos can be targeted with offers/discounts.  
- Seasonal demand peaks in **March** → prepare inventory accordingly.  
- Since **Card payments dominate**, reduce reliance on cash counters.  

---

## 📈 Tools & Libraries
- **Python**: Pandas, NumPy, Matplotlib, Seaborn  
- **Jupyter Notebook** for analysis  
- **Markdown & GitHub** for documentation  

---

## 🚀 How to Run
```bash
# Clone repo
git clone <your-repo-url>

# Install dependencies
pip install -r requirements.txt

# Run EDA script
python coffee_eda_script.py
