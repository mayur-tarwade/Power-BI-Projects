# Global Super Store Analysis
## Dashboard Link - https://app.powerbi.com/groups/93b91c12-0441-439c-b77f-660fda6218db/reports/a355be5c-0228-47fc-a2a1-6642c968f3bf/2d3217a16047276c2048?experience=power-bi

# Problem Statements

Global Super Store, a retail giant, has relied on Excel for their data analysis needs. However, with advancements in technology, they decided to migrate to Power BI for enhanced business intelligence capabilities. They have approached you to build a comprehensive dashboard with their data up to 2019. Below are the specified requirements and the corresponding business problems that this dashboard aims to solve.

This dashboard should aim to empower Global Super Store with actionable insights, enabling them to make data-driven decisions and improve their overall business performance. Each visual should be crafted to address specific business questions and challenges, providing a clear and informative representation of their data.

### Q1-     Global Super Store wants to quickly assess its overall performance through key metrics. The management needs a concise overview of:
●	    What is our total revenue generated so far?

●	    How profitable have we been over the years?

●	    How many orders have we successfully processed?

●	    How many consumers have we served?

<img width="649" height="124" alt="Screenshot 2025-07-26_1" src="https://github.com/user-attachments/assets/09b6534a-7154-4571-915f-90b69bd077a5" />


So 

Total Revenue - 12643.25K

Total Profit - 1467.56K

Total Orders - 51.295K

Total Customers - 1.59K

### Q2-     The sales team is looking to identify trends over the years to inform their strategy. They need to see how their annual sales perform Over the year  and on the same graph they also want to know the overall trend and sales of their store over the years.

<img width="1919" height="1030" alt="Screenshot 2025-07-26_2" src="https://github.com/user-attachments/assets/1b936402-e9ff-4615-bed2-e8865596e9ae" />



### Q3-    Marketing and finance teams need to understand the seasonality and profitability trends to optimise their campaigns and budgets. Sales and finance teams are working together for this cause, they need a graph that can help them understand.
●	   	How do our sales and profits fluctuate month by month? 

●	   	Are there particular months where profits significantly increase or decrease, indicating potential seasonal trends?

<img width="1917" height="1031" alt="Screenshot 2025-07-26_3" src="https://github.com/user-attachments/assets/44497a29-7cb0-4c57-ae9a-ccb0afdc2731" />



### Q4-     The regional managers are keen to understand the performance of different markets to allocate resources effectively.
●	     They need to know Which markets are generating the most sales and profits.

●	     Are there specific markets where we need to focus our efforts to boost performance?

<img width="1919" height="1028" alt="Screenshot 2025-07-26_4" src="https://github.com/user-attachments/assets/7b574004-a7e5-4db4-8a0b-78db4c8a5ff3" />

So, Canada and EMEA are the markets where we need to focus our efforts to boost.

### Q5-   To  Boost their business, Global Superstore thought of planning their business quarterly. For that they need to know their overall sales for each quarter.

<img width="1920" height="1032" alt="Screenshot 2025-07-26_5" src="https://github.com/user-attachments/assets/96266b47-8e1d-4d04-8bb9-01dee264722c" />

### Q6-    After these visuals are built, management would like to incorporate a feature allowing them to select specific segments and categories. This functionality should dynamically adjust all the graph values based on the selected category and segment, providing a tailored view of their data.

To incorporate this feature we have used slicers of Segment and Category. As shown in below snap we see that Segment selected is Consumer and Category is Office Supplies.

<img width="203" height="362" alt="Slicers" src="https://github.com/user-attachments/assets/1d02b94a-4cd1-486f-ae78-904d4c2c9617" />

and all the visual will changes as per these selection.

<img width="1919" height="1032" alt="Screenshot 2025-07-26_6" src="https://github.com/user-attachments/assets/7407497b-c1e3-4ecb-bc05-0b0f6743cfb5" />

The company is pleased with the dashboard you have built so far; however, the company has suggested some new additions and some editing.
 
### Q7 The CEO observed that the total sales and total profit values fluctuate with interactions on the graph. They now require a fixed value for these metrics, separately from the dynamic values that change with visual interactions, so that they can always have an eye on the totals.

