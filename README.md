# sales_prediction
In this Sales Prediction project, we use various features to predict the sales of a product.  We attempt to assist the retailer understand important properties which 
are crucial in increasing sales.  The features include item weight, item fat content, item visibility, item type and item price.  They also include details of the outlet such as outlet establishment year, outlet size, outlet location type, outlet type and item outlet sales.

The maximum retail price and the fat content in the product have a strong correlation with the product sales.  

For the fat content, there is not a huge difference between the sales of the low-fat and normal goods.  
![image](https://user-images.githubusercontent.com/87332869/137668455-e4aa2db6-d0b2-4451-860d-ea00cba86d8d.png)



As the price increases, the sales increase.








After testing various models, we use a Regression model to predict product sales. # The Regression model has the highest R2 for the testing data (0.48), and an 
R2 of 0.47 for the training data.  Based on R2 alone, it is the better model of the ones utilized.  However, this R2 is not a high R2.  It also has the lowest RMSE for the testing data of 1070.  

