# Prediction-of-Product-Sales
Author: Duwain Hofmeester

Business problem:
Predict product sales based on independent variable such as Outlet size, product weight

Data:
Dataset name: sales_predictions_2023.csv
 #   Column                     Non-Null Count  Dtype  
---  ------                     --------------  -----  
 0   Item_Identifier            8523 non-null   object 
 1   Item_Weight                7060 non-null   float64
 2   Item_Fat_Content           8523 non-null   object 
 3   Item_Visibility            8523 non-null   float64
 4   Item_Type                  8523 non-null   object 
 5   Item_MRP                   8523 non-null   float64
 6   Outlet_Identifier          8523 non-null   object 
 7   Outlet_Establishment_Year  8523 non-null   int64  
 8   Outlet_Size                6113 non-null   object 
 9   Outlet_Location_Type       8523 non-null   object 
 10  Outlet_Type                8523 non-null   object 
 11  Item_Outlet_Sales          8523 non-null   float64

Methods
Check for duplicate rows- Duplicate rows can impact the qaulity of your analysis and lead to decrease insights, and potentially cause erros in machine learning. 
Sample ![image](https://github.com/duwain/Prediction-of-Product-Sales/assets/53176086/73ce8ad4-82cc-4dd1-803e-c1beb9988dc4)
Check for Null values in the categorical columns and the numeric columns. If any null values are found in the categorical columns we will replace it with the most occuring value 
If any null values are found in the numerical columns we will replace it with the mean vaule

Model metrics
Results for training data:
  - R^2 = 0.696
  - MAE = 669.263
  - MSE = 900145.308
  - RMSE = 948.76

Results for testing data:
  - R^2 = 0.592
  - MAE = 737.147
  - MSE = 1124362.519
  - RMSE = 1060.36

Not well enough as the training and testing accuracy is low and the RMSE is high. 

Recommendations:
Recommendations to improve the model would be to use a bigger dataset, 
Try different parameters to find the highest accuracy, 
perform feature enginerring 

Limitations & Next Steps
Next steps would be to train more models to find a better accuracy.

For further information
Duwain4@gmail.com
