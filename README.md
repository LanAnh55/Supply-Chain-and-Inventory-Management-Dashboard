# Supply-Chain-and-Inventory-Management-Dashboard

Prepared by: Nguyễn Thị Lan Anh 

Tool used: Tableau Desktop

Data sources: SQL Database 

Purpose: Track and improve inventory performance across warehouses

Available at: [Tableau Online](https://public.tableau.com/app/profile/nguy.n.th.lan.anh6349/viz/InventoryManagementDashboard_17500622461680/Storytelling)

# I. PROJECT OBJECTIVE
In today’s fast-moving supply chain, businesses must manage inventory carefully to avoid:

•	Stock-outs that affect customer service and revenue

•	Overstock that wastes money and warehouse space

•	Poor stock coverage that leads to last-minute purchases and inefficiencies

To solve these problems, the Inventory Management Dashboard was created. Its main goals are:

•	Monitor current stock levels across products and locations

•	By analyzing Excess Stock, we can identify specific items where stock levels have exceeded reasonable thresholds — highlighting cases that may require urgent attention or even red-flag alerts due to high risk of waste or overcapacity.

•  On the other hand, Missing Stock Value helps pinpoint items that have been overlooked or understocked, potentially impacting customer fulfillment. From this, we can calculate the estimated budget needed to replenish each item at each warehouse location to meet expected demand.

•	Forecast stock needs and predict future stock-outs

•	Compare performance across warehouses

•	ABC prioritization to focus resources on high-impact items

•  Collaborative planning with suppliers to shorten lead times and reduce buffer stock

•  Ultimately, the dashboard provides a clear, data-driven foundation for improving inventory performance, minimizing costs, and enhancing service levels across the supply chain.

# II. DASHBOARD STRUCTURE

6 main dashboards: Assessment Context: Warehouses and Availability; Problem: Excess Stock and Missing Stock, Delve Into Analysis, Solution: Optimize Stock Coverage 

# III. KEY ANALYSIS 

1. Warehouses – Location Comparison
   ![Warehouse](https://github.com/LanAnh55/Supply-Chain-and-Inventory-Management-Dashboard/blob/main/Figure/Warehouse%20Inventory.png)
   
• Ranks top warehouses by stock status

• Compares excess, missing, and balanced stock levels: Evaluate the severity of the warehouse based on the % of excess stock, ,missing stock compared to inventory value 

2. Availability – Current Inventory Status
  ![Availability](https://github.com/LanAnh55/Supply-Chain-and-Inventory-Management-Dashboard/blob/main/Figure/Availability.png) 
   
• Shows product categories by stock condition: safe, overstocked, low, or critical

• Based on average consumption demand (avg.Outflow) -> predicts next stock-out periods 

• Helps with planning and reordering schedules, stock-out alerts

• Estimates how many days stock can cover future demand

2. Problem: Excess Stock – Overstock Tracking
  ![Excess Stock](https://github.com/LanAnh55/Supply-Chain-and-Inventory-Management-Dashboard/blob/main/Figure/Excess%20Stock.png) 
   
• Highlights products with stock above demand or safety level

• Tracks the value and trend of overstock over time

3. Missing Stock – Low & Out-of-Stock Position

  ![Missing Stock](https://github.com/LanAnh55/Supply-Chain-and-Inventory-Management-Dashboard/blob/main/Figure/Missing%20Stock.png)   
• Finds products below safety stock or Stock-out

• Determine the amount of money that will be spent to compensate for missing stock position 

4. Adhoc Analysis 
 ![Excess Stock](https://github.com/LanAnh55/Supply-Chain-and-Inventory-Management-Dashboard/blob/main/Figure/Adhoc%20Analysis.png) 
• Provides line charts follow the fluctuations, indicators, Pareto chart and performance bars to focus on top issues

6. Solution: Stock Coverage
![ Stock Coverage](https://github.com/LanAnh55/Supply-Chain-and-Inventory-Management-Dashboard/blob/main/Figure/Stock%20Coverage.png).

• Based on standard deviation and average Outflow Quality - consumption, to determine the level of customer demand



