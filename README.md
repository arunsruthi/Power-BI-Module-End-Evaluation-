# Power-BI-Module-End-Evaluation-<br><br>
<b>Drive link</b>
https://drive.google.com/drive/folders/12GVqeJWMkn2Gi6izfZhP6bkdpKqAOH-T?usp=drive_link<br><br>
<b>Data Cleaning & Imputation</b><br><br>

• Date Format: Converted text dates using localized query settings into a true Date type formatted as dd-MM-yyyy (e.g., 01-01-2026).</b><br><br>

• Region Imputation: Replaced empty text slots with the placeholder string "Unknown".</b><br><br>

• UnitPrice Imputation: Solved missing product baseline rates using the row-level formula: [Sales] / [Quantity].</b><br><br>

<b>Visualizations & Insights</b>
<br><br>

• Pie Chart (Region Distribution): Tracks Count of OrderID by Region to highlight geographic market share and locate volume clusters.<br><br>
• Column Chart (Top 5 Products): Uses a Top N filter by Count of OrderID to isolate high-demand items (like Laptops and Monitors) for inventory tracking.<br><br>
• Line Chart (Profit Trend): Plots Sum of Profit across OrderDate to reveal seasonal growth cycles and cash flow trends.<br><br>


 <b>DAX Calculations</b><br><br>

• Calculated Table: Built an isolated regional data subset named EastRegionOrders using the filter expression:<br><br>