For this we have to disconnect the visual's interaction with all the visuals. This option is avaulable in Formate tab as Edit Interactions.We have to select None option wich is gray in snap.

<img width="1919" height="1030" alt="Edit interaction" src="https://github.com/user-attachments/assets/0fe7e4b6-b663-4bf8-9b6b-f9b83f690a96" />

so because of above slection the visuals dont get filter as per the slicers selection.

<img width="1122" height="536" alt="Edit interaction-2" src="https://github.com/user-attachments/assets/fafc75f7-43b2-49d6-9dc4-ee9b88ce5ba8" />

### Q8 In 2016, the company set a 5-year target to achieve an overall sales goal of $25 million and a profit goal of $10 million by the end of 2020. According to this plan, by the end of 2019, the company should have reached a sales target of $20 million. This equates to approximately $1.7 million in sales per month(collectively) from 2016 to 2019.As the company is far beyond the target to be achieved, the company is now interested in seeing for each month collectively (2016-2019) fluctuations of our sales performance from the target help company visualise this.Company is also interested in seeing a visual of how far they are from the set profit target.

<img width="1919" height="1030" alt="Target" src="https://github.com/user-attachments/assets/b0242656-975c-4698-b599-245d48da7b51" />
<img width="1917" height="1029" alt="away from Target" src="https://github.com/user-attachments/assets/3f4f156b-1884-48e2-814f-27624b4ddff1" />

### Q9 Management has identified an operational challenge: when selecting any slicer, transitioning back to the default view becomes cumbersome and time-consuming. To streamline this process, they have requested the implementation of a dedicated button. This button will enable them to swiftly return to the default view with a single click, eliminating the need to manually deselect each slicer. This enhancement aims to enhance user experience by providing a more intuitive and efficient navigation option within the dashboard.

We have provided clear button on slicers with which user can deselect all the slicers.

<img width="203" height="362" alt="Slicers_2" src="https://github.com/user-attachments/assets/fa8dcf62-54fe-4be6-96a3-f6801e267bad" />

### Q10 Global Superstore has been frequenting your desk with numerous minor queries, causing interruptions to other ongoing projects within the company. In response to this challenge, your boss has tasked you with developing a solution that empowers end-users (Global Super Store) to obtain answers to their questions independently. By implementing a user-friendly tool or feature, such as a searchable database or an interactive FAQ system, users can simply type their queries and retrieve instant responses. This initiative aims to enhance efficiency, reduce dependency on direct support, and allow for smoother workflow across all projects.

For this we have provided in-build feature of power bi that F&A Ask Anything button.

<img width="1290" height="204" alt="ask anything" src="https://github.com/user-attachments/assets/05d688bf-e332-4fd2-88ce-27544fa3d144" />

Once you click on this button you will get window as shown in below snap.

<img width="1505" height="728" alt="ask anything_2" src="https://github.com/user-attachments/assets/797d5ccd-65ec-40f3-aada-56e097fffc1d" />

### Q11 Global Super Store seeks to enhance its regional performance analysis and resource allocation strategy. They want to understand which geographic country is driving high sales and where profitability is strongest. Rather than bar chart or line chart they need some visuals in the form of maps,The visuals should be very understandable and interactive.
<img width="1919" height="1031" alt="sum of profit by country" src="https://github.com/user-attachments/assets/921b1b2e-b934-4661-be0e-4c8b7d6483ff" />


### Q12 The client has specified some visualisation specifications to you: -He wants that in the visuals that will display the profit chart, the colour of the country with lowest profit should be red and colour of country with the highest profit to be green and in between values to be coloured as gradient.For the visual that will be displaying the sales, client have made a request to show that the countries where sales are <80,000 should be coloured dark red, between 80,000 to 200000 it should be red, between 200000 to 700000 it should be green, and above 700000 it should be golden.

 <img width="1919" height="1031" alt="sum of sale by country with color" src="https://github.com/user-attachments/assets/9738dcf3-5f47-47f9-8efe-079d2741304e" />

 <img width="1916" height="1030" alt="sum of sale by country with color_2" src="https://github.com/user-attachments/assets/bb4e3c51-7ebd-4480-a291-efc5de6f5f96" />


 ### Q13 The client is happy with your work and wants to continue with you for further Business Intelligence. They have produced a quick requirement. The company core team has a meeting and they must discuss some topics. They have advised the BA team to give their input for this meeting which is scheduled in the next 1.5 hours. BA Team approached you to build some visuals, however due to time constraint they want you to build those visuals in next 25 minutes only, so that rest 1 hour can be spent by BA team on those visuals to form some inputs. ·   	Global Super Store needs to understand which regions are driving the highest sales and profitability. Develop a visual that clearly depicts the sum of sales and profit across different regions.

 <img width="1919" height="1031" alt="sum of sale and profit by region" src="https://github.com/user-attachments/assets/3d552f27-1e9b-45fe-afb0-a51ca9f77c08" />

