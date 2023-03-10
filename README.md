# Power-bi-dashboard-for-AtliQ-Technologies
This bi dashboard will help the AtliQ technologies to analyse the sales of their electronic devices in different countries and make insightful decision to grow their 
revenue and recognize the area where the performance is not up-to-the-mark. 

**datasource:mysql

The data is loaded, transformed(with power query editor), and visualized with the help of Power BI.

This is a multiple-page report which is more than 25 mb, so I could not upload the iriginal file. However, I uploaded some screenshot of showing what I put into 
together to analyse the business data.


***This is a home page which is the main page and it can take you to othere pages with the 
![image](https://user-images.githubusercontent.com/123319398/224434883-9b7face1-5ab7-461c-bad6-e787d0ea0b87.png)

Data modeling where dimensions tables are the outer ones and the main transaction table is fact_actual_estimates where all the important attributes are listed. 
Key measure are on the left most which has all the measures for the calculations created using DAX.

![image](https://user-images.githubusercontent.com/123319398/224440623-6708a90b-2581-43f1-9380-a8f02483307d.png)


1. Finance view : Profit and loss statement, Net sales performance over the time, Top and bottom products and customers net sales

![image](https://user-images.githubusercontent.com/123319398/224441021-ef237c34-8e84-4d77-bb54-0d9542d224e0.png)


2. Sales view : Customer performance like net sales, gross margin and gross margin % is shown using matrix and scatter chart. Which product perform best is 
   also displayed using a matrix throgh net sales, gross margin and gross margin %. two donut charts are used for unit economics. Donut charts are used to show 
   the distribution of net sales, total post invoice deduction and total pre invoice deduction. Second donut chart is used to show cost of goods sold and gross margin.
   
   ![image](https://user-images.githubusercontent.com/123319398/224442708-6315a5ab-dd14-4198-abbe-19a18662b482.png)


3. Marketing view : drill down is used to show the performance of different products and regions using a matrix. Waterfall chart is used to show the increase or 
   decrease in gross margin, net profit and operational expense.
   
   ![image](https://user-images.githubusercontent.com/123319398/224443519-b4f2127a-b763-4972-b370-36d75ecc4402.png)


4. Supply chain view : Customer and product performance is shown on the basis of forecast accuracy %, forecast accuracy LY %, net error  and net error % is displayed in 
   a matrix. Accuracy and net error's trend is shown over the period using a line and stacked column chart.
   
   ![image](https://user-images.githubusercontent.com/123319398/224444162-182e6060-23ad-448a-99d3-c5d39c67195a.png)


