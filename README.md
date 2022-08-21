Objective: 

Create a dashboard to compare all the parameters mentioned above for different countries, to strategize market penetration and to target new customers.

Datasets:

Primary Dataset – Insurance Sample Dataset

Secondary Dataset – Global Financial Development Database

Note: Use Data Blending with Relationships between Country Code, Country, and Year

Steps to Perform: 

Create a geographic map showing the countries' fields. Color the map based on the income column from the secondary dataset

Include income group filter in the dashboard

Include a webpage to show data from the world bank webpage driven by an URL action from a geography graph

The country names in the map will act as the trigger

https://en.wikipedia.org/wiki/Country

 

Create a KPI Table to show the comparison between the selected period and the period prior to the selected one

Create two parameters for Year Selection and Category Selection

Category parameter includes life insurance share, market share, penetration, ratio of reinsurance accepted, and retention ratio

Create a calculated field to calculate the Growth %

Create a table to show these values

Title should be updated based on the category selection

 

Create Growth Indicator Shapes based on the Growth %

Growth indicator displays Negative, No Change, and Positive as values and corresponding shapes against it

 

Create a trend line to show the selected category values

The line shows an arrow or triangle at the last mark

 

Create a dashboard filter for income group to be applied for all charts with the filter action enabled in the map as well

 

Formatting should be done appropriately


Comparison of Sales Region wise

Objective: Help the organization by creating a dashboard to visualize the sales comparison between two selected regions.

Datasets: Sample Superstore

 

Steps to Perform: 

Select Sample Superstore as Dataset  

Use Sample Superstore Dataset

Select Data

Use Group by from Data Source Table on a Folder to create a folder to segregate the required data for Customer Name and Order ID inorder to organize the data thoroughly.

Create a hierarchy called Location for the variable Country. 

Create two parameters: Primary Region and Secondary Region with all regions listed in them. Here, primary and secondary region are the two regions where the sales are being compared.

Create Parameters for Primary Region and Secondary Region

Create a Calculated Field for both Primary Region and Secondary Region

Create a First Order Date

Create a Calculated Field and name it as the First Order Date

Create a dashboard

Align all sheets in the dashboard

Partition the dashboard to display the below details of Primary Region and Secondary Region

First Order Date
Total Sales
Average Sales per Order
No. of Customers
No. of Orders
No. of Products in Sale

