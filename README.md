## Case study on dominos_pizza_sales using POWER-BI & My-SQL ##

**Objective** : 
  * To analyze the key-metrics such as total revenue,total orders,Monthly & Daily trends on pizza_sales_data using My_Sql.
  * To Create a complete Dashboard on Data Visualization on Pizza Sales using Power BI.
    
This data set has 48000+ datapoints containg a basic information about the pizzas such as order_id,pizza_id,quantity,order_date,order_time,total_price,pizza_category,pizza_name that were sold in 1 year.

## My_SQL ## : 
Extracted Metrics such as total_revnue,total_orders,avg_order_value,total_pizzas_sold by writing My-Sql quieries.

**Metrics** :
1. Total Revenue: Sum of total price of each Order.
2. Total Orders: Number of distinct order_id will give the total orders.
3. Average Order Value: Total Revenue divided by Total orders.
4.Total Pizzas Sold: Sum of quantity of each pizza from all orders.
5.Average Pizzas per Order: Total Pizzas Sold divided by Total Orders will give Average pizzas sold.

These metrics helps in extracting the daily & monthly trends as well as top_selling_pizzas by revenue,quantity & total_orders by writing few queries.

## POWER-BI ## :
Imported the data from MySql server and transformed these data to get new columns such as day name,day number,month name & month number.
Extracted these Metrics (Total Revenue,Total Orders,Average Order Value,Total Pizzas Sold,Average Pizzas per Order) by writing the DAX expressions.

Created a Complete Data-Visualization dashboard analyzing the daily & monthly trends on first page ,worst & best pizza sellers on 2nd page:

**First_page** : 
 * Analyzed the bussiest times by visualizing daily trends & monthly trends for total orders.
 * Analyzed the sales performance by pizza category & pizza size.
   
**Second_page**:
 * Analyzed the best sellers & worst sellers by visualizing the pizzas with diff parameters such as revenue,quantity & total orders.







