What is the Business Problem of These Stores?

Vrinda Stores wants to create an annual sales report for 2022 so that they can better understand their customers and increase sales in 2023.

Sample Questions:

Compare the sales and orders using a single chart.
Which month had the highest sales and orders?
Who purchased more in 2024—men or women?
What are the different order statuses in 2024?
List the top 10 states contributing to the sales.
What is the relationship between age and gender based on the number of orders?
Which channel is contributing the most to sales?
What is the highest-selling category?

This is the chart we can check all the data through that sheet.


![Screenshot (153)](https://github.com/user-attachments/assets/6d8b4b44-4000-4584-b895-f6d9a725ef21)

Step of the projects : - 
Step 1: Check the Google Sheet to see if the data is helpful in solving those particular questions or not.
Step 2: Data Cleaning,Check the sheet to see if each column's data is correct.
        Specifically, check the first column, 'Order ID,' for any duplicate or null values using the filter function and other colum also.
step 3: Data Processing -  grouping the age data
      i)=IF(E2>=50,"senior",IF(E2>=30,"Adult","Teneger"))
     ii) add one column Month =TEXT(G2="MMM") 
Step 4: Data Analysis-

      i) Orders vs. Sales Status:
      To compare sales and orders using a single chart:
      Pivot the table.
      For the first question, compare the sales and orders using a single chart.
      Since I need the sum of the amount and the count of the order IDs on a monthly basis:
      Place the "Amount" and "Order ID" in the values section of the pivot table.
      Place the "Month" in the rows section of the pivot table.






![Picture1](https://github.com/user-attachments/assets/f21c91ba-5bc1-44e8-9b3e-fb12381bdcd0)

      
      
      
      ii) Men vs. Women Sales:
      To analyze the percentage of total sales between men and women:
      Pivot the table.
      First, calculate the percentage of total sales for men vs. women.
      Place the "Amount" in the values section of the pivot table.
      Place the "Gender" in the rows section of the pivot table.


      ![Picture2](https://github.com/user-attachments/assets/8dc0f575-50e8-4123-a2a9-d2c0f807f457)














      
      iii)Order Status: Percentage of Orders (Cancelled, Delivered, Returned, Refunded):
      To analyze the percentage of orders by status:
      Pivot the table.
      First, place "Order ID" in the values section of the pivot table.
      Place the statuses "Cancelled," "Delivered," "Returned," and "Refunded" in the rows section of the pivot table.


      
      ![Picture3](https://github.com/user-attachments/assets/394824df-2101-4019-99d4-2441641e8481)

      iv)Top 5 States by Sales Data:
      To get the top 5 states by sales data:
      Pivot the table.
      Place "Amount" in the values section of the pivot table.
      Place "States" in the rows section of the pivot table.
      Sort the rows by the largest values.
      Extract the top 5 values from the sorted rows.


      ![Picture4](https://github.com/user-attachments/assets/fd23db96-84c9-499c-8f54-cd173652790e)

      
      v)Age and Gender Data Along with Orders:
      To analyze orders based on age and gender:
      Pivot the table.
      Place "Order ID" in the values section of the pivot table.
      Place "Age Group" in the rows section of the pivot table.
      Place "Gender" in the columns section of the pivot table.

      ![Picture5](https://github.com/user-attachments/assets/4d244b99-3ddd-48ba-a410-d398ac10dac1)

      
      vi)Channels vs. Orders:
      To analyze the number of orders by channel:
      Pivot the table.
      Place "Order ID" in the values section of the pivot table.
      Place "Channels" in the rows section of the pivot table.
      

      ![Picture6](https://github.com/user-attachments/assets/0ae3e123-580c-4061-9dda-9db13540f344)







