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

## Q5-   To  Boost their business, Global Superstore thought of planning their business quarterly. For that they need to know their overall sales for each quarter.

<img width="1920" height="1032" alt="Screenshot 2025-07-26_5" src="https://github.com/user-attachments/assets/96266b47-8e1d-4d04-8bb9-01dee264722c" />

# Q6-    After these visuals are built, management would like to incorporate a feature allowing them to select specific segments and categories. This functionality should dynamically adjust all the graph values based on the selected category and segment, providing a tailored view of their data.

To incorporate this feature we have used slicers of Segment and Category. As shown in below snap we see that Segment selected is Consumer and Category is Office Supplies.

<img width="203" height="362" alt="Slicers" src="https://github.com/user-attachments/assets/1d02b94a-4cd1-486f-ae78-904d4c2c9617" />

and all the visual will changes as per these selection.

<img width="1919" height="1032" alt="Screenshot 2025-07-26_6" src="https://github.com/user-attachments/assets/7407497b-c1e3-4ecb-bc05-0b0f6743cfb5" />

The company is pleased with the dashboard you have built so far; however, the company has suggested some new additions and some editing.
 
## Q7 The CEO observed that the total sales and total profit values fluctuate with interactions on the graph. They now require a fixed value for these metrics, separately from the dynamic values that change with visual interactions, so that they can always have an eye on the totals.

For this we have to disconnect the visual's interaction with all the visuals. This option is avaulable in Formate tab as Edit Interactions.We have to select None option wich is gray in snap.

<img width="1919" height="1030" alt="Edit interaction" src="https://github.com/user-attachments/assets/0fe7e4b6-b663-4bf8-9b6b-f9b83f690a96" />

so because of above slection the visuals dont get filter as per the slicers selection.

<img width="1122" height="536" alt="Edit interaction-2" src="https://github.com/user-attachments/assets/fafc75f7-43b2-49d6-9dc4-ee9b88ce5ba8" />

## Q8 In 2016, the company set a 5-year target to achieve an overall sales goal of $25 million and a profit goal of $10 million by the end of 2020. According to this plan, by the end of 2019, the company should have reached a sales target of $20 million. This equates to approximately $1.7 million in sales per month(collectively) from 2016 to 2019.As the company is far beyond the target to be achieved, the company is now interested in seeing for each month collectively (2016-2019) fluctuations of our sales performance from the target help company visualise this.Company is also interested in seeing a visual of how far they are from the set profit target.

<img width="1919" height="1030" alt="Target" src="https://github.com/user-attachments/assets/b0242656-975c-4698-b599-245d48da7b51" />
<img width="1917" height="1029" alt="away from Target" src="https://github.com/user-attachments/assets/3f4f156b-1884-48e2-814f-27624b4ddff1" />

## Q9 Management has identified an operational challenge: when selecting any slicer, transitioning back to the default view becomes cumbersome and time-consuming. To streamline this process, they have requested the implementation of a dedicated button. This button will enable them to swiftly return to the default view with a single click, eliminating the need to manually deselect each slicer. This enhancement aims to enhance user experience by providing a more intuitive and efficient navigation option within the dashboard.

We have provided clear button on slicers with which user can deselect all the slicers.

<img width="203" height="362" alt="Slicers_2" src="https://github.com/user-attachments/assets/fa8dcf62-54fe-4be6-96a3-f6801e267bad" />

## Q10 Global Superstore has been frequenting your desk with numerous minor queries, causing interruptions to other ongoing projects within the company. In response to this challenge, your boss has tasked you with developing a solution that empowers end-users (Global Super Store) to obtain answers to their questions independently. By implementing a user-friendly tool or feature, such as a searchable database or an interactive FAQ system, users can simply type their queries and retrieve instant responses. This initiative aims to enhance efficiency, reduce dependency on direct support, and allow for smoother workflow across all projects.

For this we have provided in-build feature of power bi that F&A Ask Anything button.

<img width="1290" height="204" alt="ask anything" src="https://github.com/user-attachments/assets/05d688bf-e332-4fd2-88ce-27544fa3d144" />

Once you click on this button you will get window as shown in below snap.

<img width="1505" height="728" alt="ask anything_2" src="https://github.com/user-attachments/assets/797d5ccd-65ec-40f3-aada-56e097fffc1d" />

## Q11 Global Super Store seeks to enhance its regional performance analysis and resource allocation strategy. They want to understand which geographic country is driving high sales and where profitability is strongest. Rather than bar chart or line chart they need some visuals in the form of maps,The visuals should be very understandable and interactive.
<img width="1919" height="1031" alt="sum of profit by country" src="https://github.com/user-attachments/assets/921b1b2e-b934-4661-be0e-4c8b7d6483ff" />


## Q12 The client has specified some visualisation specifications to you: -He wants that in the visuals that will display the profit chart, the colour of the country with lowest profit should be red and colour of country with the highest profit to be green and in between values to be coloured as gradient.For the visual that will be displaying the sales, client have made a request to show that the countries where sales are <80,000 should be coloured dark red, between 80,000 to 200000 it should be red, between 200000 to 700000 it should be green, and above 700000 it should be golden.

 <img width="1919" height="1031" alt="sum of sale by country with color" src="https://github.com/user-attachments/assets/9738dcf3-5f47-47f9-8efe-079d2741304e" />

 <img width="1916" height="1030" alt="sum of sale by country with color_2" src="https://github.com/user-attachments/assets/bb4e3c51-7ebd-4480-a291-efc5de6f5f96" />


 ## Q13 The client is happy with your work and wants to continue with you for further Business Intelligence. They have produced a quick requirement. The company core team has a meeting and they must discuss some topics. They have advised the BA team to give their input for this meeting which is scheduled in the next 1.5 hours. BA Team approached you to build some visuals, however due to time constraint they want you to build those visuals in next 25 minutes only, so that rest 1 hour can be spent by BA team on those visuals to form some inputs. ·   	Global Super Store needs to understand which regions are driving the highest sales and profitability. Develop a visual that clearly depicts the sum of sales and profit across different regions.

 <img width="1919" height="1031" alt="sum of sale and profit by region" src="https://github.com/user-attachments/assets/3d552f27-1e9b-45fe-afb0-a51ca9f77c08" />