### Q14 We need to understand how different product segments are performing as compared to other segments. BA team needs an interactive chart that displays sales figures for each product segment, this chart should clearly show each segment's sales as a percentage of both the previous segment and the top category.

 We can use funnel chart for this.
 
 <img width="1919" height="1030" alt="image" src="https://github.com/user-attachments/assets/f5b705ab-ad37-4902-becc-637f4b7dc087" />

 ### Q15 Clients have also come out with a challenging problem: they want a bar chart only (2d graph) that will show sales per year and by region, because the current approach to analysing yearly sales trends lacks depth and fails to provide actionable insights into regional sales dynamics.

 <img width="1918" height="1031" alt="image" src="https://github.com/user-attachments/assets/ff9d9b17-ecdc-4c33-ab55-4b0371c95d18" />


 ### Q16 As Global SuperStore has been your client for a long time and this is the time to give them the customer loyalty award, your boss asked you to create some free visuals for them that could help them in enhancing and building their business and strategy.

 Free Visuals
 <img width="1919" height="1029" alt="image" src="https://github.com/user-attachments/assets/be2d17cd-e8c6-4a32-89ab-366f31c06f58" />

 <img width="1919" height="1031" alt="image" src="https://github.com/user-attachments/assets/eb6e4825-a45a-4a56-99f1-3144088c794d" />
 

### Q17 The client requires a visual representation to display the status of order processing. Orders will be classified as delayed if the shipping date exceeds the order date by more than two days.

<img width="1919" height="1031" alt="image" src="https://github.com/user-attachments/assets/8fdc4fa5-bcc0-4aac-b790-b834ade5f8cf" />

### Q18 The client requires a detailed analysis to understand sales patterns based on the day of the week. They need a pie chart that visually compares the average sales volumes on weekends versus weekdays. This will help in identifying any significant differences in consumer behaviour and sales performance, enabling more informed strategic decisions for marketing and resource allocation.

Switch:

Weekend/Weekday = SWITCH (Orders [Day Name],
                                                        “Saturday”, “Weekend”,
                                                         “Sunday”, “Weekend”,
                                                          “Weekday” )
 So basic syntax of switch is SWITCH (Expression/test, Value1, Result1, Value2, Result2, Else if test fails)
 
<img width="984" height="213" alt="image" src="https://github.com/user-attachments/assets/f3ec21e8-335c-46f1-a9ee-7a3c968c84b8" />

Another Approach:

Weekend/Weekday
var days = FORMAT (Orders [Order Date], ”dddd”)
return
if (days in {“Saturday”, “Sunday”},” Weekend”, “Weekday”)

Whenever you use var you must have to use return, otherwise value won’t get displayed/print.

<img width="1919" height="1029" alt="image" src="https://github.com/user-attachments/assets/f1762a61-4ec5-4509-bc4b-e9add0607a1e" />

### Q19 The company, CA, seeks a comprehensive analysis of sales data segmented by financial months and financial quarters. This breakdown will reveal sales performance trends and patterns within each fiscal period, facilitating effective strategic planning and accurate financial forecasting.

So, Financial years start with April and ends at March (1st April to 31st March)
Logic will month>3, month-3 else month+9

Financial Month = 

var fmon = MONTH (Orders [Order Date])
return
if(fmon>3, fmon-3, fmon+9)

<img width="1919" height="1030" alt="image" src="https://github.com/user-attachments/assets/2e6079ce-e851-4e94-9a6d-eccf01a732b2" />

Financial Quarter = 

var fqtr = QUARTER (Orders [Order Date])
return
if(fqtr>=2, fqtr-1, fqtr+3)

