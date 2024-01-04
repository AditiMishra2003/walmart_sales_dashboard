# walmart_sales_dashboard
# Walmart Sales-Dashboard


## Problem Statement

This Dashboard helps us to gain insights from the walmart sales dataset in order to analyse top cities with maximum profit, sales trend for differnet months, the time took to ship the product, top performing category of products. The aim is to analyse various factors that affect the sales and to improve sales strategies in order to gain maximum profit ,also keeping in mind 
customer satisfaction.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present.
- Step 5 : Visual filter (Slicer) was added for Field State so that we can analyse the sales,profit,etc. statewise.
- Step 6 : Four card visuals were added to the canvas in order to represent total sales, total profit, quantity of products sold and average number of days to ship products.
- Step 7 : A clustured bar chart was also added to the report design area representing the sales by category. 
- Step 8: Three Donut charts where added to visuals to represent sales by city, profit by city and category by state.


for creating new column named AvgDelivery for calculating the number of Days took to ship a product following DAX expression was written;
       
        AvgDelivery = DATEDIFF('Walmart'[Order Date],'Walmart'[Ship Date],DAY)
![Screenshot (8)](https://github.com/AditiMishra2003/walmart_sales_dashboard/assets/115421723/49218bf5-0f05-46e1-bcac-16118b472864)

        


        


 

 

 
 
 
 


# Snapshot of Dashboard 

![Screenshot (7)](https://github.com/AditiMishra2003/walmart_sales_dashboard/assets/115421723/0defdfa7-cd4d-41af-b8f3-bddf3788b8e6)



# Insights


Following inferences can be drawn from the dashboard;

### [1] Total Number of distinct Customers = 686

### [2] Top Six Category Of Product as per Sales 
     1) Phones remained the top Product as per Sales in all the four  consecutive years.
     2)Tables,Storage,Machines,Paper,Supplies were the other five top selling products as per sales.
   

 ### [4] Some other insights
 
 ### Sales as per State
 
 1.1) California was the sate with maximum number of sales.
 
 1.2) Washington was at second position with Sales point of view.
 
 1.3) The sales was minimum in wyoming.

 ### Profit by category
 
 2.1) The category of product with maximum profit was copiers (19.33k) which is 26.43% of total profit.
 
 2.2) The second product with maximum profit is accessory (16.48k) which is 22.54% of total profit.
 
 2.3)  The top five products with profit point of view are copiers, accessories, binders, paper and phones.
         
### Average number of Days took to ship a product = 3.93 days(approximately 4 days)

### Sales by month and year 

  3.1) The sale was maximum in december.
  
  3.2) The sale was minimum in january.

  3.3) In september, march and july also there was decent sales of products.


### Total number of products sold = 12K

### Sales by city 

4.1) The sales was maximum in westminster city.

4.2) In cities like yuma, whittier ,west jorden also the sales was  good .
