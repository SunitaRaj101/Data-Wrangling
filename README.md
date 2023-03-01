# Data-Wrangling/ Data Preprocessing/ Data Cleaning
It is the process of converting data from the initial format to format that may be better for analyesis.
1)Identify and handle missing Values
2)Data formating
3)Data Normalization
4)Data binning 
5)Turning Categorical Values into numeric values

# 1)Identify and handle missing values:
for detectng missing values
.isnull() and .notnull()
Deal with missing data:-
i)Drop data-drop whole row/drop the whole column
ii)Replace data-by mean/frequency/replacement based on other function

# 2)Data Formating:
Making sure that all data is in the correct format (int,float,string)
.dtype() for check and .astype() for change the data type
Sktandardization- process of transforming data into a common format.

# 3)Data Normalization:
Normalization- process of tranforming values of several variables into a similar range. It include scaling the variable.
By simple feature scaling, min-max, Z-Score

# 4)Data Binning:
Binning- process of transforming continous numerical varibles into discrete categorical 'bins' for grouped analysis.

# 5)Turning categorical values into numeric values:
because statistical models can not take Object/String as input.
By One Hot Encoding and Dummy encoding.
https://towardsdatascience.com/encoding-categorical-variables-one-hot-vs-dummy-encoding-6d5b9c46e2db#:~:text=A%20dummy%20(binary)%20variable%20just,or%20inclusion%20of%20a%20category.&text=Image%20by%20author)-,In%20one%2Dhot%20encoding%2C,0%5D%20vector%20of%20size%203.
