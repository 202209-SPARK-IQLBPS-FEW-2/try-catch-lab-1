# Introduction
In this lab, you are required to get the month name by passing in the number of the month. If the month exists then you will return the month name. If not you will catch the error and throw a custom error. 

# Instructions:

1- Declare a function called `getMonthName` that takes `monthNo` as a variable. 

2- Inside the function, you should have an array of the 12 months of the year. 

3- Add an if statement that checks the month number and returns its name if it's there. If not then it should throw a custom error.

4- Outside the function write a try ... catch statement. Run the function and catch the error. 

***Remember to adjust the month numbers according to the array index. 
Jan is the first month. Dec has number twelve not eleven**


### Example of running the code:

|  calling the function | result   |
| ------------ | ------------ |
| getMonthName(1)  |  'Jan' |
| getMonthName(12)  |  'Dec' |
| getMonthName(7)  |  'Jul' |
| getMonthName(20)  |  'Wrong month number' |
