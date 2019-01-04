# Linear Regression
   ### It takes continuous data to figure out the best fitting line
                        (OR)
   ### A linear regression is a linear approximation of a casual relationship between two or more variables



Regression Model has been prepared by using <b>Gretl Analysis Tool</b>.

Using this regression model, <b>Salary</b> has been predicted w.r.t. <b>Experience</b> in years.

<b>Background Elimination Method</b> has been used to find the desired variables that could be used in modelling.

## Variable Selection Process

A model will result with the most accuracy only if the variables used are valuable. To find the valuable variables, we need to look after a few statistical terms. 
   1. <b>p-value :</b> It should be less than 0.05, as only 5% error can be tolerated. Lesser the value, more the accuracy.
   2. <b>Adjusted R-squared value :</b> Adj. R-squared value lies between 0 and 1. Closer to 1, more the accuracy
   3. <b>Akaike criterion value :</b> In this case, lesser the value, more the accuracy.
   
 ## Background Elimination Method
 
   - In background selection method, all the variables are considered at once and then the varaibles with the highest p-value ( < 0.05) will be eleminated.
   - After every elemination, the model need to be recreated for the effect on the model.
   - When we are left with the variables having p-values ( < 0.05 ), those variables will be considered for the model development.
   
 ## Modelling
   Finally, the <b>Salary</b> and <b>Experience in years</b> are the two variables found related <b>(also known as Correletaion)</b> to produce the best fitting line for the further salary predictions.  
   Where, Experience is independent variable and Salary is dependent variable.
 
 
   
  
  
  
