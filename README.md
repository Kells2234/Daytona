# Daytona 500 Caution Laps

Number of caution laps in the past 7 Daytona 500 races

"""Find the minimum laps run under caution of seven values."""

number1 = int(input('Enter first integer:  26 '))
number2 = int(input('Enter second integer:  31 '))
number3 = int(input('Enter third integer:  40 '))
number4 = int(input('Enter fourth intger: 37 '))
number5 = int(input('Enter fifth integer: 47 '))
number6 = int(input('Enter sixth integer: 39 '))
number7 = int(innput('Enter seventh integer: 40 '))

minimum = number1  

if number2 < minimum:
    minimum = number2

if number3 < minimum:
    minimum = number3
    
if number4 < minimum:
    minimum = number4
    
if number5 < minimum:
    minimum = number5
    
if number6 < minimum:
    minimum = number6
    
if number7 < minimum:
    minimum = number7

print('Minimum value is', minimum)
