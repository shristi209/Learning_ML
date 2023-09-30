<h2>Description of Linear Regression</h2>
Linear regression is basically the combination of dependent and independent variable.

    For example: y = mx + b
            Here,
                y=dependent variable
                x=independent variable
                m=coefficient
                b=intercepts

The linear regression is divided into 2 types:

    *   Simple Regression
    *   Multiple Regression

**Simple regression** is having one dependent variable like: 
    
    y = mx + b. 

For example: If we are predicting the **price** of House, the price is dependent on the **age** of house. This is simple regression as it is only dependent with one variable, i.e. age. 

Canadian per capita income prediction: 
        https://github.com/shristi209/Learning_ML_100days/blob/main/Supervised/Regression/linear_regression.ipynb

This is how we build the model.

**Multiple Regression** is having many dependent variable like: 

    y = m1 * x1 + m2 * x2 + m3 * x3 + ... + mn * xn + b

    Here,  
        'y' represents the dependent variable.
        'x1, x2, x3, ..., xn' represents the 'n' independent variables.
        'm1, m2, m3, ..., mn' represents the coefficients or slopes associated with each independent variable.
        'b' represents the intercept or constant term.