<img width="1919" height="1030" alt="image" src="https://github.com/user-attachments/assets/bcb08582-bda8-4a61-ae4d-91cc7751c677" />

### Q20 The company, Finance Manager, requires an analysis to determine the average cost per unit, segmented by category and subcategory. This detailed breakdown should provide insights into cost distribution and highlight areas for potential cost optimization, aiding in more precise budgeting and pricing strategies.               Cost Price = Sale Price – Profit – Shipping Cost

Cost/unit = 

(Orders[Sale]-Orders[Price]-Orders[Shipping Cost]/Orders[Quantity])

<img width="1918" height="1031" alt="image" src="https://github.com/user-attachments/assets/5ef07146-91ea-425e-8f56-d992451b1e81" />

### Q21 Management wants to cluster its customers in different age groups. 14-19	        Teen, 20-30	         Young, 30-40 	Adult, 40-50 	Old Adult, >50     	Old. After Clustering, companies want a visual that will show total numbers   of consumers in each category and what is the contribution of each category to total consumer population.

Category = 

var Age = DATEDIFF (Customer [Date of Birth], DATE (2019,12,31), YEAR)
return
    SWITCH (TRUE (),
            Age<=19,"Teen",
            Age>20 && Age<=30,"Young",
            Age>30 && Age< 40,"Adult",
            Age>40 && Age< 50,"Old Adult",
            "Old"
    )

    <img width="839" height="639" alt="image" src="https://github.com/user-attachments/assets/d05e7a14-22ef-4736-a653-5f1a7f109eec" />

    

    
### Q22 Clients have given the requirement to categorise the Income into different groups. 0-30k 	             A,  30K-60K 	             B,  60K-100K    	    C,  100K -150K     	    D, >150K               	    E. Now, he wants a visual that will find the numbers of orders placed as per age category and income category in different regions.

    Age Category = 
    
   var Age = DATEDIFF (Customer [Date of Birth], DATE (2019,12,31), YEAR)
   return
   SWITCH (TRUE (),
           Age<=19,"Teen",
           Age>20 && Age<=30,"Young",
           Age>30 && Age< 40,"Adult",
           Age>40 && Age< 50,"Old Adult",
           "Old")
            
Income Group = 

var grp = Customer [Yearly Income]
return
SWITCH (TRUE (),
        grp<=30000,"A",
        grp>30000 && grp<=60000,"B",
        grp>60000 && grp<=100000,"C",
        grp>100000 && grp<=150000,"D","E"
)

<img width="940" height="428" alt="image" src="https://github.com/user-attachments/assets/c24cad0c-27c1-4607-82d4-8434c983f230" />

### Q23 The client wants a card that will show the sales from the date 15th April 2019 to 15th November 2019.

Here we are using DAX CALCULATE.

CALCULATE = CALCULATE (Expression, FILTER ())
FILTER = FILTER (Table, Filter expression)
E.g. 
Desired Sale = CALCULATE (sum(Orders[Sales]), FILTER(Orders,Orders[Order Date]>DATE(2019, 4, 15)), FILTER(Orders,Orders[Order Date]<DATE(2019, 11, 15)))

<img width="448" height="199" alt="sale between dates" src="https://github.com/user-attachments/assets/e4390783-5df3-4fb7-beac-fae6ecc286ce" />

### Q24 Global Super Store wants to value their   top 10 customers for their loyalty towards the store. Loyalty will be calculated on the basis of CLV Score [CLV score is Customer Loyalty Value Score]. CLV score is calculated: - CLV = (Average Order Value* Average Profit Margin)/ Purchase Frequency.

Formula for CLV                          
CLV  =      (Average Order Value * Average Profit Margin ) / Purchase Frequency

Profit Margin =

var mp = (Orders[Sales])/(Orders[Quantity]*(1-Orders[Discount]))
return
mp - Orders[Cost/Unit] 

CLV = 

var  cust = Customer[Customer ID]

var  sale = CALCULATE(sum(Orders[Sales]), FILTER(Orders, Orders[Customer ID] = cust ))

var  quantity = CALCULATE(sum(Orders[Quantity]), FILTER(Orders, Orders[Customer ID] = cust ))

var  profit = CALCULATE(AVERAGE(Orders[Profit Margin]), FILTER(Orders, Orders[Customer ID] = cust ))

