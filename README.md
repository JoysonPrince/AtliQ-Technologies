# AtliQ-Technologies

# **Problem Statement:**

-- AtliQ Hardwares is a consumer goods electronics company having operations in various countries.
-- Their business is growing rapidly and they still rely on excel files for data analytics. 
-- Excel files are hard to consume and not effective in generating insights. 
-- Also due to the lack of effective analytics the company faced a major loss in Latin America.
-- Senior executives of this company have decided to invest in a data analytics project and have assigned a team for this work, my work starts here.

# Task List:
1. Create a dynamic dashboard for finance, sales, supply chain, marketing teams and finally a executive-level dashboard for the management.
2. **Finance Report:** Create a detailed P & L Statement report, providing Customer-level, Product-level, Region-level, quarterly, yearly filters. Also show P & L performance 
   over time.
3. **Sales Report:** The team needs customer-wise & product-wise performance against growth margin%, net sales etc. Display the KPI's too, maintaining the filters as above.
   Give details regarding Total COGS, Pre-invoice deduction, Post-invoice deductions as Unit economics visual.
5. **Supply Chain Report:** Display KPI's like forecast accuracy %, net error, absolute error. Show net error & forecast accuracy trend over time. Also show Customer-wise, 
   segment-wise accuracy distribution, net error parameters.
6. **Marketing Report:** Create a detailed Segment-level, product-level, category-level, region-level, market-level performance table displaying net sales, net profits and 
   net profit %. Display a matrix for Growth margin % vs Net sales & Net sales vs net profit %. Total COGS, Growth margin unit economics.
7. **Executive Report:** The management of AtliQ wants to see the yearly trend of AtliQ PC Division performance against metrics like net sales, growth margin %, net profit %.
   Also, the top-5 customers and products generating highest revenue for them.
   Market share % by manufacturer, also metrics performance for different sub-zones.

# Data modeling:

![Data model](https://github.com/JoysonPrince/AtliQ-Technologies/assets/137388224/06b9511d-4a90-4b9f-8593-f2d703626424)

Although, the data modeling image is unclear, you can view it in my live dashboard link.


# **Techniques learnt and how I did it**

# Finance Report:
1. Created KPI's for net sales, net profit %, gross margin %.
2. As per the task, created various measures, as well as a P&L Table structure for dynamic presentation of values.
3. P&L performance over time
4. Created a **parameter** to view P&L metrics, so that the user can dynamically switch between Segment, Product, Customer, Region and Market
5. Also, there is a slicer to view all the metrics based on the benchmark. The benchmark can be Last Year or Target data.
6. There are icons on the left, which takes you to various other reports and the landing page of course.

 ![Fin_1](https://github.com/JoysonPrince/AtliQ-Technologies/assets/137388224/41bcdb79-7694-466c-9269-2c01b918d639)


# Sales Report:
1. Maintained all the filters to the left to save space.
2. Created a **What-If parameter** to display customers who have met or fell short of 5%, 10% of their gross margin targets.
3. Dynamic parameters for customer and product for the user to switch between to view net sales, growth margin % etc
4. Unit economics: Total COGS, Pre-invoice deduction, Post-invoice deductions etc.
5. Also, there is a slicer to view all the metrics based on the benchmark. The benchmark can be Last Year or Target data.

 ![Sales_1](https://github.com/JoysonPrince/AtliQ-Technologies/assets/137388224/2a49c110-d372-43e6-9bcb-d2badc45aa77)


# Supply Chain Report: 
1. KPI's for net error, forecast accuracy %, absolute error.
2. Customer-level and Product-level performance based on the above KPI's.
3. Forecast accuracy % and net error trend over all years, comparing Forecast accuracy % to current year and last year with net error.
4. Benchmark slicer follows. The benchmark can be Last Year or Target data.

 ![SupplyChain_1](https://github.com/JoysonPrince/AtliQ-Technologies/assets/137388224/11bc785c-65ca-417c-a510-fba879647f3f)


# Marketing Report:
1. Region-wise performance of metrics like net profit, gross margin %, net sales, following dynamic parameter-based selection
2. I used the **new card visual**, a new update from Power BI. Utilised the reference label feature to display the Last Year value, % change from last to current year, and the 
   detail feature within reference labels to show an arrow for visual purpose.
3. Unit economics: Operational income, gross margin % and the resulting net profit with a waterfall chart and a donut chart for total COGS & gross margin %.
4. Benchmark slicer follows. The benchmark can be Last Year or Target data.

  **New Card Feature:** ![Marketing_2](https://github.com/JoysonPrince/AtliQ-Technologies/assets/137388224/937447c2-788e-486d-9973-15e223120de1)
  


 ![Marketing_1](https://github.com/JoysonPrince/AtliQ-Technologies/assets/137388224/123118c7-12d1-4848-afe8-27bc336ffebb)


# Executive Report:
1. A ribbon chart displaying the market share % by different manufacturers.
2. Created a tabular visual to display metrics like net sales, gross margin %, market share %, net error % and the Risk Factor (OOS: Out Of Stock & EI: Excess Inventory).
3. Designed a table for displaying top-5 customers and top-5 products by revenue. To utilize and save space, I used the **Bookmark** feature to dynamically switch between top-5 customers and top-5 products.
4. Again, another dynamic switch for donut charts, to switch between Revenue by division & Revenue by Channel, by **Bookmark** feature.
5. Of course, the stakeholder-level KPI's for the management is shown as well.
6. Created a pop-up visual as well to display all the filters.
   Pop-Up visual Demo:
   https://www.linkedin.com/posts/prince-joyson7_new-recording-382024-24902-pm-activity-7171812910199914496-mNJM?utm_source=share&utm_medium=member_desktop

  
![Exec_1](https://github.com/JoysonPrince/AtliQ-Technologies/assets/137388224/cd64d857-b62b-4b1c-ab20-c320abf681a8)


