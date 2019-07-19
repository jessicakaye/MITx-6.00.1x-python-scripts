# PROBLEM 1
#
# Write a program to calculate the credit card balance after one year if a person only pays the minimum monthly payment required by the credit card company each month.
# 
# The following variables contain values as described below:
# 
# balance - the outstanding balance on the credit card
# 
# annualInterestRate - annual interest rate as a decimal
# 
# monthlyPaymentRate - minimum monthly payment rate as a decimal
# 
# For each month, calculate statements on the monthly payment and remaining balance. At the end of 12 months, print out the remaining balance. Be sure to print out no more than two decimal digits of accuracy
# 
# A summary of the required math is found below:
# 
# Monthly interest rate= (Annual interest rate) / 12.0
# Minimum monthly payment = (Minimum monthly payment rate) x (Previous balance)
# Monthly unpaid balance = (Previous balance) - (Minimum monthly payment)
# Updated balance each month = (Monthly unpaid balance) + (Monthly interest rate x Monthly unpaid balance)
#

monthlyInterestRate = annualInterestRate / 12
currentMonth = 1

while currentMonth <=12:
    monthPayment = monthlyPaymentRate * balance
    monthlyUnpaidBalance = balance - monthPayment
    balance = monthlyUnpaidBalance*(1 + monthlyInterestRate)
    currentMonth +=1
print("Remaining balance: " + str(round(balance, 2)))
    
