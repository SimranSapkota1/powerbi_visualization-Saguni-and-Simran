# powerbi_visualization-Saguni-and-Simran
This project includes the dashboard overview of revenue model and sales order throughout the Quarter of the year 2019.

Power Bi Desktop Interpretation

The following project showcases the data visualization of sales dataset for foods and beverages industry. The dataset is collected from Kaggle with the objective to visualize the data and the data encompasses the sales information of the year 2019 and presents insights on product category, sales trend, product performance etc. Dataset link https://www.kaggle.com/datasets/krishnasharangam/food-and-beverage-sales-data

1.	Overview of the Sales Data:
The Sales data for foods and beverages comprises of information including Quantity, Product category, Product Group, Salesperson etc. The key objective of this visualization is to understand how revenue model and sales order on food and beverage is affected by these factors such as channel, Product Category, Product Group, Sales person etc. throughout the month and Quarters. The following are the work performed for this dataset.

i.) Model relationship Management: The model relationship in powerbi shows how one data is structured and related to other datas. The dataset contains one to one relationship as the information in the dataset only appears once. Therefore, the first step we followed after cleaning the data is creating model view of one table with other table sheets within the given dataset frame

ii.) Implementation of Dax Formulas: Dax formulas can be an effective way to interpret the complex problem in the dataset or to understand the exisiting business problems. We created a Sales Amount column, and from the new measure tool in table view through Formula Sales Amount = Sheet1[Quantity]* Sheet1[UnitPrice]. This created a total Sales Amount. This helped in the proper visualization and interpretation of the given datas in dashboard. 

2.	Key Insights

i.)	Revenue Model and Orders: The visualization shows the Revenue model and orders by month and Quarter, by Salesperson, by Product group etc. in Quarter 1, 2, 3 and 4. This revenue affect can help in making decision on which determinants the improvement is needed

ii.)	Sales Trends over the years: The visualization also presents insights on how the sales trends changes over the year through factors such as Sales Person, Product Category and group. Analyzing such trends helps in better understanding of the seasonal patterns and overall fluctuation of the model.

iii.)	Product Segmentation: The product in this report are categorized into foods and beverages and it is grouped into its own food and beverage varieties like Wheat flour, Oil, Yeast, Sugar, Grounded Coffee, Vegetables, wine, Energy drink etc. After visualization it helped to clearly emphasize on the targeted customers and to understand which product category should be more emphasized upon to increase the revenue or sales order.

3.	Performance Measurement

To measure the performance of the data, we used various tools like Bar chart, Clustered Bar Chart, Donut Chart, Column Chart, Card etc., and it enables us to easily interpret and understand the dataset information through this charts and tools. These tools can be helpful for profitability measurement, to track key performance indicators of Sales revenue, average order per product, customer acquisition and retention, loss throughout the Quarters and months. Similarly, we can measure sales revenue or customer purchase on the basis of region, product categories and varieties to identify high profit areas so that maximum of resource can be used for customer retention 

4.	Conclusion
Therefore, the visualization of sales data using Power BI Desktop provides valuable insights on enabling stakeholders to make informed decision and for organization to adapt to changing marketing dynamics and to drive sustainable growth of a company. By clear understanding of the data - driven insights they can utilize their resources to grab and capitalize their investment on more marketing opportunities for future.
