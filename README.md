# Multiple-Linear-Regression
Implementation of Multiple Linear Regression

Once you run the code in Python, you’ll observe three parts:

(1) The first part shows the output generated by sklearn:
Linear Regression in Python
This output includes the intercept and coefficients. You can use this information to build the multiple linear regression equation as follows:

Stock_Index_Price = (Intercept) + (Interest_Rate coef)*X1 + (Unemployment_Rate coef)*X2

And once you plug the numbers:

Stock_Index_Price = (1798.4040) + (345.5401)*X1 + (-250.1466)*X2

(2) The second part displays the predicted output using sklearn:
Linear Regression
Imagine that you want to predict the stock index price after you collected the following data:

Interest Rate = 2.75 (i.e., X1= 2.75)
Unemployment Rate = 5.3 (i.e., X2= 5.3)
If you plug that data into the regression equation, you’ll get the same predicted result as displayed in the second part:

Stock_Index_Price = (1798.4040) + (345.5401)*(2.75) + (-250.1466)*(5.3) = 1422.86