var  purchase = CALCULATE(DISTINCTCOUNT(Orders[Order ID]), FILTER(Orders, Orders[Customer ID] = cust ))

var  avg_order_value = sale/quantity

return
(avg_order_value * profit)/purchase

<img width="1106" height="515" alt="CLV" src="https://github.com/user-attachments/assets/f864df87-e028-4a8a-a1ec-add8f2bfc4a9" />

### Q25 The Global Super Store Marketing team is interested in understanding how individuals of a specific gender, earning either above or below the average income for their gender, prefer ordering different subcategories across various regions. Based on this information, the marketing team aims to develop a targeted strategy.

Average =

 var male = CALCULATE(AVERAGE(Customer[Yearly Income]), FILTER(Customer,Customer[Gender] = "M"))
 
 var female = CALCULATE(AVERAGE(Customer[Yearly Income]), FILTER(Customer,Customer[Gender] = "F"))
 
 return
 
 if(male>Customer[Yearly Income] && Customer[Gender] = "M", "Under Average",
    if(female>Customer[Yearly Income] && Customer[Gender] = "F", "Under Average","Over Average"))

  <img width="1919" height="1030" alt="Region and age category" src="https://github.com/user-attachments/assets/e9633b86-16c2-4948-ac53-e96b2a0a98af" />

  ### Q26 The client requests an analysis of the count of high-value customers segmented by region. High-value  orders are defined as those who have made a purchase exceeding $1,500 with a profit percentage of at least 25% for that specific order.Client also wants to know out of total orders of that    region how much population is high value customers.

  High Value Customer = 
  
  CALCULATE(COUNT(Orders[Order ID]), FILTER(Orders, Orders[Sales]>1500), FILTER(Orders,Orders[Profit %]>25))
  
  HV Customer Population% =
  
  ([High Value Customer]/COUNT(Orders[Order ID]))*100

  <img width="828" height="673" alt="image" src="https://github.com/user-attachments/assets/1481923e-48df-4969-b414-3fd61e9d7c33" />

  ### Q27 The client has requested an enhancement to the previously created sales visual (Desired Sales). They would like the visual to display the variance between the desired sales of 2019 and desired sales of 2018 or the same date values.

  Desired Sale Variance = 
  
  var Twenty_ninteen = CALCULATE(sum(Orders[Sales]), FILTER(Orders,Orders[Order Date]>DATE(2019, 4, 15)), FILTER(Orders,Orders[Order Date]<DATE(2019, 11, 15)))
  
  var Twenty_eighteen = CALCULATE(sum(Orders[Sales]), FILTER(Orders,Orders[Order Date]>DATE(2018, 4, 15)), FILTER(Orders,Orders[Order Date]<DATE(2018, 11, 15)))
  
  return 
  
  ((Twenty_ninteen-Twenty_eighteen)/(Twenty_ninteen))*100

  <img width="712" height="347" alt="variance" src="https://github.com/user-attachments/assets/2205950a-307c-411b-b423-03ad6517f13a" />

  ### Q28 The client seeks an analysis of the average order value per customer. Furthermore, they request an identification of the top 15 customers based on the highest total order values.

  Avg Order Value = 
  
  ([Sales Measure]/CALCULATE(DISTINCTCOUNT(Orders[Order ID])))

  <img width="1106" height="451" alt="Avg Order Value" src="https://github.com/user-attachments/assets/71d018bc-86b3-42da-8b0b-9ca481e2d573" />

  ### Q29 The client requests the creation of a visual representation of sales data with a specific focus on country rankings. This visual should highlight and display only the countries that fall between the 11th and 19th positions based on their sales figures. The goal is to provide a clear understanding of the sales performance of countries that are mid-ranked in this range.

  [Sale Measure] = 
  
  SUM(Orders[Sale])

Rank Of Country = 

IF(RANKX(all (Orders[CONTRY]),[Sales Measure]) > 10 && RANKX(all (Orders[CONTRY]),[Sales Measure])<20 , [Sales Measure], BLANK())

<img width="1112" height="478" alt="Rank of Country" src="https://github.com/user-attachments/assets/114cf57b-0fec-44ce-b523-eb03bcee64bc" />

