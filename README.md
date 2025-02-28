# -Supply-Chain-Overcharge-Analysis-
This project analyzes courier billing discrepancies for an e-commerce company to identify overcharges and undercharges in shipping costs. By comparing expected vs. billed charges, we detect instances where the company paid extra or saved money. The analysis is based on weight slabs, delivery zones, and rate cards. 


## 📌 **Project Overview**  
Ever wondered if businesses are being **overcharged** for shipping? This project dives into the billing discrepancies in an e-commerce company's **supply chain**, ensuring that courier companies are charging the right amount for deliveries. By analyzing weight slabs, delivery zones, and rate cards, we uncover cases where the company **paid more than they should have—or got lucky with undercharges**.  

## 🔍 **The Problem**  
Company **X**, a major e-commerce player, ships thousands of orders daily through multiple courier partners. Each shipment cost depends on:  
✅ The **weight** of the package (rounded up to the nearest 0.5 KG slab)  
✅ The **distance & delivery zone** (based on pincode mapping)  

Given their **massive logistics expenses**, even small overcharges can **add up to big losses**. The goal? **Verify every charge and uncover hidden cost discrepancies.**  

🛠 **How We Did It**  
1️⃣ **Data Cleanup & Processing** 🧹  
   - Merged reports from **orders, SKU weights, and courier invoices**.  
   - Ensured data integrity (no missing values or duplicates).  

2️⃣ **Expected vs. Billed Charge Calculation** 📊  
   - Determined the correct **weight slab & expected cost** per shipment.  
   - Compared against **actual charges** billed by courier partners.  

3️⃣ **Finding Overcharges & Undercharges** 🔍  
   - Flagged orders where the company **overpaid or underpaid**.  
   - Summarized the total financial impact.  

4️⃣ **Final Report & Insights** 📑  
   - **Order-Level Breakdown** (order ID, weight, delivery zone, expected vs. billed charges).  
   - **Summary Report** showing the **total overcharged & undercharged amounts**.  

## 📊 **Key Findings**  
📌 **322 orders were overcharged**, leading to an excess cost of **₹25,304.30**.  
📌 **36 orders were undercharged**, saving **₹1,650.20**.  
📌 The company can use this analysis to **negotiate better courier contracts** and **reduce unnecessary expenses**.  

### 💾 **Tech Stack**  
- **Python** (Pandas, NumPy, OpenPyXL for Excel automation)  
- **Excel** (Data validation & reporting)  

This project is a **real-world example** of how **data analytics can save businesses money** by catching hidden cost leaks! 

