In this Sales Prediction project, we use various features to predict the sales of a product.  We attempt to assist the retailer understand important properties which 
are crucial in increasing sales.  The features include item weight, item fat content, item visibility, item type and item price.  They also include details of the outlet such as outlet establishment year, outlet size, outlet location type, outlet type and item outlet sales.

The maximum retail price and the fat content in the product have a strong correlation with the product sales.  

For the fat content, there is not a huge difference between the sales of the low-fat and normal goods.  
![image](https://user-images.githubusercontent.com/87332869/137671462-eea0575a-e624-415c-8dc7-0cd0d813778e.png)




As the price increases, the sales increase.
![image](https://user-images.githubusercontent.com/87332869/137668804-935c1546-9fbe-4f88-9b54-5c204c2245da.png)








After testing various models, we use a Regression model to predict product sales.   The Regression model has the highest R2 for the testing data (0.48), and an 
R2 of 0.47 for the training data.  It also has the lowest RMSE for the testing data of 1070.  Based on R2 alone, it is the better model of the various models that were run.  However, this R2 is not a high R2.  

More work needs to be done to gather data which can improve the values of these models to improve how well they predict sales.  Certain columns were dropped, due to missing values, so better data collection efforts can ensure those columns, which are Item Weight and Outlet Size, can be incorporated in future models.

