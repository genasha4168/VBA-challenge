#
# VBA-challenge
Module 2 Challenge

#
# Background
You are well on your way to becoming a programmer and Excel expert! In this homework assignment, you \
will use VBA scripting to analyze generated stock market data.

#
# Before You Begin
1. Create a new repository for this project called VBA-challenge. **Do not add this assignment to an existing repository**.
2. Inside the new repository that you just created, add any VBA files that you use for this assignment. \
These will be the main scripts to run for each analysis.

#
# Instructions
Create a script that loops through all the stocks for each quarter and outputs the following information:
* The ticker symbol
* Quarterly change from the opening price at the beginning of a given quarter to the closing price at the \
end of that quarter.
* The percentage change from the opening price at the beginning of a given quarter to the closing price \
at the end of that quarter.
* The total stock volume of the stock. The result should match the following image:

![alt text](images/image.png)

* Add functionality to your script to return the stock with the "Greatest % increase", "Greatest % decrease", and "Greatest total volume". The solution should match the following image:

![alt text](images/image-1.png)

* Make the appropriate adjustments to your VBA script to enable it to run on every worksheet (that is, \
every quarter) at once.

**NOTE** \
Make sure to use conditional formatting that will highlight positive change in green and negative change \
in red.

**Other Considerations**
* Use the sheet `alphabetical_testing.xlsx` while developing your code. This dataset is smaller and will allow \
you to test faster. Your code should run on this file in just a few seconds.
* Make sure that the script acts the same on every sheet. The joy of VBA is that it takes the tediousness \
out of repetitive tasks with the click of a button.