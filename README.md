# 12MonthsOfSales_Python_PBI_Analysis
12 Months Of Sales analysis project using Python and Power BI

<h3>Tools Used</h3>

- Data - ( 12 CSV files for each month )
  
- Data Cleaning & Analysis - Python - Visual Studio Code - Jupyter notebook

- Data Visualization - Power BI


<h3>Questions</h3>


- What is the City with the most sales? 
  
- What time should we display advertisements to maximize the likelihood of customers buying products? 

- What products are most often sold together?

- What product sold the most? Why do you think it sold the most? 


<h3>Python Code</h3>
<h4>Cleaning and Preparing the Data:</h4>

- Merge all the 12 months' sales data together in one csv file and save it (all_data.csv)
  
- drop all nan value, delete all rows that have Or as value

- Convert all data types

- Create month name column ( Month )  by converting (MonthNr) to the name of the month

- create sales column by (Quantity Ordered) * (Price Each)

- Create a City column from the Purchase Address

- Convert the Order date column to datetime type and create an hour column from it 

<h3>Summary of Findings</h3>

<p>- Find out that September is the best month for sales and that is true because people buy a lot of gifts in that month for the new year. the second best month is November because it has black Friday </p>

<p>- Find out that San Francisco is the best City for sales. Maybe because Silicon Valley needs more electronic products than other cities tech advertisement is better or people have more money to spend on tech products 
We can also see that Portland is the less city</p>

<p>- So the best Time for displaying ads to optimize sales is 7 PM which is the time after finishing work and going home that is the time to start watching TV </p>


<p>- We can increase sales more by creating offers that help the clients purchase those products(iPhone, lighting charging cable) as an offer package.</p>


<p>- (AAA Batteries(4-pack)) is the best product from the amount that has been sold, we can find out that the price of the product makes a huge difference, the more cheap the product the more the amount increases but that not the only reason as we can see the value of the product also makes a big difference.</p>

<h3>Sales Overview Dashboard</h3>
The sales Overview dashboard which allows filtering data for each City and Product, shows graphs..
<p>
<a href="https://app.powerbi.com/view?r=eyJrIjoiMDY4M2IxOTItNWQ5Ni00NjY5LWI4MTgtNzNlOWFiMDhkZDU2IiwidCI6IjIzZGI2ZTA2LTA1YzQtNDg5ZC1iMTM2LWNiYTk0YThlNmYzNiIsImMiOjh9" target="blank">
Click to open the dashboard and try it out!
</p>

![12 months of sales dashboard](https://github.com/khaled-gohar/Python_PBI_12MonthsOfSalesAnalysis/assets/133038582/b4db0c44-02a3-4c9f-b89a-2a3d1bf34950)

