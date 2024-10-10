# Superstore-report-using-PowerBi
## INTRODUCTION
I will be working on the Superstore Dataset analytics project as part of the evaluation for the PSP Analytics-organized Data Science course. This megastore, which sells furniture, office supplies, and technology products, is situated in the United States of America. The Super Store's shipment dates, sales, profit, and other data are included in the Superstore dataset. Analysing Superstore performance and obtaining insights for business growth is the aim of this activity. 

## DATA SOURCE: 
The dataset utilised in this work was posted by Mr. Zion Segun on the Data Science Class announcement channel.

## DATA PREPARATION
The dataset will be loaded into PowerBI in Excel format. If the data is clean, it can be loaded straight into PowerBi or transformed to make it clean.

## DATA TRANSFORMATION AND CLEANING
Here, we verify that each column's format is accurate and make any required corrections. We additionally take care of the column inconsistencies to provide a more precise dataset for analysis.
- We are now formatting the columns for Sales, Profit, and Discount in order to show currency

## DATA EXPLORATION/VISUALIZATION
Here, we used charts and tiles to provide particular business answers for a study of sales performance. Among these enquiries are the following:
i.	Which Category has the highest order totals?

ii.	What is the profit margin that each category has made?

iii.	In which city does the store have more orders?

iv.	Which Segment has more Profits? 

v. What City yields more sales?

## KEY PERFORMANCE INDICATORS 
We must first define the KPI (Key Performance Indicators) before we can respond to the inquiry. The profit margin, discount, quantity, profit, and sales are among the KPIs. This is accomplished by setting up measures and utilizing DAX to determine our profit margin as well as total sales, profit, quantity, and discount.

**i.	Sales:** To obtain the total sales, we utilise the SUM function. 

**ii.	Quantity:** Total quantity inside the dataset 

**iii.	Profit**: The data set's total profit 

**iv.	Profit margin** is calculated by dividing total profit by total sales and then multiplying the result by 100. 

**v.	Discount:** The dataset's overall amount of all discounts 

To visualise our KPI, we use the KPI tile. The Card tile is another option.

**1.	What is the highest ordered category?**

![image](https://github.com/user-attachments/assets/bfe38f47-d235-49b1-87f3-1b8067779e84)

By drawing a relationship between the "Category" column and the "Quantity" measure using the clustered column bar, the maximum order can be achieved.

**2.	What is the profit margin accrued by each category**
   
 ![image](https://github.com/user-attachments/assets/06864aaa-b14e-4111-9bf7-fe0068a38e1c)

**3.	In which city does the store have more orders?**
   
 ![image](https://github.com/user-attachments/assets/f9341663-1250-4139-abf1-4d69d14ebb8a)

**4.	Which Segment has more Profits?**

![image](https://github.com/user-attachments/assets/8bb9bc03-a041-46d7-8de8-64945f7fa76e)

**5.	What City yields more sales?**

![image](https://github.com/user-attachments/assets/48e95b7d-242c-4737-89f5-51be2f22666f)

## CONCLUSION
Thus far, the superstore dataset analysis has allowed us to derive important insights from the business problems. We may offer data-driven suggestions to support business expansion based on these findings. Below is the dashboard that was produced using PowerBI.

 ![image](https://github.com/user-attachments/assets/15529f13-e80c-4e50-85c0-836fbe1ff7bc)

