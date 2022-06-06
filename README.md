# MechaCar_Statistical_Analysis
Module 15 Challenge 

Deliverable 1: Linear Regression: 

<img width="1680" alt="Screen Shot output from the linear regression" src="https://user-images.githubusercontent.com/97544078/171928076-357baab8-013d-4938-a6ad-3c74f0bd8f1e.png">

  Vehicle_length, vehicle_weight and ground_clearance are deemed significant factors based on the p-value established.  When these measures go up,      vehicle MPG goes down. This a negative relational correlation. 

  The slope is Intercept and cannot be considered zero.  According to multiple regression models p-value is smaller than .05 the significance level.

  The linear model does an adequate job predicting mpg. Multiple r-squared .7149 or 71% of the time, these variables are able to predict mpg values correctly.  
  
  Deliverable 2: Summary Statistics on Suspension Coils
  
  <img width="1680" alt="Screen Shot Deliverable 2 Summary Statistics on Suspension Coils" src="https://user-images.githubusercontent.com/97544078/172187178-45494be5-5a3a-4018-a4db-5904501be62e.png">

  
  The overall calcuated for all three lots is under the specifications. Calculated seperatelt, lots 1 and 2 are within the specifications. However, Lot 3 calculated variance exceeds the specifcation amount. 
  
  Deliverable 3: ## T-Tests on Suspension Coils
  
  <img width="1680" alt="Screen Shot T tests Deliverable 3" src="https://user-images.githubusercontent.com/97544078/172188395-6dbb59a4-e5ce-4032-827a-84f9061de8a9.png">

  All lots are statistically significant. They are not equal to 1500 at 1497.507. The P-Value is .06028 and therre less than the significance level of .05. 
  
  Delivereable 4: Study Design: MechaCar vs Competition
  
  I'd like to conduct a study based on the safety rating on MechaCar against it's competitors in correlation to horsepower. Collecting data on various car manufacturer's accident reports and the vehicle's horse power. My hypothesis is that cars with a higher horse power equal greater speeds and therefore an increased number of accidents. I would perform a linear regression using the cor() function to measure the correlation between greater horse power and lower safety rating. It would be would be an indirectly proportial relationship, meaning as horse power goes up, safety goes down. 
  
  The null hypothesis would be not enough data to suport statistical significance of .05 or less. 