### Q30 The client desires a visual representation of the cumulative sales sum for each year. This visual should clearly illustrate the progressive accumulation of sales over time within each year.

Cumulative Sum = 

ALCULATE(sum(Orders[Sales]), Orders[Order Date].[Year]<= SELECTEDVALUE(Orders[Order Date].[Year]))

Cumulative sum = 

2016 - 2016

2017 - 2016+2017

2018 - 2016+2017+2018

2019 -2016+2017+2018+2019

<img width="273" height="166" alt="cumsum" src="https://github.com/user-attachments/assets/d3c0c88a-5cbb-4957-8fb2-4a911dce4972" />

### Q31 The CEO has requested a report showing the average daily sales amount across all years (2016, 2017, 2018, and 2019).

Average Sales = 

var lowest = min(Orders[Order Date])

var highest = max(Orders[Order Date])

var numdays = 
DATEDIFF(lowest,highest,DAY)

return
[Sales Measure]/numdays

<img width="151" height="155" alt="Avg Daily Sales" src="https://github.com/user-attachments/assets/e2c85d36-1ac2-44cd-82bd-7882dfb86e19" />

### Q32 The client requests a summary of the total sales for each month in the year 2019, specifically focusing on the sales from the last two financial quarters. This detailed monthly and quarterly breakdown will aid in assessing the performance during different periods of the year.

<img width="241" height="284" alt="monthly sale in year" src="https://github.com/user-attachments/assets/5ca7b362-dee1-4165-85b1-9a9b9960cb2a" />

It seems that there is only two quaters data available for the year of 2019.


### Q33 The client wishes to know the number of churned customers for the years 2016, 2017, and 2018. The CEO is now interested in knowing how far we need to go in customer retention services.

IN this problem first we formulate the churned customer. for that we created Retention Table

Retention Table = 

SUMMARIZE(Orders,

           Orders[Customer ID],

           "First Purchase Date", YEAR(min(Orders[Order Date])), 

           "Last Purchase Date", YEAR(max(Orders[Order Date])))

After this we formulate the count of customer churned by year

Custmr_churn_by_Year = 

var year = SELECTEDVALUE(Orders[Order Date].[Year])

return

if (year = 2016, COUNTROWS(FILTER('Retention Table', 'Retention Table'[Last Purchase Date]=year)),

if(year = 2017, COUNTROWS(FILTER('Retention Table', 'Retention Table'[Last Purchase Date]=year)), COUNTROWS(FILTER('Retention Table', 'Retention Table'[Last Purchase Date]=2018))))


But this formula is only for year 2016 to 2018 but if we want it for multiple years then we can have optimized code as

COUNTROWS(FILTER('Retention Table', 'Retention Table'[Last Purchase Date]=year))

<img width="266" height="209" alt="Customer Churn" src="https://github.com/user-attachments/assets/18e9b514-7ea7-485a-97c7-f5527fdc91ba" />

### Q34 The client requires a visual that displays the top-selling product in each country. This visual should highlight the most popular products in different regions and provide insights into regional preferences and market demand. It will be useful for targeted marketing and inventory management strategies.

MostSoldProduct = 

var TopProduct = 

TOPN(1,

SUMMARIZE(Orders,Orders[Region],Orders[Product Name],"Total", sum(Orders[Quantity])),[Total], DESC)

RETURN

MAXX(TopProduct, Orders[Product Name])

<img width="531" height="440" alt="most sold product" src="https://github.com/user-attachments/assets/0fc1cfd7-76e1-424d-87e4-682df51aa77c" />

### Q35 Analyse the company's product portfolio to determine the top 10 products that contribute the most to overall profitability.

Total Profit = 

CALCULATE(sum(Orders[Profit]), all(Orders))
Top Ten by Contribution = [Profit Measure] / [Total Profit] press %

<img width="921" height="326" alt="top 10 in profit" src="https://github.com/user-attachments/assets/8b468b38-e236-41ee-a562-54b3562959a7" />

### Q36 Determine the leading product category for each year by analysing annual sales data. This analysis will help identify trends and shifts in consumer preferences, enabling the company to make informed decisions on inventory management, marketing strategies, and product development for sustained growth.

Rank_1/yr = if (RANKX(all(Orders[Category]),[Sales Measure]) = 1, [Sales Measure], BLANK())

