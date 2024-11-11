# Global_Super_Store-Dashboard
 
 **Table of Contents:**
 
     1.Project Overview
     2.Data Source 
     3.Tools
     4.Basic Data Cleaning
     5.Dax Calculation
     6.Data Visualization
     7.Key findings and insight
     8.Recommendation

**Project  Overview :**

    The primary objective of this POWER BI project is to gain valuable insights into Global Superstore’s
    performance.This project involves several stages, including ETL (Extract, Transform, Load) using 
    Power Query, data modelling, DAX calculations, and data visualization.  

**Datasource :** 

    Global Superstore.xlsx

**Tools :**

    Microsoft Power BI

**Assignment-1  Basic Data Cleaning :**

     To ensure data accuracy and consistency, the following data cleaning tasks were performed using 
     Power Query Editor in Power BI:

        1.Identifed and removed unncessary columns that did not contribute to the analysis.
        2.Ensured that each column had the correct datatype.
        3.Handled missing values/blanks by imputing or excluding incomplete record.
        4.Checked for duplicate values to ensure integrity.
        5.Corrected column headers in the dataset.

**Assignment-2 DAX :**

       While creating reports in Power BI, sometimes we need more creative designs to visualize the 
       data in the most effective way. Here, we discuss what to do in such scenarios.We can make custom
       visualizations by adding columns and measures using DAX.

        1.We have the column order date and ship date in the given dataset. But we need another column 
        which will show us the number of days taken for shipment. We can custom column by taking the 
        date difference of order and shipment date using the DAX.Take a note to change the datatype of 
        new column.

        2.In order to show the year-wise performance details,we have to extract year from the order date
        using the time intelligence function year ().

        3.Besides,new measures are created using aggregate function sum(),count() and distinctcount().

**Assigmment-3 Data Visualization:**
        
        A simple interactive dashboard report is created in Power BI.The report is structured using visualization charts and tables.
        The final outlook of the dashboard is as under:
        

 <img width="590" alt="power bi dash global" src="https://github.com/user-attachments/assets/0a16abb2-8a02-468f-8f6b-995dd8902833">

**Key findings and insight:**

       1.Total Summary:
       
          *	Total Orders: 25,000 orders have been placed.
          * Total Sales: $9.48 million in sales.
          * Total Profit: $1.09 million in profit.
          
       2. Filters
         *	Filteres for Year, Country, Category, and Product Name to drill down into specific time periods, regions,
           or products to get more tailored insights from the data.

       3. Percent of Shipping Based on Ship Mode:
       
          * Standard Class is the most used shipping method,while same day is less common, possibly due to higher costs.

       4. Sales by State:
       
          * The map highlights sales distribution across different states worldwide.
          * Sales appears concentrated in North America and parts of Asia, indicating high-performing regions.
          
       5. Sales by City:
   
          * New York and Los Angeles are the top cities for sales.

       6. Sales by Region & Market:
       
          * Sales vary by region and market.This segmentation helps to understand how different markets contribute to the 
            overall sales.
          
       7. Top 5 Products by Sales:
       
          * Apple, Cisco, Motorola, Nokia, and Honeywell products are the top sellers.
          * These products are contributing most to sales. This information could be used for focusing on high-demand items.
          
       8. Top 5 Products by Profit:
       
         * Motorola and Cisco products are highly profitable.
         * Motorola and Cisco not only drive sales but also deliver high profits, making them key products for business growth.
         
  **Recommendation:**
  
      1.Standard classs has major shipping portion.Negotiate with shipping partners to get better rates for bulk orders.
      2.Sales by state and city indicate that sales is more concentrated in New York and Los Angeles.Increase target and 
        introduce new marketing strategies to further strenghth sales.Alos,analyze the reason for high performance in these 
        places and check whether same strategy can be applied in other places.
      3.Reduce resources of low performing and loss making products for more profitable and high demanding products.


