# Coding Dojo Project 1: Predicing Sales Volume
The purpose of this project was to use individual item sales data to predict that items sales volume in a specific store/outlet. 

## Data
There were 8523 data points. With the following characteristics: 

Item_Identifier: Unique Item Identifier

Item_Weight: Item Weight

Item_Fat_Content: If the item was low fat or regular

Item_Visibility: Percentage of the area of all products in the store that contains this item

Item_Type: Item category

Item_MRP: Maximum Retail Price

Outlet_Identifier	ID: ID of Store/Outlet

Outlet_Establishment_Year: Year the outlet was established

Outlet_Size: Categorized physical size of the outlet

Outlet_Location_Type: Categorized location type of the outlet

Outlet_Type: Categorized type of outlet (supermarket or grocery store)

Item_Outlet_Sales: Sales of the item, this is the target variable 


## Data Wrangling 
There were two variables with nulls: Item_Weight and Outlet_Size. 

Item_Weight: was able to replace null values with other lines that contained the same item and a weight value.

Outlet_Size: had to drop rows with null values, there was no way to confidently replace. Reduced sample size to 6,113 


## Visualizations


![image](https://user-images.githubusercontent.com/106602444/189394440-0a8b53ac-d6d5-4162-a341-2e9351eef293.png)
Reviewing which item categories have the most sales: Household and Fruits and Vegetables have the highest Total Sales 


![image](https://user-images.githubusercontent.com/106602444/189394575-ca241397-b50e-4515-8134-4952667c2895.png)
Which Outlets have the greatest portion of Total Sales: Outlet 027


![image](https://user-images.githubusercontent.com/106602444/189394731-6babf5d6-c001-47e1-afaf-a2869a11686a.png)
Difference between Low Fat and Regular Sales by Category: In general Regular has more sales. 

![image](https://user-images.githubusercontent.com/106602444/189394860-e06ee585-38c8-49a4-ae70-6ff4c5209d93.png)
Histogram of Item Outlet Sales by Outlet, to view the distribution and see the differences by Outlet 

![image](https://user-images.githubusercontent.com/106602444/189394979-043cbb82-b860-4e24-8a5b-eecf189e445a.png)
Correlation between all variables. We see high correlation between Visibility, Outlet Size, and Item Price vs Item Outlet Sales



## Libros de complemento y valor agregado

https://clauswilke.com/dataviz/