<img width="438" height="391" alt="image" src="https://github.com/user-attachments/assets/d1faa9d6-d71e-4451-8b76-bf2037cd0a37" />

### Q37 For each year, identify the top 3 managers annually based on the total sales they generated. This analysis will provide insights into the most effective leaders in driving sales performance, allowing the company to recognize and reward top talent, and replicate successful strategies across different regions.

Rank of Managers = if(RANKX(all(People[Name]), [Sales Measure])<4, RANKX(all(People[Name]), [Sales Measure]), BLANK())

<img width="1195" height="431" alt="top 3 mngr" src="https://github.com/user-attachments/assets/9b916bc2-a268-405f-b624-3115f9609ffd" />


### Q38 Assess how much the sales value of the top-ranked country deviates from the sales values of other countries within the top 10. This analysis will highlight the performance gap between the leading country and its peers, offering insights into potential areas for growth and improvement in underperforming regions.

Rank of Ctry = RANKX(all(Orders[CONTRY]), [Sales Measure])

Deviation = 

var top1 =CALCULATE(MAXX(TOPN(1, all(Orders[CONTRY]),[Sales Measure],DESC),[Sales Measure]))
var Sale = [Sales Measure]
var SaleDifference = top1-Sale

return

SaleDifference/top1

<img width="1478" height="483" alt="top 10 deviation" src="https://github.com/user-attachments/assets/1119cb85-c19c-4e10-9ecc-500f0a5cb333" />


 ### Q39 Evaluate the year-over-year growth in new customer acquisition and the percentage growth in the total customer base. This analysis will help the company understand the effectiveness of its customer acquisition strategies and track the expansion of its customer base over time, providing insights for future marketing and retention efforts.

 Customer Base = 
 
var year = SELECTEDVALUE(Orders[Order Date].[Year])

-- for current year

var churned = if(year=2019, 
            CALCULATE(COUNTROWS('Retention Table'),FILTER('Retention Table','Retention Table'[Last Purchase Date]<year)),
            CALCULATE(COUNTROWS('Retention Table'),FILTER('Retention Table','Retention Table'[Last Purchase Date]<=year))
            )
            
var new = CALCULATE(COUNTROWS('Retention Table'), FILTER('Retention Table','Retention Table'[First Purchase Date]<=year))

var current_base = new - churned

-- for previous year

var previous_year = year-1

var previous_churned = if(previous_year=2019, 
            CALCULATE(COUNTROWS('Retention Table'),FILTER('Retention Table','Retention Table'[Last Purchase Date]<previous_year)),
            CALCULATE(COUNTROWS('Retention Table'),FILTER('Retention Table','Retention Table'[Last Purchase Date]<=previous_year))
            )
            
 var previous_new = CALCULATE(COUNTROWS('Retention Table'), FILTER('Retention Table','Retention Table'[First Purchase Date]<=previous year))
 
 var previous_base = previous_new - previous_churned
 
return 
if(year = 2016, " ",(current_base - previous_base)/ previous_base)

<img width="458" height="227" alt="y-o-y new customer" src="https://github.com/user-attachments/assets/a3c8bf24-445f-4ac4-93a9-e07279fe650c" />

Retention Table = 

SUMMARIZE(Orders,
           Orders[Customer ID],
           "First Purchase Date", min(Orders[Order Date].[Year]), 
           "Last Purchase Date", max(Orders[Order Date].[Year]))

 <img width="1918" height="1028" alt="retesion table" src="https://github.com/user-attachments/assets/0d904c7d-f4b8-44b7-b053-3c7dc67b256b" />

 ### Q40 Client wants a visual where he will have authority to select the profit % and only the country that lies in that profit % range should be displayed.

 Profit Percentage = ([Profit Measure]/[Sales Measure])*100
 
Dynamic Profit = 

var minimum = min('Profit Slider'[Profit Slider])

var maximum = max('Profit Slider'[Profit Slider])

return
if ([Profit Percentage]>=minimum&& [Profit Percentage]<=maximum, [Profit Percentage], BLANK())

<img width="937" height="348" alt="country in profit range" src="https://github.com/user-attachments/assets/3a1eccc3-20f5-48d3-ae95-fc440b89e696" />




















































































