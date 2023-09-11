# Data_Modeling_Project

## Introduction :

In this exercise, I have undertaken a data modeling project for Global Super Store.

## Scenario :

Global Super Store have collected huge amounts of data from their business operations within the USA. This data has been collected in an Excel sheet with the following data fields: 

- Order ID and Order Date.

- Ship Date and Ship Mode.

- Total Cost and Product Price.

- Customer ID, Name and Contact Details. 

- City, State, Country, and Postal Code.

- Product ID, Category, and Sub-Category.

- Product Name and Quantity.

- Discount, Shipping Cost and Order Priority.


Global Super Store wants to restructure its database system into a proper database management system within MySQL. They also want to analyze existing data to understand their business performance and progress. 

Help Global Super Store to restructure and analyze its database by carrying out the following tasks.

## Instructions:

To complete these tasks, I have used MySQL Workbench for database modeling and Tableau for data analysis. 
<br><br>
**Step 1: Create an ER diagram**

- Your first task is to use the visual data modeling tool in MySQL Workbench to create a suitable ER diagram for the Global Super Store. 
- Make use of the data fields within the company Excel file as stated in the scenario. Feel free to add more entities and attributes if required. Make sure that your tables are normalized to conform with the three fundamental normal forms.
- The following ER diagram illustrates an adequate relational schema for Global Super Store’s database :

![image](https://github.com/himanshu1295/Data_Modeling_Project/assets/106751126/933c168d-c0d8-4348-8bf8-e611e6a3f0b4)

**Step 2: Implement the data model**
- Use MySQL Workbench’s forward engineer feature to implement the Global Super Store data model inside the MySQL server.
- You need to select that Database tab, then select the forward engineer method in MySQL Workbench to implement Global Super Store’s data model inside the MySQL server as shown below.

![image](https://github.com/himanshu1295/Data_Modeling_Project/assets/106751126/cdc7b908-69b4-4b65-a523-8e5ac1c45587)

- Once you have completed the required steps using the wizard, you need to carry out the final Commit Progress step to confirm that each task was executed.
- Click Close to close the wizard. The new database schema should now be created in the MySQL server as shown below :
![image](https://github.com/himanshu1295/Data_Modeling_Project/assets/106751126/f4e877bc-169b-4592-ac55-26a338079a64)

**Step 3: Create a Star and Snowflake Schema**

- The marketing department at the Global Super Store Company wants to build a campaign to promote the company’s products within the USA. 
- First, they need to understand the company’s performance in this market by analyzing their sales data. They are interested in data related to products, locations and times only. 
- Help them out by creating a Star schema that includes relevant fact and dimensions tables with relevant attributes and data types.
- The following ER diagram illustrates an adequate Star schema for a Global Super Store dimensional data model :

![Star Schema Global Super](https://github.com/himanshu1295/Data_Modeling_Project/assets/106751126/8d6a74d5-ddfe-477f-84bd-8535252c650c)

- The following ER diagram illustrates an adequate Snowflake schema for a Global Super Store dimensional data model :

![Snowflake Schema Global Super](https://github.com/himanshu1295/Data_Modeling_Project/assets/106751126/0db49d19-cc17-4317-8bec-794c4b9a392e)

**Step 4: Create a map chart**

- Use Tableau to investigate Global Super Store’s sales in the USA. Create a map chart that shows sales in different states within the USA. 

- If you roll over a state, then you should be able to view the state name and sales figure as shown below :

![image](https://github.com/himanshu1295/Data_Modeling_Project/assets/106751126/044b8eb4-f22c-4af0-8d4d-85aa2924c297)

**Step 5: Create a bubble chart**

The Global Super Store needs to check its profits within the USA. To help them out, create a bubble chart in Tableau. Call it “Profits in USA”. 

If you roll over a bubble, you should be able to view the following information, as shown in the screenshot below:
- State name,
- Quantity sold,
- Profits,
- and shipping cost.

Your chart should look similar to the following example:

![image](https://github.com/himanshu1295/Data_Modeling_Project/assets/106751126/15b3d78f-dbc4-49f5-9e7e-252a0ff2316d)

**Step 6: Create a line chart**

- The Global Super Store wants to view sales trends in the USA over the last 4 years. Create a line chart in Tableau for states with Sales of more than $40000. Call it “Sales Trend in the USA”, as shown below :

![image](https://github.com/himanshu1295/Data_Modeling_Project/assets/106751126/3ed6d663-b85c-418b-b8c3-603c0f46e19d)

**Step 7: Create an interactive dashboard**

- Create an interactive dashboard that includes the charts produced in tasks 4, 5 and 6. Name it ‘Sales and Profits in the USA’. If you click on a state, you should be able to view relevant sales and profits information as shown below :

![image](https://github.com/himanshu1295/Data_Modeling_Project/assets/106751126/eb86b61f-84b7-4fd0-8251-6e5342dbbe2e)

## Conclusion

I have created an ER diagram for Global Super Store and used MySQL Workbench’s Forward Engineer feature to implement the ER diagram in a MySQL database. I have also developed a dimensional data model for the Global Super Store. I have also analyzed data with relevant charts using Tableau and built an interactive dashboard.
<br><br>
