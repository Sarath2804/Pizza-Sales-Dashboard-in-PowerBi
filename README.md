# Pizza Sales

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiZTczNTc0MjMtNTAzZC00OTYzLTljMGQtNzVmNWQwOTUwMWIxIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9



This dashboard helps the Pizza shop owner understand their customers better. It helps to know if their customers are satisfied with their services. Through different ratings, they get to know their improvement area, & thus they can improve their services by identifying these area. 


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present.
- Step 5 : For calculating average delay time, null values were not taken into account as only less than 1% values are null in this column(i.e column named "Arrival Delay") 
- Step 6 : In the report view, under the view tab, theme was selected.

 - Step 7 : Created many calculated measures for the easy understanding of the data in dashboard.

 - Step 8 : Also created so many calculated columns in orders table to get the graphs and chart on related to the differentiation of the dates.

 - Step 9 :
   
<p align="center">
  <img src="https://github.com/Sarath2804/pizzasales/assets/95603007/de2ac40f-c2c9-4b51-a7aa-1172c9242a67" alt="Step 9 Screenshot">
</p>

With the use of calculated measure and calculated column we got the total order by quarter
<p align="center">
  <img src="https://github.com/Sarath2804/pizzasales/assets/95603007/07445537-b4b0-4cfa-b979-09d8da832b05" alt="Step 9 Screenshot">
</p>

In the same way we got the total Revenue by quarter


 - Step 10 : In the same way we also got the total order and total revenue by month.

<p align="center">
  <img src="https://github.com/Sarath2804/pizzasales/assets/95603007/0f5e06ef-d48b-45e1-bfba-09761e637ff1" alt="Step 9 Screenshot">
</p>


 - Step 11 : This bar chart has the average order by each month.
<p align="center">
  <img src="https://github.com/Sarath2804/pizzasales/assets/95603007/40d5f4ef-f2bc-42eb-946e-965ce5041b43" alt="Step 9 Screenshot">
</p>
 
 With the dashboard we can easily point out some of the most important aspects in the pizza sales like:

 Least Ordered Pizza : Bria Carre Pizza
 Most Ordered Pizza : Classic Deluxe 
 Least Revenue Pizza : Brie Carre 
 Most Revenue Pizza : Thai Chicken



The dashboard also provides the below measures:

1. Orders per day 
2. Orders per month
3. Orders per quarter
4. Revenue per day
5. Revenue per month
6. Revenue per quarter

These numbers are present in numeric cards to depict the numbers in the dashboard.




After that we have line chart and bar chart for orders by day, orders by month, order by quarter, and the same for revenue as well.

This is the final dashboard for the Pizza sales.

<p align="center">
  <img src="https://github.com/Sarath2804/pizzasales/assets/95603007/5098a9b9-1b72-42a5-b27d-77c67b1522d8" alt="Step 9 Screenshot">
</p>


