# House-Price-Predictor

**Purpose and Technologies:**
The following program uses **Python**, **Matplotlib**, **Numpy**, **Sympy**, **Pandas**,and **sci-kit** to predict house prices in the city of Boston. 

**Procedure:**
1. Formulate a question 
2. Gather the data
3. Clean the data
4. Explore the possibilities and correlations
5. Model the data graphically
6. Evaluate the price within a function

**Algorithm:**
I implemented a **_multivariable linear regression model_** to forecast house prices. This method, also known as multiple regression, is a statistical technique that uses several parameter variables to predict an outcome of a response variable. In this case, I extracted several variables from the dataset, including house prices, crime rates, age, proximity to water, tax, and more, to make my model more accurate. I picked out which variables had a low p-value corresponding to the initial price data, and also other conditions that had logical sense for this particular problem. I then applied my knowledge in distribution methods, standard deviation, MSE, RMSE etc ... to do a final calculation of what the house price would be. 

Additionally, I take into account issues like _Multicollinearity_ in linear regression, to make sure my program is as precise as possible. 

**Data Visualization Work:**

Below is a model to demonstrate the different correlations between the variables in the dataset. 
![correlation](https://user-images.githubusercontent.com/31941027/108793485-9a82db80-7551-11eb-9f41-c219024a38a0.PNG)

Another graphical representation of all the correlations between each variable; includes a regression fit
![image](https://user-images.githubusercontent.com/31941027/110256354-8209bc80-7f66-11eb-866f-3128fd603d4c.png)

Statistical Analysis of the p values and coefficients for specific conditions:

![image](https://user-images.githubusercontent.com/31941027/110256454-fd6b6e00-7f66-11eb-8d43-8cbc805b3aa3.png)
