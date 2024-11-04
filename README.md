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

    The primary objective of this POWER BI project is to gain valuable insights into Global Superstore’s performance.
    This project involves several stages, including ETL (Extract, Transform, Load) using Power Query, data modelling, 
    DAX calculations, and data visualization.  


**Datasource :** 

    Global Superstore.xlsx

**Tools :**

    Microsoft Power BI

**Assignment-1  Basic Data Cleaning :**

     To ensure data accuracy and consistency, the following data cleaning tasks were performed using Power Query Editor in Power BI:

        a.Identifed and removed unncessary columns that did not contribute to the analysis.

        b.Ensured that each column had the correct datatype.

        c.Handled missing values/blanks by imputing or excluding incomplete record.

        d.Checked for duplicate values to ensure integrity.

        e.Corrected column headers in the dataset.


**Assignment-2 DAX :**

       While creating reports in Power BI, sometimes we need more creative designs to visualize the data in the most effective way. 

       Here, we discuss what to do in such scenarios.We can make custom visualizations by adding columns and measures using DAX.

        a.We have the column order date and ship date in the given dataset. But we need another column which will show us the number 
        of days taken for shipment. We can custom column by taking the date difference of order and shipment date using the DAX.Take 
        a note to change the datatype of new column.

        b.In order to show the year-wise performance details,we have to extract year from the order date using the time intelligence 
        function year ().

        c.Besides,new measures are created using aggregate function sum(),count() and distinctcount().

 
