# 🍽️ Restaurant Performance Dashboard (Excel Project)

### 📊 Project Overview
This project demonstrates end-to-end Excel data analytics using **Power Query**, **data cleaning**, **lookup/merge operations**, and **Pivot-based dashboards**.  
It simulates a restaurant chain’s 2024 performance data, visualizing key insights on **sales**, **menu performance**, **transaction types**, and **server productivity**.

The goal of this project is to **practice real-world Excel analytics skills**, from raw data cleaning to dashboard design.

---

### 🧩 Data Sources
Four CSV files were used:
- `Sales_Transactions.csv` – 5,000+ individual line-item transactions  
- `Menu_Items.csv` – Menu categories, cost, and prices  
- `Servers.csv` – Employee and branch details  
- `Customer.csv` – Customer demographics and loyalty data  

---

### 🧹 Data Cleaning & Preparation (Power Query)
1. **Loaded all datasets** into Power Query.  
2. **Cleaned `Sales_Transactions`:**
   - Changed data types (Date, Time, Numeric).  
   - Calculated **Sales = Qty × Unit Price × (1 − Discount%)**.  
   - Standardized **Branch** and **PaymentType** formats:
     - Trimmed spaces and fixed typos (e.g., “Down town” → “Downtown”).  
3. **Merged Tables:**
   - Joined `Sales_Transactions` with `Menu_Items` (by `MenuItemID`).  
   - Joined `Servers` (by `ServerID`) to add employee names.
4. **Removed duplicates** and ensured data consistency.

---

### 📈 Analysis & Visualization
Created multiple **Pivot Tables and Charts** to summarize performance:

- **Sales by Branch** (clustered column chart)  
- **Top 10 Items by Sales** (bar chart)  
- **Top 5 Servers by Sales**  
- **Transaction Types** (pie chart)  
- **Interactive Slicers:** Category, Branch, and Date timeline  

All visuals are compiled into a single **Excel dashboard** for quick insights.

---

### 🧠 Key Excel Skills Practiced
- Power Query data cleaning and transformations  
- XLOOKUP / Merge joins between tables  
- PivotTable and PivotChart creation  
- Slicers and Timelines for interactivity  
- Formatting and dashboard layout design  

---

### 🏁 Result
A fully interactive **Restaurant Performance Dashboard** that provides:
- Branch-level sales and profitability insights  
- Best-selling menu items  
- Server performance comparison  
- Transaction-type analysis  

---

### ⚙️ Tools Used
- **Microsoft Excel (Power Query, PivotTables, Charts)**
- **Windows 10 / Office 365**
- **GitHub for version control and project showcase**

---

### 📌 Author
Created by *Haoyu Li* as a self-practice project to enhance Excel analytics and dashboard design skills.
