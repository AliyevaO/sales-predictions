## Sales predictions

In this project we are making predication for item sales in different stores.

Data Dictionary for this dataset:

* **Item_Identifier**	- Unique product ID
* **Item_Weight**	- Weight of product
* **Item_Fat_Content** - Whether the product is low fat or regular
* **Item_Visibility** -	The percentage of total display area of all products in a store allocated to the particular product
* **Item_Type**	- The category to which the product belongs
* **Item_MRP** -	Maximum Retail Price (list price) of the product
* **Outlet_Identifier**	- Unique store ID
* **Outlet_Establishment_Year**	- The year in which store was established
* **Outlet_Size**	- The size of the store in terms of ground area covered
* **Outlet_Location_Type** -	The type of area in which the store is located
* **Outlet_Type** -	Whether the outlet is a grocery store or some sort of supermarket
* **Item_Outlet_Sales**	- Sales of the product in the particular store. This is the target variable to be predicted.
**********************************************************************************************************************************

**Some of visualizations made to analyse Data in this project.**


![](Images/Sales%20of%20Products%20in%20Different%20Type%20of%20Outlets.png)

Highest Sales of Products has Supermarket Type 3.
It is 
* 37% more than Supermarket Type 1. 
* 46% more than Supermarket Type 2
* 91% more than Grocery Store



![](Images/Total%20Sales%20by%20Store.png)

OUT027 has $ 3,453,926 of total sales.

This store is from Outlet Type – Supermarket Type 3.

It’s location is Tier3.

**Conclusion:** The most effective sale produced in Supermarket Type 3, that located in Tier3 area and belongs to Outlet Store - OUT027. 


 Visibility comparison of Product Categories in all stores and in Store OUT027

![](Images/Relationship%20Between%20Product%20Category%20and%20Product%20Visibility.png)

![](Images/Visibility%20of%20Different%20Product%20Categories%20in%20Store%20OUT027.png)

Most of the Product Categories in Store OUT027 have less visibility that average in all stores. 

*****************************************************************************************************************************
In my project I used 3 different prediction models: Linear regression, Decision Tree, Random forest model. Result of used models:

**Linear regression model:**
* Training performance - 0.562
* Testing performance -  0.567 
* Testing RMSE - 1092.861

**Decision Tree Model:**
* Training performance - 0.604 
* Testing performance - 0.595 
* Testing RMSE - 1057.443

**Random forest model:**
* Training performance - 0.611
* Testing performance - 0.603 
* Testing RMSE - 1047.069

**After using 3 Maching Learning models we can tell that the best result we get with Random Forest Model. However this results are still low to be able to make a good predictions on our product sales.**
