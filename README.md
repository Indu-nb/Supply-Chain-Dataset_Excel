This is a Supply Chain dataset related to MakeUp domain. 
You can find this dataset on Kaggle: https://www.kaggle.com/datasets/harshsingh2209/supply-chain-analysis
This dataset has the following parameters (each with 100 values): Product Type (Skincare, Haircare, Cosmetics), SKU, Price, Availability, Number of products sold, Revenue generated, Customer demographics, Stock levels, Lead times, Order quantities, 
Shipping times, Shipping carriers, Shipping costs, Supplier name, Location, Lead time, Production volumes, Manufacturing lead time, Manufacturing costs, Inspection results, Defect rates, Transportation modes, Routes,
Costs

This excel file attempts to find answers to these questions:
1. Which Product category has been the most profitable?
Ans. Skincare contributes maximum to the revenue and sale count and also has the highest revenue per order.
   
2. Time Optimization: Which supplier has the lowest lead time? Which carrier has the lowest shipping time? Which Transportation Mode has the lowest lead time, Which route has the lowest lead time?
Ans. Carrier B, Supplier 3, Air Mode, Route A has the lowest lead time or shipping time.
   
3. What is the status regarding inspection compliance and how it passes on to different suppliers?
Ans. Inspection pass% is at 23%, 36% fail and the rest in pending which paints a sober picture. Supplier 1 ahs the most SKUs with pass % and Supplier 4 has none. Supplier 4 also ends up with most failed inspection items.
Manufacturer will have to take Supplier 4 in confidence while improving on inspection compliance metrics.
   
4. Calculate ReOrder Point and create order amangement for suppliers and manufacturers for each SKU that has cost breakdown?
Ans. Safety stock is taken as 0 in this case as the data points to none. Reoder Point is calaculated as sale velocity * lead time ((no of products sold/quarter of year in days) * (Shipping + Order Processing Lead Time)

5. Which Product Category does better under defect analysis?
Ans. Cosmetics is generally a well performing category under defect analysis. Skincare has the highest variability, which is warning as it contributes the highest to revenue and generally has high expectations of
   quality from customers and regulations. Haircare performs comparatively poor among the three categories.
   
6. If we consider two primary risks of supply chain as holdour risk and stockout risk - calculate a consolidated risk score for each SKU and product category.
   Which SKU and Product category perform the best and worst in terms of risk?
Ans. SKUs of skincare and Haircare form both the highest and lowest risk category list. SKU 72 has the higest risk (wothout outliers) and including outliers, it would be SKU 52. SKU 0 has the lowest risk.
Cosmetics is the lowest risk product category (also low variability). Skincare has highest risk, followed closely by haircare. 

7. Calculate EOQ with present data and compare how it deviates from present order quantities. Which supplier has the highest and lowest EOQ and faces highest and lowest variability?
Ans. EOQ is higher than present order quantities than all of the present order quantities. Supplier 3 has the highest EOQ order levels and variability. Supplier 1 has lowest EOQ levels and variability.  
